# Animated Login Form
## Explicación para la creación de este formulario.

Basados en la clase _*.login*_ que envuelve a la imagen de fondo y al formulario, podemos decir que: 
---
**position: relative**: Este atributo establece el método de posicionamiento del elemento. En este caso, se establece en "relative", lo que significa que la posición del elemento se basará en su posición original, y no se moverá en relación a otros elementos de la página.

**height: 100vh;**: Este atributo establece la altura del elemento. En este caso, se establece en "100vh", lo que significa que la altura del elemento será igual al 100% del tamaño de la ventana del navegador (la altura visible de la página).

**display: grid;**: Este atributo establece el método de visualización del elemento. En este caso, se establece en "grid", lo que significa que el elemento será un contenedor de elementos que serán organizados en una cuadrícula.

**align-items: center;**: Este atributo establece la alineación vertical de los elementos dentro del contenedor. En este caso, se establece en "center", lo que significa que los elementos dentro del contenedor serán centrados verticalmente.

En resumen, los atributos establecidos en el selector .login hacen que el contenedor tenga una altura igual al 100% del tamaño de la ventana del navegador, que los elementos dentro del contenedor se alineen verticalmente al centro y que el contenedor sea un contenedor de elementos organizados en una cuadrícula.

Ahora para la clase *_.login__img_*:
---
**position: absolute;**: Este atributo establece el método de posicionamiento del elemento. En este caso, se establece en "absolute", lo que significa que la posición del elemento se basará en su contenedor padre y se posicionará en relación a él.

**width: 100%;**: Este atributo establece el ancho del elemento. En este caso, se establece en "100%", lo que significa que la imagen se ajustará al ancho completo del contenedor padre.

**height: 100%;**: Este atributo establece la altura del elemento. En este caso, se establece en "100%", lo que significa que la imagen se ajustará a la altura completa del contenedor padre.

**object-fit: cover;**: Este atributo establece cómo se ajustará la imagen al contenedor padre en caso de que la relación de aspecto de la imagen no coincida con la relación de aspecto del contenedor padre. En este caso, se establece en "cover", lo que significa que la imagen se ajustará al contenedor padre de manera que cubra todo el área disponible y que no deje espacios en blanco.

**object-position: center;**: Este atributo establece la posición de la imagen dentro del contenedor padre en caso de que la imagen sea más pequeña que el contenedor padre. En este caso, se establece en "center", lo que significa que la imagen se centrará verticalmente y horizontalmente dentro del contenedor padre.

En resumen, los atributos establecidos en el selector .login__img hacen que la imagen dentro del contenedor tenga una posición absoluta en relación al contenedor padre, que la imagen se ajuste al ancho y altura completa del contenedor padre y que se centre vertical y horizontalmente dentro del contenedor padre. Además, el atributo object-fit: cover hace que la imagen cubra todo el área disponible en caso de que la relación de aspecto de la imagen no coincida con la del contenedor padre.

Ahora la explicación del *_.login__form_*:
---
**position: relative;**: Este atributo establece el método de posicionamiento del elemento. En este caso, se establece en "relative", lo que significa que la posición del elemento se basará en su posición original, y no se moverá en relación a otros elementos de la página.
En resumen, el atributo establecido en el selector .login__form hace que el formulario tenga una posición relativa a su posición original en la página. Esto significa que si se aplica algún otro estilo como top, bottom, left o right, el formulario se moverá en relación a su posición original.

Resumen:
---
En el caso del contenedor padre .login, éste tiene control sobre las clases .login__img y .login__form ya que ambos elementos son hijos directos del contenedor .login.

Por lo tanto, cualquier estilo aplicado al contenedor padre .login también afectará a los elementos hijos .login__img y .login__form. Sin embargo, los estilos aplicados a los elementos hijos no afectarán al contenedor padre, a menos que se apliquen estilos específicos para ello.

Cada uno de los elementos hijos, .login__img y .login__form, pueden tener estilos propios que afecten únicamente a ellos mismos y no a los demás elementos, pero siempre estarán dentro del contenedor .login.

