# Proyecto Municipalidad de Castro

## Introducción

Este es mi proyecto creado con HTML y tailwindcss.

## Características

- estructura utilizando HTML5
- Estilos modernos con Tailwindcss
- Paginas informativas sobre Historia, Nosotros, Blog, Transparencia y contacto

## estructura de carpetas

-input: contiene el archivo input.css

-public: contiene el archivo de salida de tailwindcss

-assets: contiene los archivos de imagenes y css

--css: contiene el archivo de css en el cual se le aplica tailwindcss

--img: contiene las imagenes del proyecto

-blog: contiene el archivo de blog

-noticias: contiene el archivo de noticias

-contacto: contiene el archivo de contacto

-historia: contiene el archivo de historia

-index: contiene el archivo de index

-noticias: contiene el archivo de noticias

-nosotros: contiene el archivo de nosotros

-transparencia: contiene el archivo de transparencia

## verificar si tenemos node.js

node -v

## Crear package.json

npm init

## instalar tailwindcss

npm install tailwindcss @tailwindcss/cli

## importar tailwindcss en input.css

@import "tailwindcss";

## importar tailwindcss en package.json

abajo de "scripts"

-***"watch": "npx @tailwindcss/cli -i ./input/input.css -o ./public/assets/css/style.css --watch"***


## Verificar si tenemos tailwindcss

- en el archivo index.html en el head
< link rel="stylesheet" href="assets/css/style.css"> ***llamamos al archivo que tiene tailwindcss***

- entre el body
< h1 class="text-3xl text-red-500">hola mundo!</ h1 > ***aplicamos tailwindcss a nuestro html***

# Responisve design

el sitio esta optimizado para dispositivos móviles (el menu no aparece en movil), tables y PC

# propietario

este proyecto es de Elioth Vargas