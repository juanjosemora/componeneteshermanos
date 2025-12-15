actividad  Componentes 

Institución: SENA - Centro de Biotecnología
Programa: Análisis y Desarrollo de Software (ADSO)
Aprendiz: Juan José Bocanegra Mora
Instructor: Alexis Arévalo
Ficha: 3203082

Tema del Proyecto

El proyecto se centra en la temática de fútbol, aplicando la comunicación entre componentes para gestionar información de un equipo deportivo.
La aplicación simula un panel de control de un equipo de fútbol, donde se pueden visualizar secciones como Inicio del equipo, Entrenamiento y Competencias, demostrando la interacción dinámica entre componentes y la actualización en tiempo real de los datos relacionados con jugadores, tácticas y estrategias de juego.
Resumen del Proyecto

El presente proyecto consiste en una aplicación web desarrollada en Angular, diseñada para demostrar la comunicación efectiva entre componentes hermanos mediante el uso de servicios y rutas. La aplicación permite la navegación dinámica entre distintas secciones, así como la actualización en tiempo real del contenido según las acciones del usuario.

Funcionalidades Principales

Barra Superior (Componente 1):
Incluye un logotipo y tres botones interactivos que permiten actualizar dinámicamente el contenido del Componente 2, indicando visualmente el botón actualmente activo.

Barra Lateral (Componente 2):
Presenta un título y una lista de opciones que cambian según el menú seleccionado. Resalta la opción activa y permite la navegación entre tres páginas funcionales, mientras que las restantes tienen un carácter visual.

Router Outlet:
Implementa el sistema de rutas de Angular, proporcionando una navegación SPA (Single Page Application) fluida que carga tres componentes diferentes sin recargar la página.

Estructura del Proyecto
src/
├── app/
│   ├── componente1/              # Barra superior con botones
│   ├── componente2/              # Barra lateral de navegación
│   ├── pagina1/                  # Vista de la página 1
│   ├── pagina2/                  # Vista de la página 2
│   ├── pagina3/                  # Vista de la página 3
│   ├── comunicacion.service.ts   # Servicio de comunicación
│   ├── app-routing.module.ts     # Configuración de rutas
│   └── app.module.ts             # Módulo principal

Tecnologías Utilizadas

Angular: Framework principal

TypeScript: Lenguaje de programación

SCSS: Preprocesador de estilos

RxJS: Programación reactiva para la comunicación entre componentes

Conceptos Aplicados

Comunicación entre componentes hermanos a través de servicios

Uso de Observables y BehaviorSubjects para programación reactiva

Implementación de rutas en Angular para SPA

Data binding y uso de directivas

Desarrollo de componentes modulares y reutilizables

Inyección de dependencias

Instalación y Ejecución

Clonar el repositorio:

git clone https://github.com/lFonseca117/comunicacion-componentes-angular.git


Instalar dependencias:

cd comunicacion-componentes-angular
npm install


Ejecutar la aplicación:

ng serve


Abrir en el navegador: http://localhost:4200

Aprendizajes Obtenidos

Durante la realización del proyecto se adquirieron conocimientos sobre:

Implementación de servicios para comunicación entre componentes

Uso de Observables y BehaviorSubjects

Configuración y gestión de rutas en Angular

Diseño de interfaces responsivas con SCSS

Organización y buenas prácticas en la estructura de proyectos Angular

Autor: Juan José Bocanegra Mora
Aprendiz ADSO – SENA
Ficha: 3203082
