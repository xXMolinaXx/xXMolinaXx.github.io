## Transform
- La propiedad transform sirve para transformar un elemento HTML mediante funciones. Estas funciones permitirán trasladar, escalar, rotar o torcer a lo largo, ancho y profundidad del elemento.

TIPO | TRASLADRA | ESCALAR | INCLINAR | PERPECTIVA
 -- | -- | -- | -- | --|
 Multiple | translate() | scale() | rotate() | skew()| matrix()| perspective()
 Eje x| translateX() | scaleX() | rotateX() | skewX()| matrixX()| perspectiveX()
 Eje y| translateY() | scaleY() | rotateY() | skewY()| matrixY()| perspectiveY()
  Eje z| translateZ() | scaleZ() | rotateZ() | skewZ()| matrixZ()| perspectiveZ()
  3D | translate3d() | scale3d|rotate3d()
 ejemplo
 ```
 .class{
  
 }
 .class:hover{
transform translate(1px,2px)
 }
 ```
## Transition
- La propiedad transition sirve para agregar un intervalo de tiempo a un elemento HTML para visualizar los cambios de un punto inicial A, a un punto final B.

## Animation
- La propiedad animation sirve para cambiar estilos CSS a lo largo de un intervalo, consiste en reglas para un estado inicial, final e intermedios que conformarán una animación

- en public hay 3 pdf donde se ven todas las opciones de transition,trasnofrom y animation

# Transform style para transformaciones en 3D
- Por lo tanto, es momento para aplicar transformaciones en 3D. Las propiedades CSS para esto serán: transform-style y perspective.
- La propiedad transform-style de CSS establece si un elemento hijo está en el plano 2D (flat) o 3D (preserve-3d). Por defecto, el elemento está con valor flat.
- La propiedad perspective se utiliza para proveer de profundidad a un elemento con respecto al usuario y dar la sensación de 3D.

- El valor que recibe la propiedad es una longitud (px, rem, etc.) que representa la profundidad del plano para construir la perspectiva.

# PARALLAX
- tema de css donde sea crea profundidad y movimiento estudiar mas

# TIMING DEFAULT VALUES
Recapitulando, una timing function es la representación de la progresión en función del tiempo de cada ciclo de una animación. Representa la aceleración del elemento desde un punto A hasta un punto B.

- linear: El elemento se mueve a una aceleración constante.
- ease: Es el valor predeterminado si no se especifica. El elemento acelera inicialmente, pero presenta mucha desaceleración.
- ease-in: El elemento empieza lento pero termina rápido.
- ease-out: El elemento empieza rápido pero termina lento.
- ease-in-out: Es la combinación de ease-in y ease-out. El elemento empieza lento, a medida que avanza va acelerándose, pero termina lento.
- cubic-bezier: Se necesitan cuatro números, que representan dos puntos de control para formar la curva de aceleración deseada.