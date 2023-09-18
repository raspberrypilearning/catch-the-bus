## Ulepsz swój projekt

Teraz możesz dodać wybranego duszka do swojej animacji. Twój nowy duszek będzie musiał `przejść do`{:class="block3motion"} pozycji startowej, `ustawić się`{:class="block3motion"} we właściwym kierunku, a następnie `powtórzyć`{:class ="block3control"} polecenia: `przesuń o`{:class="block3motion"} i `następny kostium`{:class="block3looks"}, dzięki czemu dotrze do autobusu.

**Wskazówka:** Kiedy przeglądasz bibliotekę duszków po wcześniejszym kliknięciu ikony **Wybierz Duszka**, możesz przytrzymać kursor myszy nad duszkiem, aby zobaczyć jego kostiumy, lub na niektórych urządzeniach mobilnych możesz dotknąć i przytrzymać duszka, aby zobaczyć jego kostiumy (jeśli okno wyskakuje Ci po dotknięciu i przytrzymaniu duszka, dotknij boku ekranu, aby je zamknąć i zobaczyć kostiumy). Przeglądanie kostiumów duszków może pomóc Ci znaleźć duszka, który dobrze sprawdzi się w animacji.

![Inne duszki zmierzają w stronę autobusu z napisem "Festyn Twórców".](images/bus-upgrade.png){:width="300px"}

Możesz użyć dowolnych bloków, z których korzystaliśmy w tym projekcie, jak również tych, które już znasz:

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
title: Ukończony projekt
---

Tutaj możesz zobaczyć [ukończony projekt](https://scratch.mit.edu/projects/724160134/){:target="_blank"}.

--- /collapse ---

Możesz także „zremiksować” projekt, aby wprowadzić dowolne zmiany. Możesz dodać efekty dźwiękowe do autobusu lub innych duszków albo zmienić kolor autobusu poprzez zmianę efektu kolor. Możesz również sprawić, aby jeden z duszków przegapił autobus i nie zniknął ze sceny.

Podziękowania dla cyfrowej twórczyni Lyli za wysłanie tej fantastycznej aktualizacji!

![Projekt z autobusem z migającymi kolorami.](images/Lyla-bus.gif)

--- save ---