En resumen, el contenedor .login tiene control total sobre sus elementos hijos directos, .login__img y .login__form, pero cada elemento puede tener estilos específicos que sólo se aplicarán a él y no afectarán al resto de los elementos dentro del contenedor .login.

Añadiendo estilos CSS a nuestro *_login__form_*:
---
**background-color**: hsla(0,0%,10%,.1);: Este atributo establece el color de fondo del elemento. En este caso, se establece en un color en formato HSLA con un valor de opacidad del 10%. Esto significa que el fondo será un poco transparente.

**border**: 2px solid var(--white-color);: Este atributo establece el borde del elemento. En este caso, se establece en un borde sólido de 2px de ancho y de color blanco, utilizando una variable CSS para definir el color.

**margin-inline**: 1.5rem;: Este atributo establece el margen del elemento en los lados inline (izquierdo y derecho) del elemento. En este caso, se establece en 1.5 rem, que es una unidad de medida relativa que representa el tamaño de la fuente del elemento.

**padding**: 2.5rem 1.5rem;: Este atributo establece el relleno del elemento en la parte interior del borde. En este caso, se establece en 2.5 rem para la parte superior e inferior del elemento y en 1.5 rem para los lados izquierdo y derecho.

**border-radius**: 1rem;: Este atributo establece el radio de los bordes del elemento. En este caso, se establece en 1 rem, lo que significa que los bordes del elemento tendrán un radio suave de 1 rem.

**backdrop-filter**: blur(8px);: Este atributo aplica un efecto de desenfoque al fondo del elemento. En este caso, se establece en un desenfoque de 8px, lo que significa que el fondo se verá desenfocado detrás del elemento.

En resumen, los atributos que has añadido a la clase .login__form afectan al estilo visual del formulario. Estos incluyen el color de fondo, el borde, el margen, el relleno, el radio de los bordes y el efecto de desenfoque del fondo.

---
Estilos al título *_login__title_*:
---
**text-align**: center; establece que el texto dentro del elemento se debe alinear en el centro horizontalmente.

**font-size**: var(--h1-font-size); establece el tamaño de fuente del texto a través de una variable CSS personalizada llamada --h1-font-size. El valor de esta variable se debe definir en otra parte del CSS o en un archivo de variables.

**font-weight**: var(--font-medium); establece el peso de la fuente del texto a través de otra variable CSS personalizada llamada --font-medium. Al igual que --h1-font-size, el valor de esta variable también debe definirse en otra parte del CSS o en un archivo de variables.

**margin-bottom**: 2rem; establece el margen inferior del elemento en 2 rem (otra unidad de medida relativa al tamaño de la fuente).

En resumen, estos estilos CSS aplicados al elemento login__title establecen la apariencia visual del título de la sección de inicio de sesión, incluyendo la alineación del texto, el tamaño de la fuente y el peso, y el margen inferior.


Estilos a las clases *_login__content/login__box_*:
---
**.login__content**, **.login__box** { display: grid; }: este estilo se aplica a los elementos con las clases login__content y login__box y establece que se deben mostrar como una cuadrícula. Esto significa que cualquier contenido dentro de esos elementos se organizará en filas y columnas.

**.login__content** { row-gap: 1.75rem; margin-bottom: 1.5rem; }: este estilo se aplica solo al elemento con la clase login__content. row-gap establece el tamaño del espacio entre las filas en la cuadrícula, en este caso, 1.75 rem (unidades de medida relativas al tamaño de la fuente). margin-bottom establece el margen inferior del elemento, en este caso, 1.5 rem.

En resumen, estos estilos establecen que los elementos con las clases login__content y login__box se deben mostrar como cuadrículas y especifican el tamaño del espacio entre filas y el margen inferior del elemento login__content.

Estilos a la clase *_Login__box_*:
---
**grid-template-columns**: max-content 1fr; establece las columnas de la rejilla grid en la que se organiza el contenido del elemento login__box. En este caso, la primera columna tendrá una anchura máxima equivalente al ancho del contenido que contenga, mientras que la segunda columna ocupará todo el espacio restante disponible (1fr).

**align-items**: center; establece la alineación vertical de los elementos secundarios del contenedor en el centro.

