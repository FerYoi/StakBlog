---
title: 'Post seis'
description: Post seis.
date: '2022-10-10'
modified_date: '2022-10-10'
image: /assets/images/posts/random-img.jpg
---

Post seis
Dos formas de pre-renderizado
A continuación.js tiene dos formas de pre-renderizado: Generación estática y Renderizado del lado del servidor. La diferencia está en cuándo genera el HTML para una página.

Generación estática (recomendado): El HTML se genera en el momento de la compilación y se reutilizará en cada solicitud.
Representación del lado del servidor: el HTML se genera en cada solicitud.
Es importante destacar que Next.js le permite elegir qué formulario de representación previa le gustaría usar para cada página. Puede crear una aplicación "híbrida" Next.js mediante la generación estática para la mayoría de las páginas y la representación del lado del servidor para otras.

Recomendamos utilizar la generación estática sobre la representación del lado del servidor por razones de rendimiento. Las páginas generadas estáticamente pueden ser almacenadas en caché por CDN sin configuración adicional para aumentar el rendimiento. Sin embargo, en algunos casos, la representación del lado del servidor puede ser la única opción.

También puede utilizar la obtención de datos del lado del cliente junto con la generación estática o la representación del lado del servidor. Eso significa que algunas partes de una página se pueden representar completamente por JavaScript del lado del cliente. Para obtener más información, eche un vistazo a la documentación de Data Fetching.
```js
function About() {
  return <div>About</div>
}

export default About
```
