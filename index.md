Tecnologías Empleadas
Bibliotecas y Frameworks:
    • React (v18.2.0): Biblioteca de JavaScript para construir interfaces de usuario interactivas y componentes reutilizables.
    • React Router DOM (v6.11.2): Navegación declarativa y basada en componentes para aplicaciones React.
    • Ant Design (v5.6.1): Framework de diseño de UI con componentes preconstruidos para construir aplicaciones web modernas y atractivas.
    • MUI Icons (v5.11.16): Conjunto de iconos de Material Design para React.
    • Zustand (v4.3.8): Biblioteca de gestión de estado ligera para React.
    • Tanstack React Query (v5.17.1): Biblioteca para gestionar el estado de la aplicación y los datos de forma eficiente.
    • Tanstack React Query Devtools (v5.17.1): Herramientas de desarrollo para React Query.
    • React Hook Form (v7.44.2): Biblioteca para gestionar formularios en React de manera sencilla y eficiente.
    • React Cookie (v4.1.1): Manejo de cookies en aplicaciones React.
Utilidades y Herramientas:
    • Axios (v1.4.0): Cliente HTTP para realizar peticiones AJAX en el navegador y Node.js.
    • Dayjs (v1.11.8): Biblioteca ultraligera para manipular y formatear fechas en JavaScript.
    • Cronstrue (v2.47.0): Convierte expresiones cron en frases legibles por humanos.
    • I18next (v23.2.7): Biblioteca de internacionalización para JavaScript.
    • Install (v0.13.0): Herramienta para la instalación de paquetes y gestión de dependencias.
    • npm (v9.6.7): Gestor de paquetes para JavaScript.
Estilos y Diseño:
    • @Ant Design/Plots (v1.2.5): Biblioteca de gráficos y visualizaciones basada en Ant Design.
    • @Emotion/React (v11.11.0): Librería para estilos en línea para React.
    • @Emotion/Styled (v11.11.0): CSS en línea para React con soporte para estilos dinámicos.
    • Tailwind CSS (v3.3.2): Framework de utilidades de CSS de bajo nivel para construir interfaces rápidas y modernas.
Herramientas de Desarrollo y Testing:
    • Babel (Presets: Env, React, TypeScript): Herramienta para transpilar código JavaScript moderno.
    • Jest (v29.5.0): Framework de testing para JavaScript y React.
    • React Testing Library (v14.0.0): Utilidades para realizar pruebas de componentes React.
    • TypeScript (v5.0.2): Superset de JavaScript que añade tipado estático.
    • Vite (v4.3.2): Herramienta de construcción rápida y eficiente para proyectos web.
Linter y Formateo de Código:
    • ESLint (v8.42.0): Herramienta para identificar y arreglar problemas en el código JavaScript.
    • Prettier (v2.8.8): Formateador de código para mantener la consistencia y legibilidad del código.
    • PostCSS (v8.4.23): Procesador de CSS para transformar estilos con JavaScript plugins.
    • Autoprefixer (v10.4.14): Plugin PostCSS para agregar prefijos de proveedores automáticamente.
Herramientas recomendadas
La idea es que cada persona trabaje con las herramientas con las que sea más prodcutivo, pero dejamos algunas recomendaciones:
IDEs
    • Visual Studio Code 
















¡Por supuesto! Aquí está la sección actualizada que incluye cómo instalar Node.js y npm:

---

# Guía de Inicio Rápido

¡Bienvenido a nuestro proyecto! Sigue estos pasos para comenzar a trabajar en el código y contribuir al desarrollo.

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalado en tu sistema:

### Node.js y npm

- **Node.js:** Necesitarás Node.js para ejecutar JavaScript del lado del servidor y npm, el gestor de paquetes de Node.js.

  #### Instalación de Node.js y npm:

  - **Windows y macOS:**
    Puedes descargar el instalador desde [el sitio oficial de Node.js](https://nodejs.org/).
  
  - **Linux (Usando NVM):**
    ```bash
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
    nvm install node
    ```

## Clonar el Repositorio

```bash
git clone https://github.com/Akralogic/spa-erpcloud.git
cd spa-erpcloud
```

## Instalar Dependencias

```bash
npm install
```

Este comando instalará todas las dependencias necesarias para el proyecto.

## Configuración del Entorno de Desarrollo

Para iniciar el entorno de desarrollo, ejecuta:

```bash
npm run dev
```

Esto iniciará el servidor de desarrollo de Vite y podrás ver tu aplicación en `http://localhost:3000`.

## Construcción para Producción

Si estás listo para construir el proyecto para producción, ejecuta:

```bash
npm run build
```

Esto compilará tu código TypeScript y generará una versión optimizada del proyecto en el directorio `dist`.

## Ejecutar Pruebas Unitarias

Para ejecutar las pruebas unitarias, utiliza:

```bash
npm run test:unit
```

Este comando ejecutará las pruebas utilizando Jest.

## Linting del Código

Para verificar la calidad del código, ejecuta:

```bash
npm run lint
```

En caso de que desees corregir automáticamente los problemas encontrados, utiliza:

```bash
npm run lint:fix
```
