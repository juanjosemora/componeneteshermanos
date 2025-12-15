# Comunicación entre Componentes Hermanos - Angular

**INSTITUCIÓN:** SENA - Centro de Biotecnología  
**PROGRAMA:** Análisis y Desarrollo de Software (ADSO)  
**APRENDIZ:** Laura Fonseca  
**INSTRUCTOR:** Alexis Arévalo  
**FICHA:** 3203082

---

## Descripción del Proyecto

Este proyecto es una aplicación web desarrollada en Angular que demuestra la **comunicación entre componentes hermanos** mediante el uso de servicios y el sistema de rutas de Angular. La aplicación permite la navegación dinámica entre diferentes secciones y la actualización en tiempo real del contenido según las interacciones del usuario.

---

## Funcionalidades Implementadas

### 1. Componente 1 - Barra de Interacción Superior
- Contiene un logo de la aplicación
- Incluye tres botones interactivos: **Configuración**, **Control** y **Usuarios**
- Al presionar cada botón, se actualiza dinámicamente el contenido del Componente 2
- Indica visualmente cuál botón está actualmente seleccionado

### 2. Componente 2 - Barra de Navegación Lateral
- Muestra un título dinámico que cambia según el botón seleccionado en el Componente 1
- Presenta una lista de opciones de navegación que varía según el menú activo
- Tres opciones son funcionales y permiten navegar entre páginas
- Las demás opciones son solo visuales (sin funcionalidad de navegación)
- Resalta visualmente la opción de navegación actualmente seleccionada

### 3. Router Outlet - Sistema de Navegación
- Implementa el sistema de rutas de Angular para navegación SPA (Single Page Application)
- Carga dinámicamente tres componentes diferentes: Página 1, Página 2 y Página 3
- Permite transiciones fluidas entre las diferentes vistas sin recargar la página

---

## Estructura del Proyecto

```
src/
├── app/
│   ├── componente1/          # Barra superior con botones
│   ├── componente2/          # Barra lateral de navegación
│   ├── pagina1/              # Vista de página 1
│   ├── pagina2/              # Vista de página 2
│   ├── pagina3/              # Vista de página 3
│   ├── comunicacion.service.ts  # Servicio de comunicación
│   ├── app-routing.module.ts    # Configuración de rutas
│   └── app.module.ts            # Módulo principal
```

---

## Tecnologías Utilizadas

- **Angular** - Framework principal
- **TypeScript** - Lenguaje de programación
- **SCSS** - Preprocesador de estilos CSS
- **RxJS** - Programación reactiva para la comunicación entre componentes

---

## Conceptos Aplicados

- **Comunicación entre componentes hermanos** mediante servicios
- **Observables y Subjects** de RxJS para programación reactiva
- **Sistema de rutas** de Angular para navegación SPA
- **Data binding** y directivas de Angular
- **Inyección de dependencias**
- **Componentes modulares y reutilizables**

---

## Instalación y Ejecución

### Requisitos previos
- Node.js instalado
- Angular CLI instalado

### Pasos para ejecutar el proyecto

1. Clonar el repositorio:
```bash
git clone https://github.com/lFonseca117/comunicacion-componentes-angular.git
```

2. Instalar dependencias:
```bash
cd comunicacion-componentes-angular
npm install
```

3. Ejecutar la aplicación:
```bash
ng serve
```

4. Abrir en el navegador:
```
http://localhost:4200
```
## Aprendizajes Clave

Durante el desarrollo de este proyecto se adquirieron conocimientos sobre:

- Implementación de servicios para comunicación entre componentes
- Uso de Observables y BehaviorSubjects
- Configuración y uso del sistema de rutas de Angular
- Diseño de interfaces responsivas con SCSS
- Buenas prácticas de estructura de proyectos Angular

---

## Autor

**Laura Fonseca**  
Aprendiz ADSO - SENA  
Ficha: 3203082

---

