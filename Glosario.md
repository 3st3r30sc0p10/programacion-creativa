## Glosario: Términos / Conceptos

Una serie de términos que nos sirven para tener un lenguaje común y aprender a buscar soluciones a problemas específicos.

|Español|Inglés|
|---|---|
|Tipos de variables (diferencias entre `const`, `let`, `var`)|Variables|
|Tipos de funciones (`function(){...}` vs. `() => {...}` vs. `() => ...` )|Arrow functions|
|Modelo de Objetos del Documento (MOD)|Document Object Model (DOM)|
|Elementos del MOD|DOM Elements|
|MOD virtual|Virtual DOM|
|Manipulación del MOD|DOM Manipulation|
|Eventos Sensibles|Eventlisteners|
|[Sintaxis](#sintaxis)|Sintax|
|JavaScript Nativo|Vanilla JavaScript|
|JavaScript Compilado (ES6 o TypeScript -> JS)|Compiled JavaScript|
|CSS Nativo|CSS / Vanilla CSS|
|CSS Compilado (SASS o LESS -> CSS)|Compiled CSS / superset of CSS|
|Compilador / Transpilador (Babel) [ref.](https://www.stevefenton.co.uk/2012/11/compiling-vs-transpiling/)|Compiler / Transpiler|
|Empaquetador (Webpack, Parcel, Rollup, Snowpack, ...)|Bundler|
|Manipulación de pixeles|Pixel Manipulation|
|Dibujo Generativo|Generative Drawing|
|Telemática|Telematic|
|[Programación creativa](#programación-creativa)|Creative Programing|
|Comunicación en tiempo real (WebSockets, WebRTC)|Real-time communication|
|Sincrónico - Asincrónico (Promises, Async, Await)|Blocking - Non-Blocking / Synchronous - Asynchronous|
|[Programación orientada a objetos (POO)](#programación-orientada-a-objetos-poo)|Object Oriented Programming (OOP)|
|Frontal - *backend* / servidor (JS, NodeJS) |Frontend - Backend|
|Paquetes|Package Manager (NPM)|
|Interfaz programable de aplicación|Application Programmable Interface (API)|
|Lógica vs. Algoritmo|Logic vs. Algorithms|
|Vectores|Vectors|
|Matrices, Matriz|Matrices, Matrix|
|Render con CPU vs. GPU (contexto del `canvas` 2d vs WebGL)|CPU vs GPU rendering|
|[Interfaz de Programación de Aplicaciones (API)](#interfaz-de-programación-de-aplicaciones-api)|Application Programming Interface API|

## Ejercicio

- Crear un branch `terminos-NOMBRE`.
- Seleccionar al menos 2 términos (más si quieren) y escribir definiciones cortas de estos en un lenguaje que tenga sentido para ustedes. Si el término ya esta definido en "Definiciones" pueden sugerir cambios o agregar contenido.
- Buscar 1 término adicional que les interesa entender, sumarlos a la lista y escribir su definición corta.
- Hacer un hipervínculo desde el término en español en la tabla y la definición usando anclas.

## Definiciones

Definiciones no-técnicas de conceptos técnicos.

### Sintaxis

La forma, las reglas y la estructura que debe tener un lenguaje de programación para que la máquina lo entienda correctamente. 

### Programación Creativa

Negociar con las máquinas un gesto artístico. Es un acto de agenciamiento entre potencias físicas y potencias del dispositivo. En el mejor de los casos produce un devenir en artista post-humano.

### Programación orientada a objetos POO
Es un paradigma de programación (es decir, una forma de entender la construcción de un programa) en el cual se estructura el código en piezas simples y reutilizables llamadas clases, a partir de las cuales se crean objetos. Estos objetos y clases se relacionan entre sí, tienen ciertas características (atributos) y son capaces de llevar a cabo ciertas acciones (funciones) dentro del programa. Algunas clases (hijas) pueden heredar atributos y funciones de otras clases (madres). <br> Típico ejemplo: Una clase madre Animal puede tener clases hijas Perro, Gato, Vaca. Todos los objetos de la clase Animal (y por extensión Perro, Gato, Vaca) tendrán un color, un peso, un tamaño (atributos) y podrán desplazarse y alimentarse (funciones). Un objeto de la clase Gato, por ejemplo, heredará de su clase madre Animal los atributos y funciones anteriores y sumará los suyos propios: colorDeBigotes (atributo) y maullar (función). 

### Interfaz de Programación de Aplicaciones API

Conjunto de reglas que hacen posible la comunicación entre distintas aplicaciones, por ejemplo entre sistemas operativos, bases de datos, redes sociales y otras plataformas online. Son especialmente útiles porque permiten aprovechar fragmentos de código de un programa en otro, sin necesidad de reinventarlos ni reescribirlos.