# React

Para comenzar tu camino en el mundo de React necesitas tener una **base sólida** en las principales tecnologías del front end: **HTML**, **CSS** y **JavaScript**, te recomendamos seguir la **[Escuela de Desarrollo Web](https://platzi.com/web/)** en orden.

El trabajo de un desarrollador front-end es darle la mejor experiencia posible a nuestros usuarios en:

- Flujo de navegación
- Tiempos de carga
- Accesibilidad
- Optimización
- Usabilidad

## ¿Qué es React.js?

React es una herramienta de JavaScript en el front end que nos ayuda a
 construir la parte visual de nuestras aplicaciones web, las interfaces 
con las que van a interactuar nuestros usuarios.

React es una librería progresiva, esto porque puedes hacer desde una 
página sencilla hasta poder desarrollar aplicaciones gigantes, y llegar a
 convertirse en un framework en conjunto de muchas herramientas que 
existen a su alrededor.

## Pero… ¿Por qué aprender React?

Mientras más crecen nuestras aplicaciones web, se vuelve más 
complicado nuestro trabajo utilizando solamente HTML, CSS y JavaScript. 
La magia de React es que nos facilita crear y organizar nuestro código, 
acelerar el proceso de creación, además de ofrecernos una mejor 
experiencia como desarrolladores.

Seguramente por esto quieres aprender React:

- Curiosidad sobre por qué React es tan poderoso
- Quieres conseguir un mejor empleo
- Te apasiona el desarrollo web
- Quieres mejorar tu salario

Sea cual sea tu motivación, React te puede ayudar.

## Requisitos para el curso:

Profundizar y dominar estos temas retornará buenos frutos y te convertirá en un excelente desarrollador.

- [HTML y CSS](https://platzi.com/cursos/html-css/)
- [JavaScript](https://platzi.com/cursos/basico-javascript/)
- [ECMAScript 6+](https://platzi.com/cursos/ecmascript-6/)
- [Clousures y Scope](https://platzi.com/cursos/scope/)
- [POO](https://platzi.com/cursos/javascript-poo/)
- [JavaScrip Engine](https://platzi.com/cursos/javascript-navegador/)
- [Asincronismo](https://platzi.com/cursos/asincronismo-js/)
- [Peticiones a API](https://platzi.com/cursos/api/)
- [Manipulación del DOM](https://platzi.com/cursos/dom/)
- [Frameworks y librerías de JavaScript](https://platzi.com/cursos/frameworks-javascript/)

## ¿Quién será tu profesor?

En este curso, Juan David Castro, course director en la facultad de 
computer science de Platzi te acompañará mientras aprendes los temas 
esenciales de React, desde la teoría hasta la práctica.

## Cuándo usar React.js

Para saber cuándo usar React es necesario conocer el tipo de proyecto que estás desarrollando. Conociendo los alcances actuales y los futuros, podrás tener un panorama completo de las necesidades que vas a cubrir y cuáles son las funciones básicas que debe tener para ser un MVP.

React es muy útil cuando queremos construir rápidamente la primera versión funcional de una aplicación web sin sacrificar su escalabilidad. Si no necesitamos escalarla después, no es necesario utilizar React, podemos utilizar JavaScript vanilla.

###¿Qué es un MVP?

MVP (Minimum Viable Product - Producto Mínimo Viable): se refiere a construir funcionalidades pequeñas que sean completas para que podamos lanzarla y medir su impacto y decidir si seguir ese camino o probar otra cosa.

Hay que escoger el problema más crucial que debe resolver la aplicación.
![imagen](https://user-images.githubusercontent.com/83564327/205417237-17580f1a-77f8-41c7-b8ef-8733320f27f4.png)

### Flujos de trabajo para aplicaciones web

Existen dos flujos de trabajo para crear aplicaciones web profesionalmente.

1. Modelo en cascada

Cada equipo tiene un tiempo para hacer todo su respectivo trabajo para construir una aplicación.

Por ejemplo: el equipo de diseño diseña la aplicación, el de desarrollo programa todo lo diseñado y finalmente se lanza la app recogiendo el feedback de los usuarios y se vuelve a empezar tomando en cuenta lo dicho por los usuarios.

Es problemático porque el esfuerzo puede ser en vano porque no se tiene un feedback hasta que se termina de construir la app.
![imagen](https://user-images.githubusercontent.com/83564327/205417246-63caa40c-2b00-49bc-9c44-c6d36cdf99cc.png)

2. Modelo del ciclo MVP iterativo

El modelo del ciclo MVP se refiere a que cada equipo se enfocará en ciclos pequeños para construir partes más pequeñas de una app que en conjunto se puedan ir ensamblando para hacer la app completa.

Resuelve el problema del modelo anterior, aquí se recibe el feedback al terminar cada pequeño ciclo, recibiendo así el feedback de manera más inmediata que antes.

![imagen](https://user-images.githubusercontent.com/83564327/205417323-08678edb-8bb6-4ebb-a6de-5e039b0a17e5.png)


### Análisis: componentes y comportamientos

Componentes: son la forma de estructurar las piezas de nuestra página web para hacerlas escalables, nos ahorran tiempo y esfuerzo. Son abstracciones de los elementos de nuestra página web para ser reusados las veces que necesitemos.

Los componentes pueden trabajar de manera independiente a los demás, pero con React todos los componentes tienen una conexión con el resto de componentes, para que en conjunto puedan reaccionar al comportamiento de los usuarios.

Comportamiento: cómo actúan nuestros componentes con las interacciones de los usuarios.

### Cambios en React 

React 18 fue publicado el 29 de marzo de 2022. Sus cambios más importantes van a ayudar muchísimo para optimizar el render e hidratación de aplicaciones o componentes de React en el DOM. El más importante, crucial y significativo fue la migración de ReactDOM.render a ReactDOM.createRoot.

En la próxima clase vamos a usar Create React App, una de las herramientas más populares para instalar un entorno de desarrollo con React.js de forma muy rápida. No hay absolutamente ningún problema si decides usar React 18. Solo ten en consideración los cambios para hacer el render principal de tu aplicación.
Migración de ReactDOM.render a ReactDOM.createRoot

Antes de React 18:

      const root = document.getElementById('root');
      ReactDOM.render(e(LikeButton), root);

Desde React 18:

      const rootElement = document.getElementById('root');
      const root = ReactDom.createRoot(rootElement);
      root.render(e(LikeButton));

Antes de React 18:

     ReactDOM.render(
       <React.StrictMode>
         <App />
       </React.StrictMode>,
       document.getElementById('root')
     );

Desde React 18:

     const rootElement = document.getElementById('root');
     const root = ReactDom.createRoot(rootElement);

    root.render(
      <React.StrictMode>
        <App />
      </React.StrictMode>
    );

Actualizaciones de React

En los siguientes recursos puedes estudiar más a detalle los cambios de React y ReactDOM en su versión 18:

<a href="https://platzi.com/blog/react-conf-2021/">-React Conf 2021: anuncios, cambios y el futuro de React.js</a>

<a href="https://github.com/facebook/react/blob/main/CHANGELOG.md">-CHANGELOG de React</a>

<a href="https://reactjs.org/blog/2022/03/29/react-v18.html">-React 18 is now available on npm!</a>

<a href="https://reactjs.org/blog/2022/03/08/react-18-upgrade-guide.html">-How to Upgrade to React 18</a>

Además, si quieres conocer un poco más a fondo la filosofía y principios de diseño de React para elegir cómo hacer sus actualizaciones, te recomiendo tomar la siguiente clase:

    Filosofía y principios de diseño en React

    ⚠️ Si apenas estás empezando tu ruta de aprendizaje con React.js, no tienes que preocuparte por nada de esto. Todas las herramientas se actualizan constantemente, igual que los cursos de Platzi. Esa es la norma y el día a día en el mundo de la tecnología. Más adelante comprenderás la importancia y lo divertido de todas estas actualizaciones.

