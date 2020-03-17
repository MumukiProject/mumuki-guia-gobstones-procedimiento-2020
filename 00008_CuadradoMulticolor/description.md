Vamos a crear un procedimiento que nos permita dibujar un tablero como este:

<gs-board>
     GBB/1.0
     size 5 5
     cell 0 0 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 1 0 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 2 0 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 3 0 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 0 1 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 1 1 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 2 1 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 3 1 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 0 2 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 1 2 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 2 2 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 3 2 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 0 3 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 1 3 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 2 3 Azul 1 Rojo 1 Verde 1 Negro 1
     cell 3 3 Azul 1 Rojo 1 Verde 1 Negro 1
     head 0 0
</gs-board>

> Definí un procedimiento `PonerCuadradoMulticolor4` que ponga un cuadrado de 4×4 celdas en el que cada celda tenga una bolita de cada color e invocalo en el `program`. El cabezal debe quedar en la celda inicial.