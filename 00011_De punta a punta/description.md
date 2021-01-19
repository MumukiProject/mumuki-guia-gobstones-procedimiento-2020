En el ejercicio anterior ya dibujamos una punta, ahora vamos a pensar cómo aprovechar lo que hicimos.

:warning: Podemos crear diferentes soluciones que resuelvan un mismo problema, por eso el procedimiento `DibujarPuntaNegra` que está en Biblioteca puede variar en algún detalle respecto al que creaste. Te recomendamos mirar bien su funcionamiento y aprovecharlo para crear un tablero como este:

<gs-board>
 GBB/1.0
  size 4 4
  cell 2 3 Negro 1 
  cell 0 0 Negro 1 
  cell 2 2 Negro 1 
  cell 3 2 Negro 1 
  cell 0 1 Negro 1 
  cell 1 0 Negro 1 
  head 0 0
</gs-board>

> Definí el procedimiento `DibujarDosPuntas` e invocalo dentro un `program`. Acordate de utilizar `DibujarPuntaNegra`.