## Methu'r bws

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Beth os nad oedd y Gath Scratch wedi rhedeg yn ddigon cyflym i ddal y bws?
</div>
<div>

![Y Gath Scratch yn methu'r bws.](images/cat-misses-bus.png){:width="300px"}

</div>
</div>

--- task ---

Dewisa gorlun y **Gath Scratch** ac ychwanegu bloc `aros`{:class="block3control"}:

![Corlun y Gath Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) 
show
repeat (20) // try different numbers
move (5) steps 
next costume 
+ wait (1) seconds
end
hide
```
--- /task ---

--- task ---

**Prawf:** Clicia ar y faner werdd. Bydd y Gath Scratch yn cerdded yn rhy araf ac yn methu'r bws!

--- /task ---

Bydd angen amser oedi o lai nag un eiliad. Mae 0.5 yn hanner eiliad, 0.25 yn chwarter eiliad, a 0.1 yn ddegfed ran o eiliad.

--- task ---

Newidia yr amser oedi yn y bloc `aros`{:class="block3control"}:

![Corlun y Gath Scratch.](images/scratch-cat-sprite.png)

```blocks3
wait (0.2) seconds // try 0.1, 0.5, 0.05
```

**Prawf:** Clicia ar y faner werdd, a bydd y Gath Scratch yn cerdded yn gyflymach. Dewisa'r amser oedi sydd well gen ti.

--- /task ---

**Dewis:** Dewisa os wyt ti am i'r Gath Scratch **fethu'r bws** neu **ddal y bws**.

--- task ---

Os wyt ti am i'r Gath Scratch **fethu'r bws**, tynna'r bloc `cuddio`{:class="block3looks"} o dy god fel bod y Gath Scratch yn aros ar y Llwyfan:

![Llusgo'r bloc 'cuddio' o'r sgript yn ardal y Cod i'r ddewislen Blocisu i dynnu'r bloc o'r sgript.](images/removing-blocks-at-script-ends.gif)

![Corlun y Gath Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) 
show
repeat (20) 
move (5) steps 
next costume
wait (0.5) seconds 
end
-hide
```
--- /task ---

--- task ---

Os wyt ti am i'r Gath Scratch **ddal y bws**, gwna i'r bws aros yn hirach cyn iddo adael:

![Corlun Bws y Ddinas.](images/bus-sprite.png)

```blocks3
+when [timer v] > [6] // change from 4 to 6
glide [2] secs to x: [320] y: [-100] // right-hand side of the Stage
hide
```

Bydd angen i ti roi'r bloc `cuddio`{:class="block3looks"} yn ôl yng nghod corlun y **Gath Scratch** os wyt ti wedi ei dynnu ac os wyt ti am i'r Gath Scratch ddal y bws.

--- /task ---

--- task ---

Gwna newidiadau nes i ti gael yr animeiddiad i weithio yn y ffordd rwyt ti am iddo wneud.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Wrth weithio ar brosiect, byddi di'n aml yn mynd yn ôl ac yn gwella dy god wrth gael syniadau newydd. 
</p>

--- save ---


