Ya vimos que los comandos que vienen definidos por el lenguaje se llaman **primitivas**. Hay una primitiva que no usaste hasta ahora que queremos presentarte.

Imaginate que no sabés ni dónde está el cabezal ni qué tamaño tiene el tablero pero querés llegar a una esquina: La primitiva Mover no te va a ser de mucha ayuda. :scream:

Por suerte :four_leaf_clover: existe una primitiva :gift: llamada `IrAlBorde`, que toma una dirección, y se mueve todo lo que pueda en esa dirección, **hasta llegar al borde**.

¿Cómo? Mirá el ejemplo:

<gs-board>   
  GBB/1.0
  size 4 5
  head 0 0
<gs-board>

``` gobstones
program {
	IrAlBorde(Este)
}
```

Luego de ejecutar el programa, el resultado será:
<gs-board>   
  GBB/1.0
  size 4 5
  head 3 0
<gs-board>

> Definí el procedimiento `RojoAlBorde` que ponga una bolita roja en la esquina superior izquierda del tablero e invocalo en el `program`.