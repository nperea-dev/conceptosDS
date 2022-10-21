# Desarrollo Web Ciclo 4

## Semana 2 Funciones en JavaScript

Un elemento fundamental para el manejo de JavaScript son las funciones, que básicamente se refieren a trozos de código con propósitos específicos.

[Funciones](https://youtu.be/9UdWQ6L_lh8)

[funciones parte 2](https://youtu.be/F7zHCIfwUyA)

[importaciones y exportaciones](https://youtu.be/uhwddurj4Ew)

[arreglos y promesa](https://youtu.be/BgsxmEDpXwE)

[fetch api](https://youtu.be/KQEDHe2siOs)

### Lecturas de la semana

[fetch API](https://www.freecodecamp.org/espanol/news/tutorial-de-fetch-api-en-javascript-con-ejemplos-de-js-fetch-post-y-header/)

[Funciones Asincronas](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)

## Semana 3 Introducción a React

React es unalibrería muy útil de JavaScript, que permitirá que nuestro desarrollo sea mucho más dinámico y que se puedan evidenciar cambios de manera inmediata en el despliegue de nuestro proyecto. 

**Objetivos de aprendizaje** 

Identificar la estructura de trabajo de la librería **React** para JavaScript en aplicaciones del tipo single-page application (SPA). 

Construir el **FronEnd** de una aplicación web usando JavaScript y React bajo el patrón SPA.

[introducion React](https://youtu.be/ZnTghCuXZ7Q)

[React parte 2](https://youtu.be/g69goDFDp0o)

[Paso a paso par crear una ReactApp](https://github.com/nperea75-gh/conceptosDS/blob/6e8fc4bfb015e7e3d707eac021b08f01301323d6/Primer_manual_React.pdf)



### **lecturas interesante **


[Tutorial React](https://es.reactjs.org/tutorial/tutorial.html)

[Atributos DOM](https://es.reactjs.org/blog/2017/09/08/dom-attributes-in-react-16.html)

### ¿Por qué construimos React?
June 05, 2013 by Pete Hunt
Hay muchos frameworks MVC para JavaScript. ¿Por qué construimos React y por qué querrías usarlo?

### React no es un framework MVC
React es una biblioteca para construir interfaces de usuario componibles. Fomenta la creación de componentes reutilizables para interfaces de usuario que muestran datos que cambian con el tiempo.

### React no usa plantillas
Tradicionalmente, las interfaces de usuario para aplicaciones web se crean utilizando plantillas o directivas HTML. Estas plantillas dictan el conjunto completo de abstracciones que se permiten usar para crear tus interfaces de usuario.

React se enfoca en la construcción de interfaces de usuario de forma diferente al dividirlas en componentes. Esto significa que React utiliza un lenguaje de programación real y completo para renderizar vistas, lo que vemos como una ventaja sobre las plantillas por varias razones:

JavaScript es un lenguaje de programación flexible y potente con la capacidad de crear abstracciones. Esto es increíblemente importante en aplicaciones grandes.
Al unificar el markup con la lógica en vista correspondiente, React puede hacer a las vistas fácil de extender y mantener.
Al integrar la comprensión del markup y su contenido dentro de JavaScript, no hay concatenación manual de string y por tanto menos menos espacio para vulnerabilidades XSS.
También hemos creado JSX, una extensión de sintaxis opcional, en caso de que prefieras la legibilidad de HTML a JavaScript simple.

Las actualizaciones reactivas son muy simples
React realmente brilla cuando sus datos se modifican con el tiempo.

En una aplicación de JavaScript tradicional, debes tomar en cuenta qué datos han cambiado y realizar cambios de forma imperativa en el DOM para mantenerlos actualizados. Incluso AngularJS, que proporciona una interfaz declarativa a través de directivas y binding de datos requiere una función que enlace manualmente los cambios a los nodos del DOM.

### React adopta un enfoque diferente.

Cuando un componente se inicializa por primera vez, el método render es invocado generando una representación ligera de tu vista. A partir de esa representación, se produce una cadena de markup, e inyectada en el documento. Cuando tus datos cambian, se vuelve a llamar al método render. Para realizar las actualizaciones de la manera más eficiente posible, diferenciamos el valor de retorno de la llamada anterior para procesar con el nuevo, y generamos un conjunto mínimo de cambios que se aplicarán al DOM.

Los datos regresados desde render no son ni una cadena de texto ni un nodo del DOM: son una descripción ligera de cómo debería verse el DOM.

A este proceso lo llamamos reconciliación. Échale un vistazo a este jsFiddle para ver un ejemplo de reconciliación en acción.

Debido a que esta nueva rerenderización es tan rápida (alrededor de 1ms para TodoMVC), el desarrollador no necesita especificar explícitamente los bindings de datos. Nos hemos dado cuenta que este enfoque facilita la creación de aplicaciones.

### HTML es solo el comienzo
Debido a que React tiene su propia representación ligera del documento, podemos hacer algunas cosas muy interesantes con él:

Facebook tiene gráficas dinámicas que se renderizan en un <canvas> en lugar de HTML.
Instagram es una aplicación web “de una sola página” construida completamente con React y Backbone.Router. Los diseñadores contribuyen regularmente con código React con JSX.
Hemos creado prototipos internos que ejecutan las aplicaciones React en un web worker y usan React para impulsar las vistas nativas de iOS a través de un puente en Objective-C.
Puedes ejecutar React en el servidor para favorecer SEO, desempeño, compartir código y sobre todo flexibilidad.
Los eventos se comportan de manera coherente y compatible con los estándares en todos los navegadores (incluyendo IE8) y utilizan automáticamente la delegación de eventos.
Dirígete a https://reactjs.org para ver lo que hemos construido. Nuestra documentación está orientada a crear aplicaciones con el framework, pero si estás interesado en todos los detalles, ¡ponte en contacto con nosotros!

**https://es.reactjs.org/blog/2013/06/05/why-react.html**





[]()

[]()

[]()