**column-gap**: .75rem; establece la distancia entre las columnas en el contenedor en .75rem (otra unidad de medida relativa al tamaño de la fuente).

**border-bottom**: 2px solid var(--white-color); establece una línea de borde inferior en el contenedor con un ancho de 2 píxeles y un estilo sólido. El color del borde se establece a través de una variable CSS personalizada llamada --white-color.

En resumen, estos estilos CSS se aplican al elemento login__box para organizar el contenido en una rejilla y establecer la alineación vertical y la separación entre las columnas. Además, se agrega una línea de borde inferior al contenedor para separarlo visualmente del contenido siguiente.

Estilos para las clases *_login__icon/login__eye_*:
---
Ambas clases tienen el mismo estilo, así que se explicarán juntas.

**font-size**: 1.25rem; establece el tamaño de la fuente de los elementos que tengan las clases login__icon o login__eye en 1.25 veces el tamaño de la fuente de su elemento padre. Es decir, si el tamaño de fuente del elemento padre es de 16 píxeles, el tamaño de fuente de estos elementos será de 20 píxeles.

En resumen, estos estilos CSS se aplican a los elementos que tengan las clases login__icon o login__eye para establecer su tamaño de fuente en 1.25 veces el tamaño de fuente del elemento padre. Probablemente se use esta clase para definir iconos o elementos visuales en la interfaz de usuario del formulario de inicio de sesión.

Estilo para los inputs *_login__input_*:
---
**width**: 100%; establece el ancho del elemento que tenga la clase login__input en el 100% del ancho disponible de su elemento padre.

**padding-block**: .8rem; establece el relleno (padding) vertical del elemento en 0.8 veces el tamaño de la altura de su fuente. El relleno vertical es el espacio entre el borde del elemento y el contenido del elemento.

**background**: none; establece que no se aplique ningún color de fondo al elemento que tenga la clase login__input. Esto es útil si se desea que el fondo sea transparente o que el fondo sea proporcionado por un elemento envolvente.

**color**: var(--white-color); establece el color de texto del elemento que tenga la clase login__input en la variable de CSS --white-color, que probablemente sea blanco.

**position**: relative; establece la posición del elemento que tenga la clase login__input como "relativa". La posición "relativa" permite desplazar el elemento en relación a su posición original mediante el uso de las propiedades "top", "right", "bottom" y "left".

**z-index**: 1; establece la propiedad "z-index" del elemento que tenga la clase login__input en 1. La propiedad "z-index" define la posición de apilamiento de los elementos en la interfaz de usuario, permitiendo que los elementos se superpongan entre sí. El valor más alto de "z-index" corresponde al elemento que se encuentra en la parte superior de la pila.

En resumen, estos estilos CSS se aplican a los elementos que tengan la clase login__input para establecer su ancho al 100% del ancho disponible de su elemento padre, establecer el color del texto en blanco, y establecer una posición relativa con una propiedad "z-index" de 1.

Explicación del position aplicado a la clase *_login__box-input_*:
---
La razón por la que se utiliza la propiedad "position: relative" en la clase ".login__box-input" es para permitir el posicionamiento relativo de los elementos secundarios en relación con este contenedor.

En el código HTML, ".login__box-input" contiene un campo de entrada de correo electrónico (input) y una etiqueta de texto (label) para identificar el campo. Al establecer la posición relativa en este contenedor, se permite el posicionamiento de la etiqueta de texto "Email" encima del campo de entrada mediante la propiedad "position: absolute" en la clase ".login__label".

De esta manera, la posición de la etiqueta de texto puede ser ajustada en relación con el contenedor ".login__box-input", lo que permite la colocación adecuada del texto sobre el campo de entrada.

Estilos para la clase *_login__label_*:
---
La clase .login__label es utilizada para estilizar la etiqueta label que acompaña al campo de entrada input. Los atributos CSS que se le han dado son los siguientes:

**position**: absolute;: establece la posición del elemento como absoluta en relación con el primer elemento posicionado (no estático) encontrado en el flujo de documentos. En este caso, el elemento padre .login__box-input tiene una posición relativa, lo que hace que el posicionamiento absoluto de .login__label sea en relación con su contenedor padre.

