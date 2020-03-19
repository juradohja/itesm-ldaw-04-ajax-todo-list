### itesm-ldaw-04-ajax-todo-list

# Creación de tareas en AJAX
## Por: José Alberto Jurado

GD #4 de Laboratorio de desarrollo de aplicaciones Web.
Aplicación simple que permite la creación de tareas a través
de peticiones AJAX. Permite también el marcado de estas
como terminadas, y posteriormente borrarlas.

## Requerimientos

El sistema depende de que tengas [Knex.js](http://knexjs.org/) instalado de forma global.

```bash
npm i knex -g
```

## Instalación

1. Guarda el archivo .env.example como .env y modifica las variables para que coincidan con tu ambiente.

```bash
cp .env.example .env
```

2. Instala los paquetes indicados en el `package.json`.

```bash
npm install
```

3. Ejecuta las migraciones.

```bash
knex migrate:latest
```

## Ejecución
```
node server.js
```
