# ui-pt-webcomponents
Este repositorio contiene una colección de **Web Components reutilizables** desarrollados con tecnologías estándar (HTML, CSS y JavaScript), diseñados para ser utilizados en múltiples proyectos frontend, incluyendo aplicaciones construidas con **React** y **Next.js**.


## Características

- Componentes personalizados como `<input-rfc>`, `<button-primary>`, etc.
- Estilo encapsulado mediante Shadow DOM.
- Documentación y pruebas visuales con **Storybook**.
- Compatible con cualquier framework moderno (React, Vue, Angular, etc.).
- Empaquetado listo para distribución vía NPM o importación directa desde CDN.


## 🧰 Requisitos para desarrollo

Antes de comenzar a desarrollar o probar componentes en este repositorio, asegúrate de tener el siguiente entorno configurado:

### ✅ Prerrequisitos

- **Node.js** versión **22.20.0 o superior**  
  Verifica tu versión con:

  ```bash
  node -v
- Puedes **instalar** la version :
  ```bash
  nvm install 22
  nvm use 22

## 🚀 Desarrollo

Para desarrollar y probar los componentes localmente:

1. **Instala las dependencias:**
   ```bash
   npm install
   ```

2. **Inicia Storybook para desarrollo:**
   ```bash
   npm run storybook
   ```
   
   Esto abrirá Storybook en `http://localhost:6006` donde podrás ver y probar todos los componentes en desarrollo.
   
## ¿Por qué usar Vite?

* **Velocidad de desarrollo**
  * Vite usa ES Modules nativos en desarrollo, lo que significa que no se necesita hacer un bundle completo cada vez que se cambia algo.
  * Resultado: inicio del servidor y recarga en caliente (HMR) casi instantáneos, incluso en proyectos grandes.
  
* **Configuración mínima**
  * Vite funciona bien con muy poca configuración.

* **Soporte moderno**
  * Vite está diseñado para trabajar con tecnologías modernas como Web Components, TypeScript, JSX, PostCSS, etc.
  * Tiene una comunidad activa y plugins oficiales para casi todo.

* **Build optimizado**
  * Usa Rollup internamente para producción, lo que genera bundles eficientes y compatibles con NPM/CDN.
  * Se puede exportar en formatos como es, umd, cjs, etc., fácilmente.






