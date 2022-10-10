---
title: 'Post cinco'
description: Post cinco.
date: '2022-10-10'
modified_date: '2022-10-10'
image: /assets/images/posts/random-img.jpg
---

Post cinco
Páginas
Nota: Estamos introduciendo un soporte de enrutamiento mejorado en Next.js. Lea el RFC De diseños para obtener más detalles y proporcionar comentarios.

En Siguiente.js, una página es un componente de React exportado desde un archivo , , o en el directorio. Cada página está asociada a una ruta basada en su nombre de archivo..js.jsx.ts.tsxpages

Ejemplo: Si crea un componente de React como el siguiente, se podrá acceder a él en .pages/about.js/about

```js
function About() {
  return <div>About</div>
}

export default About
```