**left**: 0;: establece la posición del borde izquierdo del elemento en relación con el borde izquierdo del elemento contenedor.

**top**: 13px;: establece la posición del borde superior del elemento en relación con el borde superior del elemento contenedor. En este caso, se ha especificado una distancia de 13 píxeles desde la parte superior del elemento contenedor.

**font-weight**: var(--font-medium);: establece el grosor de la fuente del texto dentro del elemento label. Se ha utilizado la variable CSS --font-medium, que se ha definido en otro lugar del código CSS.

**transition**: top .3s, font-size .3s;: establece una transición suave de 0.3 segundos para el cambio en la posición vertical de la etiqueta label (top) y su tamaño de fuente (font-size) cuando el campo de entrada input se enfoca. Esto crea un efecto suave de animación cuando se mueve la etiqueta hacia arriba y se reduce su tamaño de fuente.

Estilos para *_login__eye_*:
---
La clase .login__eye se refiere a un icono de ojo que se utiliza para mostrar u ocultar la contraseña del usuario al hacer clic en él. Los estilos que se le aplican son los siguientes:

**position**: absolute: esto hace que el icono se posicione de forma absoluta en relación con el contenedor que tenga como "padre" con position: relative.

**right**: 0: se ubica en la esquina derecha del contenedor que lo contiene.

**top**: 18px: se coloca a 18 píxeles desde la parte superior del contenedor que lo contiene.

**z-index**: 10: esto establece el orden de apilamiento de elementos. Los elementos con un valor de z-index más alto se sitúan encima de los elementos con un valor menor.

**cursor**: pointer: hace que el cursor del ratón cambie a un puntero para indicar que el elemento es "clickeable".

Estilo para la clase *_.login__box:nth-child(2) input_*:
---
La regla CSS ".login__box:nth-child(2) input" selecciona el segundo elemento de la clase "login__box" en el documento HTML y aplica un estilo a su elemento descendiente "input".

El estilo que se aplica es "padding-right: 1.8rem;", lo que significa que se añade un relleno (padding) de 1.8rem de ancho en el lado derecho del elemento "input".

Esto podría ser útil para separar visualmente el campo de entrada de texto del botón o icono que se encuentra a su lado derecho. Al agregar este relleno, se crea un espacio adicional en el lado derecho del campo de entrada de texto, permitiendo que el botón o el icono se distingan claramente del campo de entrada de texto.

---
¿Por qué el div con la clase .login__check envuelve solamente a otro div con la clase .login__check-group?
---
En cuanto a la estructura del HTML, el primer div que envuelve a otro div, es probablemente una manera de agrupar los elementos relacionados visualmente en la página. En este caso, el div con la clase login__check probablemente contiene elementos que están relacionados con la verificación de la identidad del usuario, como el checkbox para recordar al usuario y el enlace "Forgot Password?".

Estilos para las clases *_login__check/login__check-group_*:
---
**display**: flex; establece un contenedor flexible, lo que permite que los elementos hijos se alineen horizontalmente.

**align-items**: center; alinea verticalmente los elementos hijos al centro del contenedor flexible.

**justify-content**: space-between; distribuye el espacio disponible entre los elementos hijos, colocando el primer elemento al inicio del contenedor y el último elemento al final, lo que crea un espacio en blanco entre ellos. En este caso, el espacio en blanco se encuentra entre el checkbox y el label con el texto "Remember me", y el elemento a con el texto "Forgot Password?".

Estilo y explicación de *_login__check_*:
---
La propiedad **margin-bottom** con valor de 1.5rem se le aplica al elemento con clase login__check, que es un elemento contenedor que envuelve a su hijo login__check-group.

En este caso, el margen inferior aplicado a login__check se debe probablemente para crear un espacio vertical entre el grupo de elementos de login__check-group y los elementos del formulario que están debajo. De esta manera, se logra una mejor separación visual entre los distintos elementos del formulario y se mejora la legibilidad y la estética del diseño.

