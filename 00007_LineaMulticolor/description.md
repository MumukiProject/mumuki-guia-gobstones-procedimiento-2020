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

Como se ve en la imagen, cada una de sus celdas debe tener una bolita de cada color (una roja, una negra, una verde y una azul). Además, **el cabezal debe quedar en la celda inicial**. 

Hay muchas formas de resolver este problema, pero si prestamos atención vamos a notar que la solución puede separarse en distintas partes o _subtareas_.:wrench: Y si reconocemos subtareas nos conviene agruparlas ¿Cuál es la tarea que se repite? ¿Se puede definir un nuevo procedimiento para resolverla y aprovecharlo para construir nuestra solución?

> Definí un procedimiento `LineaColorida` que dibuje una **línea multicolor** de cuatro celdas hacia el `Este` y ubique el cabezal en la celda inicial. Invocá el nuevo procedimiento en un `program`. 
¡No te olvides de definir y utilizar procedimientos para dividir tu problema en problemas más chicos!