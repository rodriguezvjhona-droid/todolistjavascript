# 📝 TodoListJavascript

¡Bienvenido a **TodoListJavascript**! Una aplicación web moderna, robusta y ligera para la gestión de tareas pendientes, desarrollada con **JavaScript Vanilla (ES6+)** y potenciada por las herramientas de última generación de **Vite** y **Rolldown**.

Este proyecto implementa una arquitectura limpia basada en componentes y controladores, estructurada para ser altamente escalable, mantenible y con un rendimiento excepcional. Utiliza un enfoque dinámico para renderizar vistas y gestionar el estado sin depender de frameworks pesados como React o Vue.

---

## 🚀 Características Principales

- **⚙️ Arquitectura Limpia:** Estructura modular organizada en vistas (`views`), controladores (`controllers`) y componentes reutilizables (`components`).
- **🗂️ Simulación de Base de Datos Local:** Integración con un archivo dinámico `db.json` para emular operaciones CRUD en un entorno local y persistente.
- **⚡ Rendimiento de Vanguardia:** Flujo de desarrollo ultra rápido gracias a **Vite** y empaquetamiento optimizado con **Rolldown**.
- **🎨 Interfaz Atractiva y Fluida:** Estilos modernos y responsivos con soporte nativo de SVG y recursos vectoriales limpios.
- **🔒 Flujo de Autenticación Integrado:** Controladores dedicados para el inicio de sesión (`login`) y la seguridad de las vistas de usuario.

---

## 📂 Estructura del Proyecto

La organización del código sigue los estándares de diseño de software modernos, separando la lógica de negocio de la capa de presentación:

```bash
TodoListJavascript/
├── database/
│   └── db.json                 # Base de datos simulada (JSON)
├── public/
│   ├── favicon.svg             # Icono de la aplicación
│   └── icons.svg               # Set de iconos SVG del sistema
├── src/
│   ├── assets/                 # Recursos estáticos (Imágenes y Logotipos)
│   │   ├── hero.png
│   │   ├── javascript.svg
│   │   └── vite.svg
│   ├── components/             # Componentes visuales reutilizables
│   │   └── layout.js           # Estructura y contenedor global de la interfaz
│   ├── controllers/            # Lógica de negocio y manejo de eventos
│   │   ├── home.controller.js  # Controlador principal de la app
│   │   └── login.controller.js # Controlador del sistema de acceso
│   ├── views/                  # Plantillas de renderizado de la UI
│   │   ├── homeView.js         # Vista de la lista de tareas principal
│   │   ├── loginView.js        # Vista del formulario de login
│   │   ├── userView.js         # Vista del perfil y gestión de usuario
│   │   └── notFoundView.js     # Vista de error 404 para rutas inexistentes
│   ├── counter.js              # Módulo auxiliar para utilidades numéricas
│   ├── main.js                 # Punto de entrada principal de la aplicación
│   └── style.css               # Hoja de estilos globales optimizada
├── index.html                  # Plantilla HTML5 base
├── package.json                # Configuración de dependencias y scripts de Node
├── vite.config.js              # Configuración del entorno de desarrollo Vite
└── README.md                   # Documentación oficial del proyecto
