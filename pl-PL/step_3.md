## Kot Scratch łapie autobus

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Będziesz animować kota Scratch, aby pojawił się po **prawej stronie** sceny i podszedł do autobusu, powtarzając kilka razy mały ruch w **pętli**. 
</div>
<div>

![Kot Scratch idący do autobusu.](images/cat-catches-bus.png){:width="300px"}

</div>
</div>

### Ustaw kota Scratch w pozycji wyjściowej

--- task ---

Kliknij właściwość **Kierunek** w panelu duszka. Obróć strzałkę, aby wskazać `-90`. Następnie kliknij ikonę **Lewo/Prawo** pośrodku, aby zmienić styl obracania na `lewy- prawy` aby zatrzymać odwracanie się do góry nogami kota Scratch:

![Strzałka wskazująca na -90 i wybrana jest ikona „Lewo/Prawo”.](images/sprite-pane-direction.png)

--- /task ---


--- task ---

Przeciągnij kota Scratch do prawej dolnej części sceny.

**Wskazówka:** Jeśli spróbujesz umieścić duszka poza sceną, wróci on do swojej ostatniej pozycji na scenie.

--- /task ---

--- task ---

Dodaj kod aby ustawić kota Scratch w pozycji wyjściowej:

![Duszek kota Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // dolna prawa część
```

--- /task ---

--- task ---

**Test:** Przeciągnij kota Scratch do nowej pozycji, a następnie kliknij `przejdź do bloku x: y:`{:class="block3motion"}. Kot Scratch powinien za każdym razem cofać się do prawego dolnego rogu.

--- /task ---

### Animuj kota Scratch

Dodasz kod w pętli `powtórzeń`{:class="block3control"}, aby kot Scratch powtórzył małą liczbę kroków wiele razy. Spowoduje to, że kot Scratch będzie wyglądał na animowanego.

--- task ---

Dodaj blok `powtórz`{:class="block3control"} `10`, a następnie przeciągnij `przesuń`{:class="block3motion"} `10` `kroków`{:class="block3motion"} do środka:

![Zmiana liczby kroków w bloku 'przenieś' z 10 na 5, a następnie wstawienie bloku do pętli 'powtórz'.](images/block-into-loop.gif)

![Duszek kota Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // dolna prawa część
+ repeat (10) // wypróbuj różne liczby
move (5) steps //  5 to dobra prędkość chodzenia
end
```

--- /task ---

--- task ---

**Test:** Kliknij zieloną flagę. Spróbuj zmienić numery, aby kot Scratch zatrzymał się przy autobusie.

--- /task ---

Niektóre duszki mają więcej niż jeden kostium. Użyjesz kostiumy **kota Scratch**, aby stworzyć animację poruszającego się kota Scratch.

--- task ---

Naciśnij na zakładkę **Kostiumy**. Duszek kota **Scratch** ma dwa kostiumy i razem mogą być użyte do wykonania efektu poruszania się.

--- /task ---

--- task ---

Kliknij na zakładkę **Kod**. Dodaj blok `następny kostium`{:class="block3motion"}:

![Duszek kota Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // dolna prawa część
repeat (20) // wypróbuj różne liczby
move (5) steps //  5 to dobra prędkość chodzenia
+ next costume 
end
```
--- /task ---

--- task ---

**Test:** Kliknij zieloną flagę, a kot Scratch pójdzie do autobusu.

--- /task ---

Teraz sprawisz, że kot Scratch będzie wydawał się wchodzić do autobusu.

--- task ---

Dodaj blok do `ukryj`{:class="block3looks"} kot Scratch, gdy dotrze do autobusu:

![Duszek kota Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // dolna prawa część
repeat (20) // wypróbuj różne liczby
move (5) steps //  5 to dobra prędkość chodzenia
next costume 
end
+ hide
```

--- /task ---

--- task ---

**Test:** Kliknij ponownie zieloną flagę, a zobaczysz, że kot Scratch zniknął.

--- /task ---

Kot Scratch musi pojawić się ponownie, gdy ponownie uruchomisz animację.

--- task ---

Dodaj blok `pokaż`{:class="block3looks"}, aby kot Scratch pojawił się, zanim podejdzie do autobusu:

![Duszek kota Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // dolna prawa część
+ show
repeat (20) // wypróbuj różne liczby
move (5) steps //  5 to dobra prędkość chodzenia
next costume 
end
hide
```

**Wskazówka:** Kiedy używasz `ukryj`{:class="block3looks"}, musisz również dodać blok `pokaż`{:class="block3looks"}, aby upewnić się, że duszek jest widoczny, gdy powinien być.

--- /task ---

--- task ---

**Test:** Kliknij zieloną flagę, aby przetestować swój projekt i upewnij się, że kot Scratch pojawia się.

--- /task ---

--- save ---
