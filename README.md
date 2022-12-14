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

### Instalacion con Create React App 

Una manera muy sencilla de crear un proyecto con React es utilizando Create React App, así puedes iniciar un proyecto sin preocuparte por la configuración de herramientas como webpack o babel.

💡 Aunque siempre será mejor si nosotros hacemos esta configuración desde cero, ya que tendremos mayor control de todo e incluso nuestra aplicación tendría un mejor rendimiento.
Maneras de instalar React

Existen varias formas de trabajar con React, cada una tiene sus ventajas y desventajas, siempre que trabajemos con React necesitaremos las dependencias react y react-dom.
React en JavaScript vanilla

Podemos importar los scripts del código fuente de React, existen las versiones para desarrollo que nos facilita debuggear y para producción que está optimizada para el producto final.

React con JavaScript vanilla casi no se usa, lo ideal es crear un entorno de desarrollo que facilite nuestro trabajo.
Configuración manual desde cero

Es la mejor manera si queremos tener control absoluto de nuestro entorno de desarrollo, necesitamos emplear y configurar varias herramientas.
Create React App

Esta es la manera más simple y rápida para trabajar con React, solo necesitamos ejecutar el comando: npx create-react-app nombre-del-proyecto o npx create-react-app nombre-del-proyecto --template typescript para typescript y en unos instantes tendremos un entorno de desarrollo totalmente configurado para comenzar a trabajar.
Entorno de Create React App

Dentro de este entorno tenemos un archivo package.json en el que se encuentran nuestros scripts, dependencias y meta datos de nuestro proyecto, también tendremos dos carpetas principales:

    public/: Es la carpeta pública en donde tendremos nuestro archivo HTML y algunos assets
    src/: Es la carpeta fuente, en donde tendremos todos nuestros archivos de trabajo

Dentro del index.html siempre tendremos un div con un id, como root que será la raíz de nuestro proyecto, y la usaremos para empezar a construir con JavaScript:

 <!-- Aquí es en donde todo nuestro código será renderizado. -->
 <div id="root"></div>

¿Cómo inicializar nuestro servidor?

Para iniciar el entorno de desarrollo podemos ejecutar el comando npm start, con esto tendremos nuestro servidor corriendo en el puerto 3000 y también se refrescará automáticamente con cualquier cambio hecho en el proyecto. (A excepción de los cambios hechos en el archivo index.js).


## JSX: COMPONENTES VS ELEMENTOS 

SX es una extensión de JavaScript creada por Facebook para usarse con React.js. Nos presenta muchas ventajas el trabajar con elementos y componentes muy similar a la sintaxis de HTML.

La función que JSX tiene es de ser un preprocesador y transformar el código a JavaScript.

💡 JSX es solamente azúcar sintáctica para el método React.createElement(component, props, ...children) de React.

Nota: dentro del código encontrarás comentarios que explicarán que es lo que se está añadiendo o algunos consejos.
¿Cómo crear un componente?

Existen varias formas de crear un componente en React, por convención siempre los creamos utilizando PascalCase (La primera letra de cada palabra en mayúscula y juntas).
Crear un componente con clases

Este es el modo que se empleaba antes, ahora ya casi nadie la utiliza, pero es bueno saber cómo funciona, por si llegamos a trabajar con proyectos que las usen, con el método render podemos renderizar el JSX que retorna nuestra clase.

	class Componente extends React.Component {
		render() {
			return (
			    // JSX
			)
		}
	} 

Podemos agregar JSX entre los paréntesis del return.
Crear un componente con funciones

Los componentes funcionales son los más utilizados hoy en día, ya que nos permiten controlar el ciclo de vida mucho más fácil con los hooks de React:

		function Component() {
		    return (
			// JSX
		    )
		} 

		// Utilizando arrow function
		const Component = () => {
		    return(
			// JSX
		    )
		}

### Componentes vs. Elementos

Los componentes son invisibles para HTML, pero no para React, de hecho React utiliza los componentes para renderizar, y optimizar los re-renderizados.
Componente

Un componente es una pieza de código que describe una parte reutilizable de la interfaz, recibe propiedades y retornan elementos, dentro de los componentes podemos utilizar variables de JavaScript con ayuda de las llaves {}.

	const Component = () => {
	    const titulo = Soy un título;

	    return(
		<h1>{titulo}</h1>
	    )
	}

### Elemento

Un elemento es lo que devuelve un componente, es una representación de un nodo en el DOM.

	<h1>Soy un título</h1>

### Propiedades vs. Atributos

La diferencia principal es que un atributo no se puede modificar y una propiedad si, ya que los atributos son de HTML y las propiedades son de JavaScript.
Atributo

Los atributos los pueden tener las etiquetas de HTML.

    <!-- Por ejemplo el atributo class -->
    <h1 class="titulo">Soy un título</h1>

### Propiedad

Las propiedades las pueden recibir los elementos y componentes en React.

	const Component = () => {
	    return(
		<h1 className="titulo">
		    Soy un titulo
		</h1>
	    )
	}

Es importante notar que algunos atributos de HTML se escriben diferente como propiedades, por ejemplo; el atributo class de HTML no se debe utilizar como propiedad de una clase o elemento de React, ya que class es una palabra reservada para crear clases en JavaScript, en su lugar utilizamos className.


### Pasando propiedades a nuestros componentes

Algo mágico de React es que podemos pasarle propiedades a nuestros componentes.

		// Le pasamos la propiedad saludo
		<Componente saludo="Oli" />

		const Componente = (props) => {
		    // Recibimos las propiedades

		    return(
			{/* ¡Así creamos un comentario en JSX! */}
			{/* Accedemos a saludo desde las props */}
			<h1 className="titulo">
			    {props.saludo} 
			    {/* props.saludo = Oli */}
			</h1>
		    )
		}

### Propiedad children

También podemos utilizar los componentes de React como etiquetas abiertas, para pasarle contenido, elementos o incluso otros componentes, la manera de acceder a ellos es con la propiedad especial children.

		<Componente>
		    <h1>¡Soy un título anidado!</h1>
		</Componente>

		const Componente = (props) => {
		    return(
			<div className="titulo">
			    {props.children}
			    {/* props.children = <h1>¡Soy un título anidado!</h1> */}
			</div>
		    )
		}
