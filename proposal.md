# Propuesta TP DSW

## Grupo
### Integrantes
* 54757 - Marin, Benjamin
* 53799 - Salas, Valentino

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
Plataforma digital dedicada a la venta, alquiler por dias y suscripción mensual de videojuegos, que permite a los usuarios acceder a un amplio catálogo actualizado de títulos para PC. La plataforma se enfoca en ofrecer una experiencia simple y rápida con múltiples métodos de pago y disponibilidad inmediata. Además, busca generar una comunidad activa de usuarios mediante reseñas, valoraciones y beneficios exclusivos para suscriptores, posicionándose como una opcion asequible para todo tipo de usuario gaming.

### Modelo
https://ibb.co/JjjXn1Cx

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Categoria<br>2. CRUD Usuario
|CRUD dependiente|1. CRUD Videojuego {depende de} CRUD Categoria<br>2. CRUD Suscripcion {depende de} CRUD Usuario|
|Listado<br>+<br>detalle| 1. Listado de videojuegos filtrado por genero, muestra nombre, descripción y genero => detalle CRUD Videojuego<br>|
|CUU/Epic|1. Publicar o subir un videojuego|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Suscripcion<br>2. CRUD Alquiler<br>3. CRUD Venta<br>4. CRUD Biblioteca<br>5. CRUD Desarrollador|
|CUU/Epic|1. Adquirir el videojuego o suscripción|

### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|
