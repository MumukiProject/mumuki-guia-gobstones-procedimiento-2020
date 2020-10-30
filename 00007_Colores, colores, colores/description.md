Vamos a darle un poco más de color a todo esto haciendo líneas multicolores como esta:

<gs-board>
 GBB/1.0
  size 5 2
  cell 0 1 Azul 1 Rojo 1 Verde 1 Negro 1
  cell 1 1 Azul 1 Rojo 1 Verde 1 Negro 1
  cell 2 1 Azul 1 Rojo 1 Verde 1 Negro 1
  cell 3 1 Azul 1 Rojo 1 Verde 1 Negro 1
  head 0 1 
</gs-board>

Como se ve en la imagen, cada celda de la línea debe tener una bolita de cada color (una roja, una negra, una verde y una azul). 

_¿Cómo podemos dibujarla? ¿Cuál es la tarea que se repite? ¿Se puede definir un nuevo procedimiento para resolverla y aprovecharlo para construir nuestra solución?_

> Definí un procedimiento `DibujarLineaColorida` que **dibuje una línea multicolor** de cuatro celdas hacia el `Este` y al finalizarla ubique el cabezal en la celda inicial. Invocá el nuevo procedimiento en un `program`.