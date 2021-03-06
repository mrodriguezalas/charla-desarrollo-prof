# Charla de Desarrollo Profesional: Aplicaciones más competitivas, ejemplo de página web
Ejemplo de página web estática para la charla de desarrollo profesional de marzo 2021.

Este ejemplo hará uso de Jekyll Themes para la implementación de una página web básica para presentar un CV

## Para comenzar

1. Siga las instrucciones en [Jekyll](https://jekyllrb.com/docs/installation/)
1. Debe tener instalado [Ruby](https://www.ruby-lang.org/en/downloads/)
1. Debe tener instalado [RubyGems](https://rubygems.org/pages/download)
1. Instalar [GCC](https://gcc.gnu.org/install/) y [Make](https://www.gnu.org/software/make/). Este paso aplica solo para distribuciones de Linux.

- En Windows, la forma más sencilla de instalar todo es utilizar [Ruby Installer](https://rubyinstaller.org/downloads/)

## Primeros pasos (Windows)
- Una vez instalado todo lo anterior abra una nueva ventana de CMD y ejecute el comando `gem install jekyll bundler`
- Verifique la instalación corriendo `jekyll -v`
- Elegir una nueva carpeta donde van a estar los archivos de su página web. Vamos a crear una nueva página con el comando `jekyll new mipagina` donde 'mipagina' es el nombre que se le dará a la nueva carpeta con los archivos de la página.
- Cambiar a la carpeta recién creada con `cd mipagina`.
- Ejecute `bundle exec jekyll serve`
- Abra su navegador en la dirección `http://localhost:4000`.
