Como descubrimos en el ejemplo del cuadrado, se puede empezar a diferenciar dos tipos de comandos dentro de un programa:

- los que **vienen definidos por el lenguaje** y nos sirven para expresar operaciones básicas, como `Mover`, `Poner` y `Sacar`. A estos los llamaremos **comandos primitivos**, o simplemente **primitivas**;
- y los que **definimos nosotros**, que nos sirven para expresar tareas más complejas. Como el nombre de esta lección sugiere, estos son los **procedimientos**.

Cuando _definimos_ un procedimiento estamos "enseñándole" a la computadora :computer: a realizar una tarea nueva, que originalmente no estaba incluida en el lenguaje. 

:warning: Prestale atención a la sintaxis del ejemplo para distinguir bien cómo definimos un procedimiento y cómo lo _invocamos_ en un `program`. 

```gobstones
procedure Poner3Rojas() {
	Poner(Rojo)
	Poner(Rojo)
	Poner(Rojo)
}

program {
	Poner3Rojas()
}
```

> ¿Qué te parece que hace el nuevo procedimiento? :thinking: Copiá y enviá el código para saber qué pasa.