# Proyecto Municipalidad de Castro

## Introducción

Este es mi proyecto creado con HTML y tailwindcss.

## Características

- estructura utilizando HTML5
- Estilos modernos con Tailwindcss
- Paginas informativas sobre Historia, Nosotros, Blog, Transparencia y contacto

## estructura de carpetas

input: contiene el archivo input.css

public: contiene el archivo de salida de tailwindcss
    -assets: contiene los archivos de imagenes y css
        --css: contiene el archivo de css en el cual se le aplica tailwindcss
        --img: contiene las imagenes del proyecto
    -blog: contiene el archivo de blog
        --noticias: contiene el archivo de noticias
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

{
  "name": "proyecto-html-tailwind4.1",
  "version": "1.1.0",
  "description": "Proyecto \"Blog\" Creado con Html y Tailwindcss4.1",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    ***"watch": "npx @tailwindcss/cli -i ./input/input.css -o ./public/assets/css/style.css --watch"***
  },
  "author": "Elioth Vargas",
  "license": "ISC",
  "dependencies": {
    "@tailwindcss/cli": "^4.1.13",
    "tailwindcss": "^4.1.13"
  }
}

## Verificar si tenemos tailwindcss

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/css/style.css"> ***llamamos al archivo que tiene tailwindcss***
    <title>Document</title>
</head>
<body>
    <h1 class="text-3xl text-red-500">hola mundo!</h1> ***aplicamos tailwindcss a nuestro html***
</body>
</html>

# Responisve design

el sitio esta optimizado para dispositivos móviles (el menu no aparece en movil), tables y PC

# propietario

este proyecto es de Elioth Vargas