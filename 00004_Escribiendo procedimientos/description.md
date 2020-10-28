_Llegó el momento de programar desde cero. ¡No te preocupes! Como recién estamos empezando, repasemos lo que aprendimos._

A esta altura ya sabemos que para programar siempre tenemos que tener en cuenta la sintaxis. Para definir nuevos procedimientos también tenemos reglas: 
- empezamos con la palabra reservada `procedure`
- elegimos un nombre que lo describa y lo escribimos con mayúscula seguido de paréntesis `()` 
- encerramos las acciones que queremos que haga entre llaves `{}`

Entonces, un procedimiento que se mueve cuatro celdas al Norte se va a definir así:

``` gobstones
procedure Mover4AlNorte() {
	Mover(Norte)
	Mover(Norte)
	Mover(Norte)
	Mover(Norte)
}
```

Y si lo queremos utilizar, tenemos que invocarlo dentro del program escribiendo su nombre tal cual y sin olvidar los paréntesis ¡Prestá atención a la sintaxis!

``` gobstones
program {
	Mover4AlNorte()
}
```

¡Ahora te toca a vos! :grin:

> Definí un procedimiento `Poner3Verdes` que ponga 3 bolitas verdes en la celda actual e invocalo en el `program`.