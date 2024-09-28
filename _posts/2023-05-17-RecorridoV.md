---
layout: post
title:  "Recorrido virtual"
date:   2023-05-17
excerpt: "Recorrido virtual Tonala"
tag:
- NodeJS
- REST APIs
- JS
- EXPRESS
- MySQL

---

### ¿En que consiste?
Es un sitio web el cual tiene como objetivo el poder hacer un recorrido turístico de forma virtual por los puntos más característicos de Tonalá, Jalisco. Esta página cuenta con diferentes locaciones relevantes para el turismo y datos acerca de estos mismos, además integra la API de google maps para poder hacer un recorrido usando street view para una mejor inmersión.

Los usuarios tienen la opción de poder compartir su opinión y experiencia de los sitios turísticos siempre y cuando tengan una cuenta creada en el sitio, simplemente tienen que seleccionar el punto turístico al que deseen dejar su comentario o calificar con un sistema de estrellas.


### ¿Cómo fué hecha?
Fue desarrollada usando NodeJS con Express y utiliza la arquitectura modelo vista controlador (MVC) donde la vista fue hecha utilizando EJS para hacer las páginas más dinámicas según el contenido que se agregue sobre los puntos en la base de datos, además se implementaron medidas de seguridad para prevenir la inyección SQL sanitizando los datos que reciben los controladores y mandando los datos limpios a la base de datos y utiliza la libreria "helmet" para mejorar la seguridad de la pagina http.


### Mi experiencia
Este proyecto fue enriquecedor para practicar mi desarrollo del back-end utilizando MVC además de aprender las medidas de seguridad que se deben de tomar para prevenir ciertos ciberataques que podrían afectar la integridad de nuestra aplicación.
Pero además de las habilidades de programación adquiridas también mejore mis habilidades de trabajo en equipo, ya que lidere a un equipo de 5 personas (contándome a mi) para realizar el proyecto cumpliendo con objetivos y tiempos, en general fue una experiencia enriquecedora en este aspecto.

* <a href="https://drive.google.com/file/d/1esn4Xysigb9CgBoR0-pOiFKwk6hJ79aj/view?usp=sharing">Video la pagina turistica</a>