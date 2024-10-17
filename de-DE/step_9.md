## Verbessere Dein Projekt

Jetzt kannst du eine Figur deiner Wahl zu deiner Animation hinzufügen. Du musst dafür Code hinzufügen, damit deine Figur mit dem Block `gehe zu`{:class="block3motion"} zu einer Startposition geht und mit `setze Richtung auf`{:class="block3motion"} in die richtige Richtung zeigt. Dann kann die neue Figur mit Hilfe der Blöcke `wiederhole`{:class="block3control"}, `gehe`{:class="block3motion"}, und `wechsle zum nächsten Kostüm`{:class="block3looks"} den Bus erreichen.

**Tipp:** Wenn du auf **Figur auswählen**klickst, kannst du den Mauszeiger über eine Figur halten, um ihre Kostüme anzuzeigen. Auf manchen Mobilgeräten kannst du auch auf eine Figur tippen und gedrückt halten, um ihre Kostüme anzuzeigen (wenn ein Fenster erscheint, während du auf eine Figur tippst und gedrückt hälst, tippe auf die Seite des Bildschirms, um das Fenster zu schließen und die Kostüme anzuzeigen). Ein Blick auf die Kostüme der Figuren kann dir dabei helfen, eine Figur zu finden, die sich gut für eine Animation eignet.

![Andere Figuren bewegen sich auf einen Bus mit dem Text "Maker Festival" zu.](images/bus-upgrade.png){:width="300px"}

Du kannst alle Blöcke verwenden, die du in diesem Projekt kennengelernt hast, sowie diejenigen, die du bereits kennst:

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
title: Abgeschlossenes Projekt
---

Du findest das [abgeschlossene Projekt hier](https://scratch.mit.edu/projects/724160134/){:target="_blank"}.

--- /collapse ---

Du kannst das Projekt auch „Remixen“, um die gewünschten Änderungen vorzunehmen. Du könntest dem Bus oder anderen Figuren Soundeffekte hinzufügen oder den Farbeffekt des Busses einstellen. Eine der Figuren könnte den Bus verpassen und sich nicht verstecken.

Vielen Dank an die Digital Makerin Lyla, die uns dieses fantastischen Upgrade geschickt hat!

![Ein Projekt mit einem Bus mit blinkenden Farben.](images/Lyla-bus.gif)

--- save ---
