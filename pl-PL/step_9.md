## Ulepsz swój projekt

Teraz możesz dodać wybranego duszka do swojej animacji. Będziesz musiał dodać kod, aby twój duszek `przeszedł do`{:class="block3motion"} pozycji startowej, `ustawił się`{:class="block3motion"} we właściwym kierunku, a następnie `powtórz`{:class="block3control"} `przesuń`{:class="block3motion"} i `następny kostium`{:class="block3looks"} aby dotrzeć do autobusu.

**Wskazówka:** Kiedy klikasz **Wybierz Duszka**, możesz przytrzymać kursor myszy nad duszkiem, aby zobaczyć jego kostiumy, lub na niektórych urządzeniach mobilnych możesz dotknąć i przytrzymać duszka, aby zobaczyć jego kostiumy (jeśli okno wyskakuje po dotknięciu i przytrzymaniu duszka, dotknij boku ekranu, aby zamknąć okno i zobaczyć kostiumy). Przeszukiwanie kostiumów duszków może pomóc ci znaleźć duszka, który dobrze sprawdza się w animacji.

![Inne duszki zmierzają w stronę autobusu z tekstem "Maker Festival".](images/bus-upgrade.png){:width="300px"}

Możesz użyć dowolnych bloków, których nauczyłeś się w tym projekcie, a także tych, które już znasz:

```blocks3
when flag clicked

when [timer v] > [5]

go to x: [0] y: [0] // przeciągnij duszka, aby wybrać x i y

show

hide

glide [2] secs to x: [0] y: [-100] // środek dolnej części sceny

repeat [30]
end

point towards (City Bus v)

point in direction (180) // wskazać dół

set rotation style [left-right v]

move [3] steps

next costume

start sound [clown honk v]

wait [0.1] seconds // krótkie opóźnienie

set [color v] effect to [50] // do 200
```

--- collapse ---
---
title: Ukończony projekt
---

Tutaj możesz zobaczyć [ukończony projekt](https://scratch.mit.edu/projects/602796029/){:target="_blank"}.

--- /collapse ---

Możesz także „zremiksować” projekt, aby wprowadzić dowolne zmiany. Możesz dodać efekty dźwiękowe do autobusu lub innych duszków lub ustawić efekt kolorystyczny autobusu. Jeden z duszków mógł przegapić autobus i nie schować się.

Podziękowania dla projektantki cyfrowej Lyli za wysłanie tej fantastycznej aktualizacji!

![Projekt z autobusem z migającymi kolorami.](images/Lyla-bus.gif)

--- save ---
