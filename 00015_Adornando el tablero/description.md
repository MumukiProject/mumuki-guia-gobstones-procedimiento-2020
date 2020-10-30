_Para resolver un problema nos conviene comprender bien de qué se trata para elegir una estrategia. Es el momento de empezar a hacerlo aprovechando los procedimientos._

Uno de los objetivos de los procedimientos es reconocer las _subtareas_ que conforman un problema y combinar sus soluciones para poder resolverlo.:wrench: 
Veamos un ejemplo:
Queremos decorar con guirnaldas las dos esquinas superiores de cualquier tablero, como muestra la imagen.

<gs-board>
 GBB/1.0
  size 4 3
  cell 0 2 Verde 3 Rojo 3
  cell 3 2 Verde 3 Rojo 3
  head 0 0 
</gs-board>

Pensemos una estrategia distinguiendo subtareas:

Cada guirnalda se compone de 3 bolitas rojas y 3 bolitas verdes. Ya resolvimos cómo hacerlo en otros ejercicios :gift:, hacer una guirnalda solo requerirá combinar esas soluciones. 

¿Y que más?:thinking: el procedimiento que decore el tablero debería poder combinar crear cada guirnalda con alguna primitiva que nos ayude a ubicarnos en los bordes.:wink:

¡Manos a la obra!

> Definí dos procedimientos: el procedimiento `PonerGuirnalda` que coloque 3 bolitas rojas y 3 bolitas verdes en una celda y el procedimiento `DecorarTablero` que  lo utilice y ponga una guirnalda en cada esquina superior.
Invocá `DecorarTablero` en el `program`.
