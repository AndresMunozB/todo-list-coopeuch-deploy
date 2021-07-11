# Todo List Coopeuch Deploy

Este repositorio contiene lo necesario para realizar el deploy de frontend, backend y base de datos (postgres) utilizando docker-compose.

## Requisitos

1. Docker. [https://docs.docker.com/engine/install/ubuntu/].

2. Docker Compose. [https://docs.docker.com/compose/install/].

3. Proyecto Frontend. [https://github.com/AndresMunozB/todo-list-coopeuch-frontend].

4. Proyecto Backend. [https://github.com/AndresMunozB/todo-list-coopeuch-backend].

## Estructura de carpetas

- carpeta_contenedora/
  - todo-list-coopeuch-frontend/
    - ...
  - todo-list-coopeuch-backend/
    - ....
  - todo-list-coopeuch-deploy/ (Proyecto actual)
    - ...

## Instalación del proyecto

Dentro del proyecto "todo-list-coopeuch-deploy" utilizar el siguiente comando

> docker-compose up -d

## Rutas

Los proyectos estarán corriendo dentro de contenedores de docker que exponen diferentes puertos.
Para ingresar a cada una de las aplicaciones se disponen las siguientes rutas:

- Frontend: http://localhost:3000
- Backend (Swagger): http://localhost:8080/swagger-ui/#/
