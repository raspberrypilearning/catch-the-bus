## El autobus se va

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
En Scratch, un grupo de bloques conectados se llama **script**. Agregarás una nuevo script para hacer que el autobús se ponga en marcha.
</div>
<div>

! [El escenario mostrando que el autobús se ha movido hacia la derecha.](Images/bus-leave.png){:width="300px"}

</div>
</div>

El autobús se pondrá en marcha hacia la derecha cuatro segundos después de hacer clic en la bandera verde. El bloque `cuando cronómetro`{:class="block3events"} ejecutará los bloques que tenga debajo después de este tiempo de retraso.

--- task ---

Selecciona el objeto **City Bus** (Autobús).

![El objeto Autobús.](images/bus-sprite.png)

--- /task ---

--- task ---

Desde el menú `Eventos`{:class="block3events"}, arrastra un bloque `cuando volumen del sonido >`{:class="block3events"} `10` al área de Código. Cambia `volumen del sonido`{:class="block3events"} por `cronómetro`{:class="block3events"}. Esto iniciará un nuevo script:

![El objeto Autobús.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] // cambia de 10 a 4
```

--- /task ---

--- task ---

Arrastra tu autobús al lado derecho del escenario. Esta serán las coordenadas de `x`{:class="block3motion"} e `y`{:class="block3motion"} a la que el autobús se `desplazará`{:class="block3motion"}.

![](images/bus-right.png)

**Consejo:** Si mueves el autobús demasiado a la derecha, saltará hacia atrás. Vuelve a intentarlo, pero no lo muevas tan lejos.

--- /task ---

--- task ---

Agrega un bloque `desplazar en`{:class="block3motion"} `2` `segs a x: y:`{:class="block3motion"} debajo del bloque `cuando cronómetro`{:class="block3events"}.

Las coordenadas `x`{:class="block3motion"} e `y`{:class="block3motion"} en tu proyecto pueden ser un poco diferentes.

![El objeto Autobús.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
+glide [2] secs to x: [320] y: [-100] // lado derecho del Escenario
```

--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde. El gato de Scratch y el hipopótamo se moverán hacia el autobús, y el autobús se desplazará hacia la derecha después de cuatro segundos.

--- /task ---

--- task ---

Agrega un bloque `esconder`{:class="block3looks"} para que el autobús parezca salir del escenario:

![El objeto Autobús.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
glide [2] secs to x: [320] y: [-100]
+ hide
```
--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde. El autobús ahora se esconderá después de ponerse en marcha. ¿Recuerdas cómo asegurarte de que un objeto vuelva a aparecer cuando haces clic en la bandera verde?

--- /task ---

--- task ---

Agrega un bloque `mostrar`{:class="block3looks"} a tu script `al presionar bandera verde ⚑`{:class="block3events"} para que el bus aparezca cuando ejecutes tu proyecto:

![El objeto Autobús.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
set [color v] effect to (50) // prueba con un número hasta 200
+show
```

--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde y observa tu animación. El autobús debería aparecer en el centro del escenario y luego dirigirse hacia la derecha y desaparecer.

¿Están todos en el autobús cuando parte? Puede cambiar la cantidad de tiempo que espera el autobús, si lo necesitaras.

--- /task ---

--- save ---
