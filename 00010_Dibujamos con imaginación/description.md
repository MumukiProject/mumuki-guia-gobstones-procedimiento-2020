Vamos a usar un poco la imaginación y vamos a hacer un procedimiento que dibuje una "punta" negra en la esquina inferior izquierda de esta forma:

<gs-board>
 GBB/1.0
  size 3 3
  cell 0 0 Negro 1
  cell 0 1 Negro 1
  cell 1 0 Negro 1
  head 1 0 
</gs-board>

> Definí el procedimiento `DibujarPuntaNegra` e invocalo dentro de un `program`. El cabezal comienza en el origen y debe terminar en el extremo inferior derecho de la punta.