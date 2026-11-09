# DevTask

DevTask es una pequeña aplicación web para organizar tareas de programación. Está desarrollada como proyecto práctico de Desarrollo Web en Entorno Cliente y utiliza TypeScript para gestionar las tareas y sus interacciones con la página.

## Funcionalidades

- Añadir tareas con prioridad alta, media o baja.
- Marcar tareas como completadas o pendientes.
- Filtrar la lista para ver todas las tareas, solo las pendientes o solo las completadas.
- Guardar las tareas en el almacenamiento local del navegador (`localStorage`), para conservarlas al volver a abrir la aplicación en el mismo navegador.
- Mostrar un conjunto inicial de tareas la primera vez que se utiliza para ver que todo funciona correctamente y tener ejemplos ya creados.

## Tecnologías

- HTML
- CSS
- TypeScript y JavaScript
- `localStorage` del navegador

## Estructura del proyecto

- `index.html`: estructura de la aplicación.
- `style.css`: estilos de la interfaz.
- `src/app.ts`: punto de entrada de la aplicación.
- `src/models/TaskManager.ts`: lógica de creación, filtrado, actualización y persistencia de tareas.
- `src/interfaces/tarea.interface.ts`: tipos de tarea y prioridad.
- `src/Ejercicios/`: ejercicios prácticos sobre arrays, peticiones asíncronas y manipulación del DOM.
- `dist/`: JavaScript generado a partir de TypeScript, que carga la página.
- `tsconfig.json`: configuración del compilador de TypeScript.

## Cómo ejecutar el proyecto

1. Asegúrate de tener instalado el compilador de TypeScript (`tsc`).
2. Desde la carpeta del proyecto, ejecuta `tsc` para compilar los archivos de `src/` en `dist/`.
3. Sirve la carpeta del proyecto con un servidor web local y abre `index.html` en el navegador. Por ejemplo, puedes usar la extensión Live Server de Visual Studio Code.

La aplicación utiliza módulos JavaScript, por lo que es necesario abrirla desde un servidor local en lugar de cargar el archivo directamente con `file://`.

## Sobre mí

Hola, soy **Iván Del Toro**, estudiante de **2 año de DAW**. Me interesa **la ciberseguridad**.

Este proyecto forma parte de mi aprendizaje de **Desarrollo Web en Entorno Cliente**.
