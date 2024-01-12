## Migliora il tuo progetto

Ora puoi aggiungere uno sprite a tua scelta alla tua animazione. Dovrai aggiungere il codice per far sì che il tuo sprite utilizzi `vai a`{:class="block3motion"} per raggiungere una posizione iniziale, `punta`{:class="block3motion"} nella giusta direzione, quindi `ripeta`{:class ="block3control"} `fai passi`{:class="block3motion"} e `passa al costume seguente`{:class="block3looks"} per raggiungere l'autobus.

**Suggerimento:** Quando fai clic su **Scegli uno Sprite**, puoi tenere il cursore del mouse su uno sprite per vedere i suoi costumi o, su alcuni dispositivi mobili, puoi toccare e tenere premuto su uno sprite per vedere i suoi costumi (se una finestra appare quando tocchi e tieni premuto su uno sprite, tocca sul lato dello schermo per chiudere la finestra e vedere i costumi). Guardare i costumi degli sprite ti può aiutare a trovare lo sprite che funziona meglio per l'animazione.

![Altri sprite che si muovono verso un autobus con il testo "Maker Festival".](images/bus-upgrade.png){:width="300px"}

Puoi utilizzare uno qualsiasi dei blocchi che hai imparato in questo progetto, oltre a quelli che già conosci:

```blocks3
when flag clicked

go to x: [0] y: [0] // drag the sprite to choose x and y

show

hide

glide [2] secs to x: [0] y: [-100] // bottom middle of the Stage

repeat [30]
end

point towards (City Bus v)

point in direction (180) // point down

set rotation style [left-right v]

move [3] steps

next costume

start sound [clown honk v]

wait [0.1] seconds // short delay

set [color v] effect to [50] // up to 200
```

--- collapse ---
---
title: Il progetto completo
---

Qui puoi visualizzare i [progetti completati](https://scratch.mit.edu/projects/724160134/){:target="_blank"}.

--- /collapse ---

Puoi anche fare 'remix' del progetto per fare le modifiche che vuoi. Potresti anche aggiungere suoni all'autobus o agli altri sprite, o cambiare i colori dell'autobus. Uno degli sprite potrebbe perdere l'autobus e non nascondersi.

Grazie al creatore digitale Lyla per aver inviato questo fantastico miglioramento!

![Un progetto con un autobus dai colori sgargianti.](images/Lyla-bus.gif)

--- save ---
