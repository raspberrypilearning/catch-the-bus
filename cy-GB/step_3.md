## Y Gath Scratch yn dal y bws

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Byddi di'n animeiddio'r Gath Scratch i ymddangos ar **ochr dde** y Llwyfan a cherdded i'r bws trwy ailadrodd symudiad bach sawl gwaith mewn **dolen**. 
</div>
<div>

![Y Gath Scratch yn cerdded i'r bws.](images/cat-catches-bus.png){:width="300px"}

</div>
</div>

### Rhoi'r Gath Scratch yn ei safle dechreuol

--- task ---

Clicia'r briodwedd **Cyfeiriad** yn y cwarel Corluniau. Tro'r saeth i bwyntio i `-90`. Wedyn, clicia'r eicon **Chwith/Dde** yn y canol i newid yr arddull cylchdroi i `chwith-dde` er mwyn atal y Gath Scratch rhag troi wyneb i waered:

![Y saeth yn pwyntio at -90 a'r eicon 'Chwith/Dde' wedi'i ddewis.](images/sprite-pane-direction.png)

--- /task ---


--- task ---

Llusga'r Gath Scratch i ochr dde y Llwyfan.

**Awgrym:** Os wyt ti'n trio gosod corlun oddi ar y Llwyfan, bydd yn symud yn ôl i'w safle olaf ar y Llwyfan.

--- /task ---

--- task ---

Ychwanega god i roi'r Gath Scratch yn ei safle dechreuol:

![Corlun y Gath Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
```

--- /task ---

--- task ---

**Prawf:** Llusga'r Gath Scratch i safle newydd, yna clicia dy floc `mynd i x: y:`{: class = "block3motion"}. Dylai'r Gath Scratch symud yn ôl i'r ochr dde isaf bob tro.

--- /task ---

### Animeiddio'r Gath Scratch

Byddi di'n ychwanegu cod mewn bloc `ailadrodd`{: class = "block3control"} i wneud i'r Gath Scratch ailadrodd nifer fach o gamau lawer gwaith. Bydd hyn yn gwneud i'r Gath Scratch ymddangos yn animeiddiedig.

--- task ---

Ychwanega floc `ailadrodd`{: class = "block3control"} `10`, wedyn llusgo bloc `symud`{: class = "block3motion"} `10` `cam`{: class = "block3motion"} y tu mewn iddo:

![Newidia nifer y camau yn y bloc 'symud' o 10 i 5, wedyn mewnosod y bloc yn y ddolen 'ailadrodd'.](images/block-into-loop.gif)

![Corlun y Gath Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
+ repeat (10) // try different numbers
move (5) steps //  5 is a good walking speed
end
```

--- /task ---

--- task ---

**Prawf:** Clicia ar y faner werdd. Rho gynnig ar newid y rhifau fel bod y Gath Scratch yn stopio wrth y bws.

--- /task ---

Mae gan rai corluniaid fwy nag un wisg. Byddi di'n defnyddio corlun y **Gath Scratch** i greu animeiddiad o'r Gath Scratch yn cerdded.

--- task ---

Clicia'r tab **Gwisgoedd**. Mae gan y **Gath Scratch** ddwy wisg, a gyda'i gilydd, gellir eu defnyddio i wneud symudiad cerdded.

--- /task ---

--- task ---

Clicia'r tab **Cod**. Ychwanega floc `gwisg nesaf`{:class="block3looks"}:

![Corlun y Gath Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
repeat (20) // try different numbers
move (5) steps //  5 is a good walking speed
+ next costume 
end
```
--- /task ---

--- task ---

**Prawf:** Clicia ar y faner werdd, a bydd y Gath Scratch yn cerdded i'r bws.

--- /task ---

Nawr, byddi di'n gwneud i'r Gath Scratch ymddangos fel petai'n mynd i mewn i'r bws.

--- task ---

Ychwanega floc i `guddio`{:class="block3looks"} y Gath Scratch pan fydd hi'n cyrraedd y bws:

![Corlun y Gath Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
repeat (20) // try different numbers
move (5) steps //  5 is a good walking speed
next costume 
end
+ hide
```

--- /task ---

--- task ---

**Prawf:** Clicia ar y faner werdd eto, ac fe weli di fod y Gath Scratch bellach wedi diflannu.

--- /task ---

Mae angen i'r Gath Scratch ailymddangos pan fyddi di'n rhedeg yr animeiddiad eto.

--- task ---

Ychwanega bloc `dangos`{:class="block3looks"} fel bod y Gath Scratch yn ymddangos cyn cerdded i'r gws:

![Corlun y Gath Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
+ show
repeat (20) // try different numbers
move (5) steps //  5 is a good walking speed
next costume 
end
hide
```

**Awgrym:** Pan fyddi di'n defnyddio bloc `cuddio`{:class="block3looks"}, bydd angen i ti ychwanegu bloc `dangos`{:class="block3looks"} i wneud yn siŵr bod corlun yn weladwy pan fydd angen.

--- /task ---

--- task ---

**Prawf:** Clicia ar y faner werdd i brofi dy brosiect, a gwneud yn siŵr bod y Gath Scratch yn ymddangos.

--- /task ---

--- save ---
