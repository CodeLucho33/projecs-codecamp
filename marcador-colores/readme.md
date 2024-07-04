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

Paso 46
Es práctica muy común aplicar color a un elemento CSS con valores hexadecimales (hex). Puede sonar complicado, pero no es más que otra forma de expresar colores RGB.

Los valores hexadecimales empiezan con el carácter #, siguiendo seis caracteres entre 0-9 y A-F. El primer par de caracteres representa el rojo, el segundo el verde y el tercero el azul. Pr ejemplo, #4B5320.

Paso 47
Seguramente estés familiarizado con valores en base 10, o decimales, los cuales van de 0 a 9. Hexadecimales, o valores en base 16, van de 0 a 9 y a continuación de A a F:

Example Code
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F
Para los colores en hexadecimal, 00 es 0% de ese color, y FF es 100%. De tal manera que #00FF00 se traduce en 0% rojo, 100% verde y 0% azul, siendo equivalente a rgb(0, 255, 0).

Disminuye la intensidad del verde estableciendo el valor hexadecimal del color verde a 7F.



Paso 48
Otra forma de representar colores es el modelo HSL, siglas de hue, saturation y lightness (matiz, saturación y luminosidad).

La función de CSS hsl acepta tres valores: un número entre 0 y 360 para el matiz (hue), un porcentaje para la saturación (saturation), y un porcentaje para la luminosidad (lightness).

Sobre un círculo cromático, el matiz (hue) rojo está en 0 grados, el verde en 120 y el azul en 240.

La saturación (saturation) es la intensidad de un color desde 0%, o gris, hasta 100% para el color puro. Debes añadir el signo de porcentaje % a los valores de saturation (saturación) y lightness (luminosidad).

La luminosidad (lightness) es lo brillante que parece un color, desde 0% o completamente negro, hasta 100%, completamente blanco, siendo neutro el 50%.

En la regla CSS .blue, utiliza la función hsl para cambiar la propiedad background-color a azul puro. Establece el tono a 240, la saturación a 100% y la luminosidad a 50%.