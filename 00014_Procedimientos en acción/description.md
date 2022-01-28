Si bien las palabras que utilizamos para crear programas (`program`) y definir procedimientos (`procedure`) se escriben parecido, son cosas muy distintas.

Cuando creamos un programa nuevo le estamos diciendo a la computadora:computer: lo que queremos que suceda luego de tocar :arrow_forward:**Enviar**.

Pero si queremos crear una tarea nueva podemos agrupar las acciones que requiere en un procedimiento. Los procedimientos se definen con un **nombre** que describa lo que hace.

Analicemos cómo definir un nuevo procedimiento llamado PonerVerdeYAzul. :eyes:

``` gobstones
procedure PonerVerdeYAzul() {
	Poner(Verde)
	Poner(Azul)
}
```

La computadora solo va a seguir las instrucciones dentro de un procedimiento cuando sea **invocado** dentro de un `program`. ¿Cómo lo invocamos? Escribimos su nombre seguido por paréntesis `()`.

``` gobstones
program {
	PonerVerdeYAzul()
}
```

> Completá el código para que además de **definir** el procedimiento `PonerNegroYRojo` luego lo **invoque** en el `program`.
