## Hipcio leci do autobusu

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Dodasz duszka hipopotama, który leci do autobusu.
</div>
<div>

![Hipopotam leci do autobusu.](images/hippo-flies.png){:width="300px"}

</div>
</div>

### Daj Hipciowi pozycję startową

--- task ---

Dodaj duszka ** Hippo1** do swojego projektu.

Zmień **Rozmiar** duszka **Hippo1**:

![Panel duszka dla duszka Hippo1 z rozmiarem ustawionym na 50.](images/hippo-sprite-size.png)

--- /task ---

--- task ---

Przeciągnij Hipcia do lewej górnej części sceny.

![Duszek Hippo1 w lewym górnym rogu sceny.](images/hippo-sprite-stage.png)

--- /task ---

--- task ---

Dodaj kod, aby ustawić Hipcia w pozycji startowej:

```blocks3
when flag clicked
go to x: [-200] y: [150] // top left-hand side
```

**Wskazówka:** Współrzędne `x`{:class="block3motion"} i `y`{:class="block3motion"} w bloku `idź do x: y:`{:class="block3motion"} będą wskazywały aktualną pozycję hipopotama, więc nie musisz ich wpisywać.

--- /task ---

### Spraw, aby Hipcio trzepotał skrzydłami i latał

--- task ---

Dodaj kod, aby hipopotam leciał w kierunku duszka **City Bus**:

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+repeat [100] 
point towards (City Bus v) // change from mouse-pointer
move [3] steps
next costume
+end
```

--- /task ---

--- task ---

**Test:** Kliknij zieloną flagę i sprawdź, czy hipopotam leci do autobusu. Możesz zmienić liczbę w pętli `powtórz`{:class="block3control"}, aby hipopotam zatrzymał się we właściwym miejscu.

--- /task ---

### Pokaż i ukryj Hipcia

--- task ---

Dodaj bloki `pokaż`{:class="block3looks"} i `ukryj`{:class="block3looks"}:

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+ show
repeat [90] 
point towards (City Bus v)
move [3] steps
next costume
end
+ hide
```

--- /task ---

--- task ---

**Test:** Kliknij zieloną flagę. Hipopotam powinien polecieć do autobusu i wsiąść do niego.

--- /task ---
