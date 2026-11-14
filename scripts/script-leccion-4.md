Guion - Lección 4: Introducción a CSS (10 minutos)

**Responsable:** Luis Alonso Huaco Oliva
**Formato:** Narración en off + grabación de pantalla en CodePen  
**Nota para el video:** En CodePen el HTML y el CSS van en paneles separados. No necesitas escribir `<link>` ni `<style>`; eso se explica solo como concepto.

---

**Visual:** Pantalla con el CodePen starter abierto.

**Narración:**

> “¡Hola a todos! Bienvenidos a la Lección 4. En las lecciones anteriores aprendimos a crear la estructura de una página con HTML: títulos, párrafos, imágenes, listas y enlaces. Pero hasta ahora todo se ve muy simple, sin colores ni estilos. Hoy vamos a conocer CSS, el lenguaje que nos permite darle color, forma y diseño a nuestras páginas. Al terminar esta lección, tu página se verá mucho más atractiva. ¡Vamos a ello!”
> 
> “CSS significa Hojas de Estilo en Cascada. Es el lenguaje que usamos para dar estilo al HTML. Mientras HTML es el esqueleto, CSS es la ropa y los colores. En CodePen, el CSS va en el panel de la derecha. Si estuvieras trabajando en un proyecto real, crearías un archivo `styles.css` y lo enlazarías con la etiqueta `<link>`, pero en CodePen ya está todo listo.
>
> La estructura básica de una regla CSS es: primero escribimos un selector, que indica a qué elemento queremos aplicar el estilo. Luego abrimos llaves `{}` y dentro escribimos las propiedades con sus valores, separadas por punto y coma. Por ejemplo:
> 
> Eso hará que todos los títulos `h1` sean de color azul.”

> “Empecemos con el `body`, que es el cuerpo de nuestra página. Vamos a cambiar el color de fondo, la fuente y centrar el texto.
>
> Primero, `background-color` para el fondo. Puedes usar nombres de colores como `lightblue` o códigos como `#f0f8ff`. Luego `font-family` para cambiar la letra; usaremos `Arial, sans-serif`. Y `text-align: center` para centrar todo el texto.
>
> Observa cómo el fondo cambia inmediatamente. Eso es CSS en acción.”
> 
> “Ahora vamos a darle color al título principal. Usamos el selector `h1` y la propiedad `color`. Elegimos un azul oscuro, por ejemplo `#2c3e50`.
>
> Luego, para los párrafos, usamos el selector `p`. Podemos cambiar el tamaño de la letra con `font-size` y el color con `color`. Pondremos un gris suave para que no sea tan fuerte.
>
> Recuerda: los selectores de etiqueta afectan a todos los elementos de ese tipo. Más adelante veremos selectores de clase para ser más específicos.”
> 
> “Ahora vamos a estilizar una caja. En el HTML tenemos un `div` con la clase `caja`. Para seleccionar una clase en CSS, escribimos un punto antes del nombre: `.caja`.
>
> Vamos a agregar un borde con `border: 3px solid #3498db;`. Luego, espacio interno con `padding: 20px;`. Para centrar la caja horizontalmente, usamos `margin: 20px auto;`. También le damos un fondo blanco con `background-color: white;` y bordes redondeados con `border-radius: 10px;`.
>
> ¡Mira cómo la caja ahora se ve como una tarjeta! Este es el mismo concepto que usarás en la Lección 5 para crear tu página de perfil.”
> 
> “Repasemos lo que aprendimos. Usamos selectores de etiqueta como `body`, `h1` y `p`, y un selector de clase como `.caja`. Aprendimos propiedades como `background-color`, `color`, `font-family`, `text-align`, `border`, `padding`, `margin` y `border-radius`.
>
> Recuerda que en CSS las propiedades van dentro de llaves y terminan con punto y coma. Si algo no funciona, revisa que no falte un punto y coma o una llave.”
> 
> “¡Y listo! Ya sabes cómo darle estilo a una página web con CSS. Te dejo el enlace al CodePen de práctica para que completes los estilos por tu cuenta. En la siguiente lección usaremos todo esto para crear una página de perfil personal. ¡Nos vemos allá!”