Estilo para las clases *_.login__check-label/.login__forgot/.login__register_*:
---
**font-size**: var(--small-font-size); es una variable de CSS que se ha definido en algún lugar del código como un valor de tamaño de fuente específico, por lo que el tamaño de fuente real dependerá del valor que se le haya asignado a la variable.

En este caso, al establecer el tamaño de fuente en var(--small-font-size), se asegura una coherencia visual en el tamaño de fuente en toda la página, lo que facilita la legibilidad y la comprensión del contenido para los usuarios.

Estilo para *_login__check-group_*:
---
La clase .login__check-group se aplica a un contenedor que envuelve el checkbox para "Remember me" y el enlace "Forgot Password?". La propiedad **column-gap** establece la separación horizontal entre los elementos secundarios del contenedor en un diseño de cuadrícula. En este caso, se establece en .5rem, lo que significa que habrá un espacio de .5rem entre el checkbox y el texto "Remember me", y otro espacio de .5rem entre el texto "Remember me" y el enlace "Forgot Password?".

Estilos para *_login__check-input_*:
---
La clase .login__check-input es aplicada a un elemento de tipo input con el atributo type="checkbox" que representa un elemento de casilla de verificación. Estos estilos definen el ancho y la altura de la casilla de verificación con una dimensión de 16 píxeles para cada lado. En otras palabras, esta regla de CSS establece el tamaño de la casilla de verificación.

Explicacion para los estilos *_login__forgot/login__forgot:hover_* :
---
Estos estilos definen la apariencia y comportamiento de un enlace (un elemento `<a>`) que tiene la clase .login__forgot.

El primer bloque de estilos establece el color de texto del enlace como el color blanco (var(--white-color)) y el segundo bloque define un efecto de subrayado (text-decoration: underline) cuando se coloca el cursor sobre el enlace (:hover).

En resumen, estos estilos definen un enlace que aparece en el formulario de inicio de sesión como un texto de color blanco y que, cuando el usuario coloca el cursor sobre él, se muestra subrayado para indicar que es un enlace que puede ser clicado.


Estilos para el botón de logueo *_login__button_*:
---
**width**: 100%: La anchura del botón se establece en el 100% del ancho disponible en el contenedor.

**padding**: 1rem;: Se agrega un relleno interno de 1 rem al botón.

**border-radius**: .5rem;: Los bordes del botón se redondean mediante el valor 0.5rem del radio de borde.

**background-color**: var(--white-color);: El fondo del botón se establece en el color blanco definido en la variable --white-color.

**font-weight**: var(--font-medium);: La fuente del botón se define en el valor --font-medium definido en una variable CSS que contiene el peso de fuente adecuado.

**cursor**: pointer;: El cursor se cambia a un cursor de puntero para indicar que el botón es interactivo.

**margin-bottom**: 2rem;: Se agrega un margen inferior de 2 rem al botón para crear un espacio visual entre el botón y el siguiente elemento.

Estilos aplicados a *_Login__register/ a/ a:hover_* :
---
El primer estilo, **text-align**: center, centra el texto del elemento.

Los siguientes estilos, .login__register a, se aplican al elemento a que esté dentro del elemento con clase login__register. Estos estilos cambian el color del texto del enlace a var(--white-color) (probablemente blanco) y establecen su peso de fuente en var(--font-medium) (probablemente una fuente seminegrita o negrita).

El último estilo, .login__register **a:hover**, se aplica al enlace cuando se pasa el cursor sobre él. Agrega un subrayado al enlace con **text-decoration**: underline.

---
Ahora continuamos con 'Input focus move up label': "El enfoque del input mueve la etiqueta hacia arriba"
---
Estilos y explicación de *_.login__input:focus + .login__label_* :
---
Este selector CSS selecciona el elemento .login__label que sigue inmediatamente a un elemento .login__input cuando este último tiene el enfoque (cuando se hace clic en el input o se selecciona de otra manera).

La propiedad **top**: -12px indica que se moverá el elemento .login__label 12 píxeles hacia arriba cuando se aplique el enfoque al input, dando la apariencia de que el label se mueve hacia arriba del input.

La propiedad **font-size**: var(--small-font-size) establece el tamaño de fuente para el label cuando se mueve arriba. En este caso, está utilizando una variable CSS personalizada --small-font-size, que se define en otra parte del código.

