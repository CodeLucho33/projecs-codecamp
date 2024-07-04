Paso 9
Ahora añadirás algunos elementos, a los que darás forma de marcadores o plumones en los siguientes pasos.

Primero, dentro del elemento body, añade un elemento div ya su atributo class dale el valor container. Asegúrate que el elemento div esté debajo del elemento h1.

Paso 12
Se aplicó el color de fondo, pero dado que el elemento div del marcador está vacío, no tiene ninguna altura por defecto.
En la regla CSS .marker, establezca la propiedad height en 25px y la propiedad width en 200px

Paso 13
Para centrar tu marcador en la página, dale el valor auto a la propiedad margin. Esto les da el valor auto a margin-top, margin-right, margin-bottom y margin-left.

Paso 14
Ya que tienes un marcador centrado y con color, es hora de añadir los otros marcadores.

En él div con la clase container, añade otros dos elementos div y dales una clase con el valor marker a cada uno.

Paso 15
Ahora tienes tres marcadores div, pero parecen un solo rectángulo grande. Deberías añadir un poco de espacio entre ellos, para que sea más fácil diferenciar cada elemento.

Cuando la propiedad margin tiene dos valores, el primer valor corresponde a margin-top y margin-bottom y el segundo valor corresponde a margin-left y margin-right.

En tu regla CSS .marker dale a la propiedad margin el valor 10px auto.

Paso 16
Para dar a los marcadores diferentes colores, necesitará añadir una clase única a cada uno. Múltiples clases pueden ser añadidas a un elemento listándolas en el atributo class y separándolas con un espacio. Por ejemplo, lo siguiente añade las clases animal y dog a un elemento div.

Example Code
div class="animal dog"

Editor
styles.cssEditor
5
Diseño Web Responsivo
Aprenda los colores de CSS construyendo un conjunto de marcadores de colores

Paso 21
Hay dos modelos principales de colores: el modelo aditivo RGB (rojo, verde, azul) utilizado en dispositivos electrónicos, y el modelo sustractivo CMYK (cian, magenta, amarillo, negro) utilizado para impresión.

En este proyecto, trabajarás con el modelo RGB. Esto significa que los colores comienzan como negros y cambian a medida que se introducen diferentes niveles de rojo, verde y azul. Una forma fácil de ver esto, es con la función CSS rgb.