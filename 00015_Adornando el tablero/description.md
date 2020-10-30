Uno de los objetivos de los procedimientos es reconocer las _subtareas_ que conforman un problema y combinar sus soluciones para poder resolverlo.:wrench: 
Veamos un ejemplo:
Tenemos que decorar el tablero con guirnaldas en sus dos esquinas superiores como muestra la imagen.

<gs-board>
 GBB/1.0
  size 4 3
  cell 0 2 Verde 3 Rojo 3
  cell 3 2 Verde 3 Rojo 3
  head 0 0 
</gs-board>

Cada guirnalda se compone de 3 bolitas rojas y 3 bolitas verdes. Ya resolvimos cómo poner 3 bolitas de esos colores en otros ejercicios :gift:, hacer una guirnalda requerirá combinar esas soluciones. 

Luego, para definir un procedimiento que decore el tablero, solo nos restaría utilizar el que crea una guirnalda las veces que sea necesario y combinarlo con la primitiva para ubicarnos en los bordes.

> Definí dos procedimientos: el procedimiento `PonerGuirnalda` que coloque 3 bolitas rojas y 3 bolitas verdes en una celda y el procedimiento `DecorarTablero` que  lo utilice y ponga una guirnalda en cada esquina superior.
Invocá `DecorarTablero` en el `program`.
