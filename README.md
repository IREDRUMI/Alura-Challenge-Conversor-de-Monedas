# Conversor de Monedas

Aplicacion de consola desarrollada en Java para convertir monedas en tiempo real mediante el consumo de una API de tasas de cambio.  
El proyecto permite consultar tasas de conversion, procesar respuestas en formato JSON y mostrar al usuario conversiones entre distintas monedas de interes.

## Descripcion

Este proyecto fue desarrollado como parte del challenge Conversor de Monedas.  
El objetivo principal es practicar el consumo de APIs, el manejo de datos JSON y la interaccion con el usuario mediante una aplicacion de consola en Java. [file:161]

## Funcionalidades

- Consultar tasas de cambio desde una API externa
- Convertir valores entre distintas monedas
- Filtrar monedas de interes
- Mostrar resultados en consola de forma clara
- Validar opciones ingresadas por el usuario

## Tecnologias utilizadas

- Java
- HttpClient
- Gson o Jackson
- API de tasas de cambio
- IntelliJ IDEA

## Objetivos del challenge

Durante este desafio se trabajan los siguientes puntos:

- Configuracion del ambiente Java
- Creacion del proyecto
- Consumo de la API
- Analisis de la respuesta JSON
- Filtro de monedas
- Exhibicion de resultados al usuario

## Como funciona

La aplicacion muestra un menu en consola con distintas opciones de conversion.  
El usuario selecciona la conversion deseada, ingresa el monto y el programa consulta la API para devolver el valor convertido.

## Ejemplo de uso

**
Sea bienvenido/a al Conversor de Moneda

1) Dolar =>> Peso argentino
2) Peso argentino =>> Dolar
3) Dolar =>> Real brasileno
4) Real brasileno =>> Dolar
5) Dolar =>> Peso colombiano
6) Peso colombiano =>> Dolar
7) Salir
Elija una opcion valida:
**
Ejemplo de conversion:

Ingrese el valor que desea convertir:
100

El valor 100 USD corresponde al valor final de 386500 COP

## Requisitos
Java 17 o superior
Conexion a Internet
IDE o terminal para ejecutar Java
Clave de acceso si la API utilizada la requiere

## Configuracion
Si tu proyecto usa una API con clave, puedes manejarla con variables de entorno para no exponerla en el codigo.

Ejemplo:
API_KEY=${API_KEY}

## Aprendizajes
Este proyecto permitio practicar:
Solicitudes HTTP en Java
Consumo de APIs REST
Conversion de respuestas JSON a objetos Java
Uso de menus interactivos en consola
Separacion de responsabilidades en clases

## Autor
Proyecto desarrollado como parte del programa de formacion de Alura Latam.
