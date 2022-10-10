---
title: 'Post cuatro'
description: Post cuatro.
date: '2022-10-10'
modified_date: '2022-10-10'
image: /assets/images/posts/random-img.jpg
---

Configuración manual de NEXT.JS
Instale y en su proyecto:next react react-dom

```js
npm install next react react-dom
# or
yarn add next react react-dom
# or
pnpm add next react react-dom
```
Abra y agregue lo siguiente:package.jsonscripts
```js
"scripts": {
  "dev": "next dev",
  "build": "next build",
  "start": "next start",
  "lint": "next lint"
}
```
Estos scripts se refieren a las diferentes etapas del desarrollo de una aplicación:

dev - Ejecuta el siguiente desarrollador para iniciar Siguiente.js en modo de desarrollo
build - Ejecuta la siguiente compilación para compilar la aplicación para el uso de producción
start - Se ejecuta el siguiente inicio para iniciar un servidor de producción Next.js
lint - Ejecuta next lint para configurar la configuración eslint incorporada de Next.js
Cree dos directorios y en la raíz de la aplicación:pagespublic

pages - Asociado a una ruta basada en su nombre de archivo. Por ejemplo, se asigna a pages/about.js/about
public - Almacena activos estáticos como imágenes, fuentes, etc. Los archivos dentro del directorio pueden ser referenciados por su código a partir de la URL base ().public/
A continuación.js se construye en torno al concepto de páginas. Una página es un componente de React exportado desde un archivo , , , o en el directorio. Incluso puede agregar parámetros de ruta dinámica con el nombre de archivo..js.jsx.ts.tsxpages

Dentro del directorio, agregue el archivo para comenzar. Esta es la página que se representa cuando el usuario visita la raíz de la aplicación.pagesindex.js

Rellenar con los siguientes contenidos:pages/index.js
```js
function HomePage() {
  return <div>Welcome to Next.js!</div>
}

export default HomePage
```