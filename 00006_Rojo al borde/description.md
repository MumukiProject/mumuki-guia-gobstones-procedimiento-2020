Ya vimos que los comandos que vienen definidos por el lenguaje se llaman **primitivas**. Hay una primitiva que no usaste hasta ahora que queremos presentarte.

Imaginate que no sabés ni dónde está el cabezal ni qué tamaño tiene el tablero pero querés llegar a una esquina: La primitiva Mover no te va a ser de mucha ayuda. :scream:

Por suerte :four_leaf_clover: existe una primitiva :gift: llamada `IrAlBorde`, que toma una dirección, y se mueve todo lo que pueda en esa dirección, **hasta llegar al borde**.

¿Cómo? Mirá el resultado del siguiente programa:

``` gobstones
program {
	IrAlBorde(Este)
}
```

<table class= "table table-borderless" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>   
       GBB/1.0
       size 4 2
       head 1 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>   
        GBB/1.0
        size 4 2
        head 3 0
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

_¡Vamos a aprovecharlo!_

> Definí el procedimiento `RojoAlBorde` que ponga una bolita roja en la esquina superior izquierda del tablero e invocalo en el `program`.