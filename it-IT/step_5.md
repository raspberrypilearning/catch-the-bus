## L'autobus parte

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Aggiungi altri blocchi per far partire l'autobus.
</div>
<div>

![Lo stage mostra che l'autobus si è spostato a destra.](images/bus-leaving.png){:width="300px"}

</div>
</div>

### Anima l'autobus

--- task ---

Seleziona lo sprite **City Bus**.

![Lo sprite dell'autobus cittadino.](images/bus-sprite.png)

--- /task ---

--- task ---

Aggiungi il codice per far partire l'autobus verso destra quattro secondi dopo aver cliccato sulla bandierina verde.

![Lo sprite dell'autobus cittadino.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // cambia da 1 a 4
```

--- /task ---

--- task ---

Trascina il tuo autobus sul lato destro dello Stage. Questa è la posizione `x`{:class="block3motion"} e `y`{:class="block3motion"} verso la quale l'autobus `scivola`{:class="block3motion"}.

![](images/bus-right.png)

**Suggerimento:** Se sposti l'autobus troppo a destra, tornerà indietro. Riprova, ma non spostarlo così lontano.

--- /task ---

--- task ---

Aggiungi un blocco `scivola in`{:class="block3motion"} `2` `secondi a x: y:`{:class="block3motion"} sotto il blocco `attendi`{:class="block3control"}.

Le coordinate `x`{:class="block3motion"} e `y`{:class="block3motion"} nel tuo progetto potrebbero essere leggermente diverse e saranno la posizione esatta in cui hai trascinato il bus.

![Lo sprite dell'autobus cittadino.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // cambia da 1 a 4
+glide [2] secs to x: [320] y: [-100] // lato destro dello Stage
```

--- /task ---

--- task ---

**Prova:** Clicca sulla bandierina verde. Lo Scratch Cat e hippo si sposteranno verso l'autobus e l'autobus partirà a destra dopo quattro secondi.

--- /task ---

### Nascondi e mostra l'autobus

--- task ---

Aggiungi un blocco `nascondi`{:class="block3looks"} per far sembrare che l'autobus esca dallo Stage:

![Lo sprite dell'autobus cittadino.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // cambia da 1 a 4
glide [2] secs to x: [320] y: [-100]
+ hide
```
--- /task ---

--- task ---

**Prova:** Clicca sulla bandierina verde. L'autobus ora si nasconderà dopo essere partito. Ricordi come fare in modo che uno sprite ricompaia quando clicchi sulla bandierina verde?

--- /task ---

--- task ---

Aggiungi un blocco `mostra`{:class="block3looks"} dopo il blocco `quando si clicca sulla bandierina verde`{:class="block3events"} per far apparire il bus quando fai partire il tuo progetto:

![Lo sprite dell'autobus cittadino.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
set [color v] effect to (85) // prova dei numeri fino a 200
+show
```

--- /task ---

--- task ---

**Prova:** Clicca sulla bandierina verde e guarda la tua animazione. L'autobus dovrebbe apparire al centro dello stage, poi dirigersi a destra e scomparire.

Sono tutti sull'autobus quando parte? Se serve, puoi modificare il tempo di attesa dell'autobus.

--- /task ---
