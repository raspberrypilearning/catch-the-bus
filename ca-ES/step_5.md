## L'autobús surt

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Afegeix més blocs per fer que l'autobús marxi.
</div>
<div>

![L'escenari ens mostra que l'autobús s'ha mogut cap a la dreta.](images/bus-leaving.png){:width="300px"}

</div>
</div>

### Anima l'autobús

--- task ---

Selecciona el personatge **City Bus** .

![El personatge del 'City Bus'.](images/bus-sprite.png)

--- /task ---

--- task ---

Afegeix un nou bloc de codi per fer que l'autobús marxi cap a la dreta quatre segons després de fer clic a la bandera verda.

![El personatge del 'City Bus'.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // change 1 to 4
```

--- /task ---

--- task ---

Arrossega l'autobús cap al costat dret de l'escenari. Aquesta és la posició `x`{:class="block3motion"} i `y`{:class="block3motion"} capa on `llisca`{:class="block3motion"} l'autobús.

![](images/bus-right.png)

**Consell:** Si mous l'autobús massa cap a la dreta, tornarà enrere. Torna-ho a provar, però no ho moguis tan lluny.

--- /task ---

--- task ---

Afegeix un `llisca`{:class="block3motion"} `2` `segons a x: y:`{:class="block3motion"} sota el bloc `espera`{:class="block3control"}.

Les coordenades `x`{:class="block3motion"} i `y`{:class="block3motion"} al vostre projecte poden ser una mica diferents i serà la posició exacta a la qual heu arrossegat l'autobús.

![El personatge del 'City Bus'.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // change 1 to 4
+glide [2] secs to x: [320] y: [-100] // right-hand side of the Stage
```

--- /task ---

--- task ---

**Prova:** Feu clic a la bandera verda. El gat Scratch i l'hipopòtam es mouran cap a l'autobús i l'autobús marxarà cap a la dreta al cap de quatre segons.

--- /task ---

### Amaga i mostra l'autobús

--- task ---

Afegeix un bloc `amaga't`{:class="block3looks"} perquè l'autobús sembli sortir de l'escenari:

![El personatge del 'City Bus'.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // change 1 to 4
glide [2] secs to x: [320] y: [-100]
+ hide
```
--- /task ---

--- task ---

**Prova:** Feu clic a la bandera verda. L'autobús es mourà i després s'amagarà. Recorda com assegurar-te que un personatge reapareix quan feu clic a la bandera verda?

--- /task ---

--- task ---

Afegeix un bloc `mostra't`{:class="block3looks"} a la teva llista d'accions `quan la bandera verda es cliqui`{:class="block3events"} per fer que el bus apareixen quan executeu el vostre projecte:

![El personatge del 'City Bus'.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
set [color v] effect to (85) // try numbers up to 200
+show
```

--- /task ---

--- task ---

**Prova:** Fes clic a la bandera verda i mira la teva animació. L'autobús hauria d'aparèixer al centre de l'escenari i després marxar cap a la dreta i desaparèixer.

Tothom està a l'autobús quan surt? Pots canviar la quantitat de temps que l'autobús espera, si és necessari.

--- /task ---
