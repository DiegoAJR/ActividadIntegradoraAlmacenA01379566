Realizado por Diego Alejandro Juárez Ruiz A01379566
Fecha de entrega 23 de noviembre 2021

Actividad integradora:
En esta actividad se realiza un modelo 3D del almacén donde se tienen robots que organizan cajas en estantes. 
En este problema se tienen 5 robots que deberían poder organizar las cajas que encuentren en el piso. Estos agarran las cajas y las mueven hasta los estantes.

Puntos importantes

a) Modelos con materiales y texturas: 
Se realizó un mapa de almacén con paredes creadas con una textura obtenida de Google imágenes por “Aerogondo” recuperada de “deamstime” con cubos muy delgados. 
Igualmente se obtuvo el piso, estantes, robots y otros props por medio de la tienda de assets de Unity. Para estos últimos también podemos ver sus materiales y texturas.
Para las cajas se obtuvo una imagen recuperada de “artstation” por Ethan Seddon. Con esta textura se creó un material que se le puso a un cubo creado en probuilder, con mapeo UV se le pusieron las texturas. 
Como la textura es un cuadrado, este queda perfectamente en las caras de la caja. Los materiales y texturas modificadas se encuentran en la carpeta de “MaterialesyTexturas”

b) Iluminación:
La luz direccional se encuentra arriba del mapa con una intensidad de 1 y cada robot tiene, en su jerarquía, una luz puntual que se mueve con el robot. 
La luz puntual tiene una intensidad de 1. Esto hace que los puntos donde la luz toque al robot tengan un tono mucho más claro.

c) Animación
Para hacer que los robots se muevan se utilizó la técnica vista en clase para modelar el movimiento de las aves. 
Se utilizó el servidor web que genera las posiciones a las cuales el robot tiene que ir y se utiliza una técnica de interpolación para hacer que el robot se desplace con la fórmula 
de newPos = A + t * (B - A) siendo A el valor donde se empieza, B el punto al que queremos llegar y t el valor del tiempo que ha pasado. De esta forma obtenemos todos los puntos requeridos para llegar a ese punto B


El tamaño del mapa es de 22 x 13.45 pero los robots solo se pueden mover en el área de 19 x 11 para que ninguna parte del robot se salga del mapa.
De esta forma se completa la modelación del sistema. Se utilizan todos los temas que se vieron en clase y se ponen en práctica para la integración de un sistema de agentes.


Autores de Paquetes obtenidos de Unity Store Assets:

1.	Garage Props Pack: Abandoned World - Vladimir Seleznev -  https://www.artstation.com/s_grez
2.	Gist Level Designer: n-gist - https://n-gist.github.io/
3.	Robot JR-1 (animated) + mod1 & mod2: Jope Anti-Studio – John Jopeman - https://www.artstation.com/johnjopeman

Licencia incluida en el paquete de Unity*
