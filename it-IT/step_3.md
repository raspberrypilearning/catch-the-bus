## Il Gatto Scratch prende l'autobus

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Anima lo Scratch Cat in modo che appaia sul **lato destro** dello Stage e cammini verso l'autobus ripetendo un piccolo movimento molte volte in un **ciclo**. 
</div>
<div>

![Lo Scratch Cat che cammina verso l'autobus.](images/cat-catches-bus.png){:width="300px"}

</div>
</div>

### Porta il Gatto Scratch nella posizione di partenza

--- task ---

Fai clic sulla proprietà **Direzione** nel pannello degli Sprite. Ruota la freccia in modo che punti su `-90`. Poi, fai clic sull'icona **Sinistra/Destra** al centro per modificare lo stile di rotazione in `Sinistra-Destra`, per impedire al Gatto Scratch di girarsi sottosopra:

![La freccia che punta a -90 e l'icona "Sinistra/Destra" selezionata.](images/sprite-pane-direction.png)

--- /task ---

--- task ---

Trascina lo sprite Scratch Cat nella parte in basso a destra dello Stage.

![Lo Stage con il gatto posizionato nell'angolo in basso a destra.](images/bottom-right-cat.png)

**Suggerimento:** Se provi a posizionare uno sprite fuori dallo Stage, tornerà alla sua ultima posizione sullo Stage.

--- /task ---

--- task ---

Aggiungi il codice per portare il Gatto Scratch alla sua posizione iniziale:

![Lo sprite di Scratch Cat.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // in basso a destra
```

--- /task ---

--- task ---

**Prova:** Trascina il Gatto Scratch in una nuova posizione, poi fai clic sul blocco `vai a x: y:`{:class="block3motion"}. Il Gatto Scratch dovrebbe tornare ogni volta nel punto in basso a destra.

--- /task ---

### Anima il Gatto Scratch

Aggiungerai il codice in un ciclo `ripeti`{:class="block3control"} per fare in modo che lo Scratch Cat ripeta pochi passi molte volte. Questo darà al Gatto Scratch un'apparente animazione.

--- task ---

Aggiungi un blocco `ripeti`{:class="block3control"} `10` `volte`{:class="block3control"}, quindi trascina un blocco `fai`{:class="block3motion"} `10` `passi`{:class="block3motion"} al suo interno:

![Modifica del numero di passaggi nel blocco 'fai passi' da 10 a 5, quindi inserimento del blocco nel ciclo 'ripeti'.](images/block-into-loop.gif)

![Lo sprite di Scratch Cat.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // in basso a destra
+ repeat (10) // prova numeri diversi
move (5) steps //  5 è una buona velocità di camminata
end
```

--- /task ---

--- task ---

**Prova:** Clicca sulla bandierina verde. Prova a cambiare i numeri nel blocco `ripeti`{:class="block3control"} `10` `volte`{:class="block3control"} in modo che il Gatto Scratch si fermi all'autobus.

--- /task ---

Alcuni sprite hanno più di un costume. Utilizzerai i costumi dello sprite **Scratch Cat** per creare una camminata.

--- task ---

Fai clic sulla scheda **Costumi**. Lo sprite **Scratch Cat** ha due costumi e insieme possono essere usati per creare un specie di camminata.

--- /task ---

--- task ---

Fai clic sulla scheda **Codice**. Aggiungi un blocco `passa al costume seguente`{:class="block3looks"}:

![Lo sprite di Scratch Cat.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // in basso a destra
repeat (20) // prova numeri diversi
move (5) steps // 5 è una buona velocità di camminata
+ next costume 
end
```
--- /task ---

--- task ---

**Prova:** Clicca sulla bandierina verde e il Gatto Scratch camminerà verso l'autobus.

--- /task ---

### Nascondi il Gatto Scratch

--- task ---

Aggiungi un blocco `nascondi`{:class="block3looks"} allo Scratch Cat quando raggiunge l'autobus:

![Lo sprite di Scratch Cat.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // in basso a destra
repeat (20) // prova numeri diversi
move (5) steps // 5 è una buona velocità di camminata
next costume 
end
+ hide
```

--- /task ---

--- task ---

**Prova:** Clicca nuovamente sulla bandierina verde e vedrai che Scratch Cat ora è scomparso.

--- /task ---

### Mostra il Gatto Scratch

--- task ---

Aggiungi un blocco `mostra`{:class="block3looks"} in modo che il Gatto Scratch appaia prima di camminare verso l'autobus:

![Lo sprite di Scratch Cat.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // in basso a destra
+ show
repeat (20) // prova numeri diversi
move (5) steps // 5 è una buona velocità di camminata
next costume 
end
hide
```

**Suggerimento:** Quando usi un blocco `nascondi`{:class="block3looks"}, devi aggiungere anche un blocco `mostra`{:class="block3looks"} per assicurarti che uno sprite torni visibile all'inizio.

--- /task ---

--- task ---

**Prova:** Clicca sulla bandierina verde per provare il tuo progetto e assicurati che il Gatto Scratch appaia.

--- /task ---

