# Jose.work.2

Introducción a CSS:

1. ¿Qué es CSS y para qué sirve? 

Cascading Styles Sheet o en español hoja de estilo en cascada es básicamente un
lenguaje de diseño gráfico que se complementa con html
para dar el estilo visual y animativo en una web.

2. ¿Cómo se relaciona CSS con HTML?

Como vimos antes, CSS se relaciona con HTML principalmente
para dar un estilo a nuestro proyecto, de manera que tengamos una
página web visualmente más atractiva y dinámica, para ofrecer
una experiencia más satisfactoria e inmersiva a nuestro cliente.

3. ¿Qué son las hojas de estilo en cascada (Cascading Style Sheets)?

Una hoja de estilos es una serie de códigos que definen
el aspecto o presentación de los elementos de una página.
El término cascada se refiere a como están distribuidos nuestros elementos
desde el componente primario hasta los detalles más específicos.

4. ¿Cuáles son las ventajas de usar CSS?

   Tener una mejor estética en nuestra página web.
   Ofrecer una experiencia más dinámica a nuestro cliente.
   Estilos diferentes en cada proyectos.
   Mejor accesibilidad en la navegación.

5. ¿Dónde puedo encontrar recursos para aprender CSS?

Podemos conseguir campamentos de CSS, cursos tanto pagos como gratuitos por ejemplo en Youtube, y también
disponemos de páginas web que nos ofrecen juegos basados en la práctica de código CSS
que nos ayudan a familiarizarnos, estas pueden ser:

   1- Flexbox Froogy
   
   2- CSS Grid Garden
   
   3- CSS Diner

**Sintaxis básica de CSS:**

6. ¿Cómo se escribe una regla CSS?

Para colocar una regla CSS tendremos 
nuestro selector que podria ser por tipo, clase
o id. Luego dentro de unas cejillas "{}" (a esto le llamaremos
bloque de declaracion) colocamos nuestras dos declaraciones
con su propiedad y valor quedando así:

h1, clase, #id {propiedad: valor; propiedad: valor;}

7. ¿Qué son los selectores CSS?

Los selectores CSS son el valor de nuestra regla que manda a llamar
el elemento, clase, o id al que queramos aplicarle una propiedad de css.

8. ¿Qué son las propiedades CSS?

Las propiedades de nuestra regla CSS es el cambio visual que 
queremos aplicarle al selector que elejimos, como pueden ser
el background-color, el font-size, etc...

9. ¿Qué son los valores CSS?

Un valor de CSS es el atributo de ese cambio visual 
que queremos cambiar pudiendo ser el color de nuestro background-color o
los px, em o rem de nuestro font-size.

10. ¿Cómo se aplica un estilo CSS a un elemento HTML?

Hay tres modos para aplicar un estilo CSS a un elemento HTML.

Colocar la etiqueta <styles> dentro del <head> de nuestro HTML
y dentro de nuestra etiqueta styles colocar nuestro código de CSS.

Estilos embebidos, esta forma de aplicar un estilo CSS es escribiendo nuestro style
directamente en nuestro elemeto, por ejemplo dentro de nuestro elemento colocaremos
como atributo "style" y como valor la propiedad y valor de CSS que querramos aplicar.

Hoja de estilos, este método es el más recomendable para aplicar
reglas CSS, lo hacemos linkeando nuestro archivo index con la hoja de estilos 
que va a tener nuestro código de CSS con las siguientes líneas de código:

<"head">
 link rel="stylesheet" href="./styles.css"
 <"head">


11. ¿Qué tipos de selectores CSS existen?

Existen selectores por tipo, id, por clase, universal, descendientes, adyacentes, pseudoclase y pseudoelementos.

12. ¿Cómo seleccionar elementos por tipo?

Para seleccionar por tipo vamos a elegir la etiqueta de nuestro codigo de esta manera:

h1 {propiedad:valor; propiedad: valor;}


13. ¿Cómo seleccionar elementos por ID?

#id-correspondiente {propiedad: valor; propiedad: valor;}

14. ¿Cómo seleccionar elementos por clase?

.nombre-de-nuestra-clase {propiedad: valor; propiedad: valor;}

15. ¿Cómo seleccionar elementos descendientes?

En este seleccionamos un elemento dentro de otro asi:

div h1 {propiedad: valor; propiead: valor;}


16. ¿Cómo seleccionar elementos adyacentes?

elemento_anterior + elemento_afectado {propiedad: valor; propiead: valor;}

**Propiedades CSS básicas:**

17. ¿Cómo cambiar el color del texto?

h1 {color: red;}

18. ¿Cómo cambiar el tamaño de la fuente?

html {font-size: 62.5%;}

19. ¿Cómo agregar un borde a un elemento?

.clase1 {border-style: dotted;} 

20. ¿Cómo modificar el margen y el relleno de un elemento?

header {padding: 400px; margin: 0 auto;}


