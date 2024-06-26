## Perder el autobús

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
¿Qué pasa si el gato de Scratch no corre lo suficientemente rápido para tomar el autobús?
</div>
<div>

! [El gato de Scratch pierde el autobús.](Images/cat-misses-bus.png){:width="300px"}

</div>
</div>

### Haz que el Gato Scratch pierda el autobús

--- task ---

Selecciona el **Gato de Scratch** y agrega un bloque `esperar`{:class="block3control"}:

![El objeto gato de Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) 
show
repeat (20) // prueba diferentes números
move (5) steps 
next costume 
+ wait (1) seconds
end
hide
```
--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde. ¡El gato de Scratch caminará demasiado lento y perderá el autobús!

--- /task ---

### Haz que el Gato Scratch tome el Autobús

--- task ---

Vas a querer un tiempo de retraso de menos de un segundo. 0.5 es medio segundo, 0.25 es un cuarto de segundo y 0.1 es una décima de segundo.

Cambia el tiempo de retraso en el bloque `esperar`{:class="block3control"}:

![El objeto gato de Scratch.](images/scratch-cat-sprite.png)

```blocks3
wait (0.2) seconds // prueba 0.1, 0.5, 0.05
```

**Prueba:** Haz clic en la bandera verde y el gato Scratch caminará más rápido. Elige el tiempo de retraso que prefieras.

--- /task ---

### Elige si el Gato Scratch toma o pierde el autobús

--- task ---

Si quieres que el gato de Scratch **pierda el autobús**, quita el bloque `esconder`{:class="block3looks"} de tu código para que el gato de Scratch permanezca en el escenario:

![Arrastra el bloque 'esconder' del script en el área de Código al menú de Bloques para eliminar el bloque del script.](images/removing-blocks-at-script-ends.gif)

![El objeto gato de Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) 
show
repeat (20) 
move (5) steps 
next costume
wait (0.5) seconds 
end
-hide
```
--- /task ---

--- task ---

Si quieres que el gato de Scratch **tome el autobús**, haz que el autobús espere más antes de partir:

![El objeto Autobús.](images/bus-sprite.png)

```blocks3
when flag clicked 
+wait [4] seconds // cambia de 4 a 6
glide [2] secs to x: [320] y: [-100] // lado derecho del Escenario
hide
```

Necesitarás volver a colocar el bloque `esconder`{:class="block3looks"} en el código del objeto **Gato de Scratch** si lo has eliminado y quieres que el gato de Scratch tome el autobús con éxito.

--- /task ---

--- task ---

Haz cambios hasta que la animación funcione como quieras.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Cuando trabajes en un proyecto, a menudo tendrás que retroceder y cambiar o mejorar tu código a medida que obtengas nuevas ideas. 
</p>



