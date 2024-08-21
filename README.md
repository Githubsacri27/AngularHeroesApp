# Marvel Heroes App

Este proyecto es una aplicación web centrada en los héroes de Marvel, desarrollada con Angular con un objetivo didáctico. El proyecto se enfoca en aprender y aplicar diferentes conceptos y características de Angular, como la autenticación, inyección de dependencias, integración con Angular Material, y mucho más.

## Estructura del Proyecto

El proyecto está organizado en varios módulos, cada uno con una responsabilidad específica:

- **`auth/`**: Módulo de autenticación que incluye las páginas de login y registro de usuarios, así como los guards para proteger las rutas privadas.
- **`heroes/`**: Módulo principal que gestiona la visualización y manejo de los héroes. Incluye funcionalidades como el listado, búsqueda, edición y eliminación de héroes.
- **`material/`**: Módulo que centraliza las importaciones de Angular Material, facilitando su uso y consistencia en toda la aplicación.
- **`shared/`**: Módulo compartido que incluye componentes reutilizables, como la página de error 404, pipes personalizados y servicios comunes.

## Tecnologías Utilizadas

- **Angular**: Framework principal para el desarrollo de la aplicación.
- **Angular Material**: Biblioteca de componentes de UI que ofrece un conjunto de herramientas preconstruidas y estilizadas para crear interfaces de usuario modernas y responsivas.
- **TypeScript**: Lenguaje de programación utilizado para garantizar un tipado estático y una mejor escalabilidad del código.
- **JSON-Server**: Herramienta para crear una API REST falsa que permite probar la aplicación sin necesidad de un backend real.
- **Prime Flex**: Biblioteca de utilidades CSS para facilitar el diseño responsivo y flexible.

## Ejercicios Realizados

1. **Integración de Angular Material**:
   - Uso de componentes de Angular Material para construir la interfaz de usuario.
   - Implementación de un sistema de autocomplete para facilitar la búsqueda de héroes.

2. **Implementación de Interfaces y Tipado**:
   - Definición de interfaces TypeScript para representar los datos de los héroes, mejorando la robustez y mantenibilidad del código.
   - **Snacks**: Notificaciones rápidas para proporcionar retroalimentación al usuario después de operaciones como guardado o eliminación.
   - **Dialogs**: Diálogos modales para confirmar acciones importantes, como la eliminación de un héroe.

3. **Creación de Pipes Personalizados**:
   - Desarrollo de pipes personalizados para formatear y manipular datos de manera eficiente, incluyendo pipes puros e impuros según la necesidad.

4. **Configuración de Variables de Entorno**:
   - Gestión de diferentes configuraciones para entornos de desarrollo y producción mediante el uso de variables de entorno.

5. **Peticiones HTTP**:
   - Implementación del servicio `HttpClient` de Angular para realizar peticiones HTTP y conectar la aplicación con un servidor backend (simulado inicialmente con JSON-Server).

6. **CRUD Completo**:
   - Desarrollo de un sistema CRUD (Create, Read, Update, Delete) completo para gestionar los datos de los héroes, permitiendo la creación, modificación, visualización y eliminación de héroes desde la interfaz de usuario.

7. **Uso de Prime Flex**:
   - Integración de Prime Flex para mejorar el diseño responsivo y optimizar la disposición de los componentes en la aplicación.

8. **Protección de Rutas**:
   - **Rutas Privadas**: Protección de rutas utilizando `CanActivate` y `CanMatch` guards (`AuthGuard` y `PublicGuard`) para asegurar que solo usuarios autenticados puedan acceder a ciertas áreas de la aplicación.
   - **Rutas Públicas**: Páginas como login y registro accesibles sin necesidad de autenticación.

## Instalación y Uso

### Pasos para Configurar el Entorno de Desarrollo

1. Clona el proyecto:
    ```bash
    git clone https://github.com/Githubsacri27/AngularHeroesApp.git
    ```
2. Instala las dependencias:
    ```bash
    npm install
    ```
3. Levanta el backend simulado con JSON-Server:
    ```bash
    npm run backend
    ```
4. Inicia la aplicación:
    ```bash
    npm start
    ```
    o alternativamente:
    ```bash
    ng serve -o
    ```

### Uso de la Aplicación

- **Autenticación**: Usa las páginas de login y registro para gestionar el acceso a la aplicación.
- **Gestión de Héroes**: Navega por el listado de héroes, visualiza sus detalles, edítalos o crea nuevos héroes.
- **Protección de Rutas**: Las rutas críticas están protegidas para evitar accesos no autorizados, redirigiendo a los usuarios no autenticados a la página de login.

