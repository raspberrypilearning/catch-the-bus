## El gato de Scratch toma el autobús

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Animarás el gato de Scratch para que aparezca en el **lado derecho** del escenario y camine hacia el autobús repitiendo un pequeño movimiento muchas veces en un **bucle**. 
</div>
<div>

![El gato de Scratch caminando al autobús.](images/cat-catches-bus.png){:width="300px"}

</div>
</div>

### Coloca al Gato de Scratch en su posición inicial

--- task ---

Haz clic en **Dirección** en el panel de objetos. Gira la flecha hasta que apunte a `-90`. Luego, haz clic en el ícono que está al medio **Izquierda / Derecha** para cambiar el estilo de rotación a `izquierda-derecha` para evitar que el gato de Scratch se dé la vuelta:

![La flecha apuntando a -90 y el icono 'Izquierda / Derecha' seleccionado.](images/sprite-pane-direction.png)

--- /task ---

--- task ---

Arrastra al gato de Scratch a la parte inferior derecha del escenario.

![El Escenario con el gato ubicado en la esquina inferior derecha.](images/bottom-right-cat.png)

**Consejo:** Si pruebas colocar un objeto fuera del escenario, este volverá a su última posición en el escenario.

--- /task ---

--- task ---

Agrega código para llevar al gato de Scratch a su posición inicial:

![El objeto gato de Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
```

--- /task ---

--- task ---

**Prueba:** Arrastra al gato de Scratch a una nueva posición, luego haz clic en el bloque `ir a x: y:`{:class="block3motion"}. El gato Scratch debería volver a la parte inferior derecha cada vez.

--- /task ---

### Anima al gato de Scratch

Agregarás código en un bucle `repetir`{:class="block3control"} para hacer que el gato de Scratch repita una pequeña cantidad de pasos muchas veces. Esto hará que el gato de Scratch parezca estar animado.

--- task ---

Agrega un bloque `repetir`{:class="block3control"} `10`, luego arrastra un bloque `mover`{:class="block3motion"} `10` `pasos`{:class="block3motion"} dentro de él:

![Cambiando el número de pasos en el bloque 'mover' de 10 a 5, luego insertando el bloque en el bucle 'repetir'.](images/block-into-loop.gif)

![El objeto gato de Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
+ repeat (10) // try different numbers
move (5) steps //  5 is a good walking speed
end
```

--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde. Intenta cambiar los números hasta que el gato de Scratch se detenga en el autobús.

--- /task ---

Algunos objetos tienen más de un disfraz. Utilizarás el objeto **Gato de Scratch** para crear una animación del gato de Scratch caminando.

--- task ---

Haz clic en la pestaña **Disfraces**. El objeto **Gato de Scratch** tiene dos disfraces, que pueden usarse juntos para hacerlo caminar.

--- /task ---

--- task ---

Haz clic en la pestaña **Código**. Agrega un bloque `siguiente disfraz`{:class="block3looks"}:

![El objeto gato de Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
repeat (20) // try different numbers
move (5) steps //  5 is a good walking speed
+ next costume 
end
```
--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde y el gato de Scratch caminará hacia el autobús.

--- /task ---

### El gato de Scratch debe reaparecer cuando vuelvas a ejecutar la animación.

--- task ---

Agrega un bloque para `esconder`{: class = "block3looks"} al gato de Scratch cuando llegue al autobús:

![El objeto gato de Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
repeat (20) // try different numbers
move (5) steps //  5 is a good walking speed
next costume 
end
+ hide
```

--- /task ---

--- task ---

**Prueba:** Vuelve a hacer clic en la bandera verde y verás que el gato de Scratch ha desaparecido.

--- /task ---

### Ahora, harás que parezca que el gato de Scratch está entrando al autobús.

--- task ---

Agrega un bloque `mostrar`{:class="block3looks"} para que el gato de Scratch aparezca antes de empezar a caminar hacia el autobús:

![El objeto gato de Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
+ show
repeat (20) // try different numbers
move (5) steps //  5 is a good walking speed
next costume 
end
hide
```

**Consejo:** Cuando usas un bloque `esconder`{:class="block3looks"}, también necesitas agregar un bloque `mostrar`{:class="block3looks"} para asegurarte de que un objeto sea visible cuando lo necesites.

--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde para probar tu proyecto y asegúrate de que el gato de Scratch aparezca.

--- /task ---

