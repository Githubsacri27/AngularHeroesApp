# Marvel Heroes App

Este proyecto es una aplicación web de Heroes de Marvel  desarrollada con Angular. La aplicación tiene como objetivo principal aprender y aplicar diferentes conceptos y características de Angular, incluyendo Angular Material, tipado con TypeScript, personalización de pipes, manejo de variables de entorno, y más.

## Estructura del Proyecto

La aplicación está organizada en varios módulos para mantener el código limpio y modularizado:

- **`auth/`**: Módulo de autenticación que incluye las páginas de login y registro de usuarios.
- **`heroes/`**: Módulo principal que gestiona la visualización y manejo de los héroes. Incluye funcionalidades como listado, búsqueda, y edición de héroes.
- **`material/`**: Módulo que centraliza las importaciones de Angular Material, facilitando su uso en toda la aplicación.
- **`shared/`**: Módulo compartido que incluye componentes reutilizables, como la página de error 404.

## Tecnologías 

- **Angular**: Framework principal para el desarrollo de la aplicación.
- **Angular Material**: Biblioteca de componentes de UI que ofrece un conjunto de herramientas preconstruidas y estilizadas para crear interfaces de usuario modernas.
- **TypeScript**: Lenguaje de programación que permite tipado estático y otros beneficios que mejoran la escalabilidad y mantenibilidad del código.
- **JSON-Server**: Herramienta para crear una API REST falsa para probar la aplicación sin necesidad de un backend real.
- **Prime Flex**: Biblioteca de utilidades CSS para facilitar el diseño responsivo y flexible.

## Próximos Pasos

1. **Integración de Angular Material**:
   - Aprovechar los componentes de Angular Material para construir una interfaz de usuario moderna y funcional.
   - Implementar un sistema de autocomplete usando Angular Material para facilitar la búsqueda de héroes.

2. **Implementación de Interfaces y Tipado**:
   - Definir interfaces claras para representar los datos de los héroes, lo que permitirá un código más robusto y fácil de mantener.

3. **Creación de Pipes Personalizados**:
   - Desarrollar pipes personalizados para formatear y manipular datos de manera eficiente.

4. **Configuración de Variables de Entorno**:
   - Gestionar diferentes configuraciones para distintos entornos (desarrollo, producción, etc.) utilizando variables de entorno.

5. **Peticiones HTTP**:
   - Implementar el servicio `HttpClient` de Angular para realizar peticiones HTTP y conectar la aplicación con un servidor backend (inicialmente simulado con JSON-Server).

6. **CRUD Completo**:
   - Desarrollar un CRUD completo (Create, Read, Update, Delete) para gestionar los datos de los héroes, permitiendo la creación, modificación, visualización y eliminación de héroes desde la interfaz de usuario.

7. **Uso de Prime Flex**:
   - Integrar Prime Flex para optimizar el diseño responsivo y mejorar la disposición de los componentes en la aplicación.

## Objetivos de Aprendizaje

Este proyecto tiene como objetivo aprender y dominar el uso de Angular Material, así como aplicar buenas prácticas en el desarrollo de aplicaciones Angular, incluyendo modularización, tipado con TypeScript, creación de pipes personalizados, y manejo de peticiones HTTP. Al finalizar, se espera que la aplicación esté bien estructurada, fácil de mantener, y escalable.


# AngularHeroesApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
