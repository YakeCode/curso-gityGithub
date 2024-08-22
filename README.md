

# Curso de Git :fa-git-square: y GitHub  :fa-github:

Nota: A GitHub no se deben subir archivos como imágenes, como buena práctica se deberían subir a una página, como por ejemplo (https://imgur.com/) y de ahí referenciarlas hacia nuestros proyectos.

## Crea un .gitignore

Syntax:

    *.extensión -> si quiero ignorar todos los archivos con esa extensión
    /directorio/ : para ignorar una carpeta por completo
    archivo.extensión : archivo específico a ignorar
    !archivo.extensión : archivo que se excluye de la lista gitignore

## Crea un Readme.md

Lo más fácil será haciéndolo en la siguiente página:

https://pandao.github.io/editor.md/en.html

## Deploy con GitHub Pages

Pasos:

    settings
    pages
        NOTA: en source no seleccionar: choose a theme
    en source seleccionar: la rama en la cual queremos hacer deploy
    luego elegir la carpeta o ruta desde la cual haremos el deploy
    guardar

Otra forma diferente de hacerlo está explicada en https://pages.github.com/