En resumen, estos estilos cambian la posición y el tamaño del label cuando el input tiene el enfoque para que sea más visible y fácil de leer.

Explicacion de 'Input focus sticky top label':  Etiqueta superior fija al enfocar en el campo de entrada
---
Explicación para *_.login__input:not(:placeholder-shown).login__input:not(:focus) + .login__label_* :
---
Esta línea de CSS selecciona un elemento con la clase .login__label que es un hermano adyacente (siguiente elemento inmediato) de un elemento con la clase .login__input, que no tiene su marcador de posición (placeholder) visible y que no está enfocado (:not(:placeholder-shown).login__input:not(:focus)).

Para ser más específicos, esta línea selecciona el elemento .login__label que sigue inmediatamente a un elemento .login__input que tiene contenido escrito dentro de él (es decir, no muestra el marcador de posición) y no está enfocado.

En otras palabras, cuando se escribe texto en el campo de entrada y luego se elimina el foco, el elemento de la etiqueta correspondiente se mueve a la posición superior del campo de entrada. Esto es parte del efecto de animación que se muestra cuando se escribe en el campo de entrada en el formulario de inicio de sesión.

Ahora para las propieades:
---
Las propiedades que se aplican a la etiqueta .login__label cuando el selector .login__input:not(:placeholder-shown).login__input:not(:focus) + .login__label se cumple son las siguientes:

**top**: -12px;: Esta propiedad mueve la etiqueta .login__label hacia arriba 12 píxeles, de modo que se superponga en la parte superior del campo de entrada cuando hay contenido escrito en el campo. Esto es para dar la ilusión de que el texto de la etiqueta es el contenido del campo.

**font-size**: var(--small-font-size);: Esta propiedad cambia el tamaño de fuente de la etiqueta .login__label a var(--small-font-size). Presumiblemente, esta es una fuente más pequeña que la fuente normal de la etiqueta para que pueda caber en la parte superior del campo de entrada sin ser demasiado grande.

---
Explicación de la funcionalidad Javascript:
---
Este código es una función de JavaScript que agrega funcionalidad a un botón de ojo que se utiliza para mostrar u ocultar contraseñas en un formulario de inicio de sesión. La función se llama showHiddenPass y toma dos argumentos: el id del campo de contraseña y el id del botón de ojo.

El código hace lo siguiente:

Selecciona el campo de contraseña y el botón de ojo en la página HTML usando document.getElementById().
Agrega un "event listener" al botón de ojo que escucha el evento de clic.
Cuando se hace clic en el botón de ojo, la función anónima cambia el tipo de entrada del campo de contraseña de "password" a "text" y viceversa, para que la contraseña sea visible u oculta.
También cambia la clase CSS del botón de ojo para cambiar el ícono y mostrar visualmente si la contraseña está oculta o visible.
La función showHiddenPass permite que el usuario tenga control sobre si quiere o no mostrar su contraseña mientras la escribe.

---
Explicacion de media queris:
---
Este código es una regla CSS que se aplica solo en pantallas con un ancho mínimo de 576px, utilizando el media query @media screen and (min-width: 576px).

Cuando la pantalla cumple esta condición, se aplican las siguientes propiedades CSS a los elementos con las clases correspondientes:

La clase .login tiene su propiedad justify-content establecida en center, lo que centrará el contenido horizontalmente en su contenedor.

La clase .login__form tiene su propiedad width establecida en 432px, su padding establecido en 4rem 3rem 3.5rem y su border-radius establecido en 1.5rem. Esto le da un ancho específico, un relleno personalizado y bordes redondeados al elemento.

La clase .login__title tiene su propiedad font-size establecida en 2rem. Esto aumentará el tamaño de la fuente del título en el formulario de inicio de sesión.

En resumen, este código es una forma de personalizar la apariencia de un formulario de inicio de sesión en pantallas más grandes, para que tenga un ancho específico, bordes redondeados y se centre horizontalmente en la pantalla.# Login-Form-by-Bedimcode
# Login-Form-by-Bedimcode
