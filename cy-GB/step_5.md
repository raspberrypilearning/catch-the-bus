## Mae'r bws yn gadael

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Gelwir grŵp o flociau cysylltiedig yn Scratch yn **script**. Byddi di'n ychwanegu sgript newydd i wneud i'r bws yrru i ffwrdd.
</div>
<div>

![Y Llwyfan yn dangos bod y bws wedi symud i'r dde.](images/bus-leaving.png){:width="300px"}

</div>
</div>

Bydd y bws yn gyrru i ffwrdd i'r dde bedair eiliad ar ôl i'r faner werdd gael ei chlicio. Bydd y bloc `pan fydd yr amserydd`{:class="block3events"} yn rhedeg y blociau oddi tano ar ôl yr amser oedi hwn.

--- task ---

Dewisa'r corlun **City Bus**.

![Corlun Bws y Ddinas.](images/bus-sprite.png)

--- /task ---

--- task ---

Llusga bloc `pan cryfder sain >`{:class="block3events"} `10` i ardal y cod o'r ddewislen blociau `Digwyddiadau`{:class="block3events"}. Newidia `cryfder sain`{:class="block3events"} i `amserydd`{:class="block3events"}. Bydd hyn yn cychwyn sgript newydd:

![Corlun Bws y Ddinas.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] // newid 10 i 4
```

--- /task ---

--- task ---

Llusga dy fws i ochr dde y Llwyfan. Dyma fydd y safle `x`{:class="block3motion"} ac `y`{:class="block3motion"} y bydd y bws yn `llithro`{:class="block3motion"} iddo.

![](images/bus-right.png)

**Awgrym:** Os wyt ti'n symud y bws yn rhy bell i'r dde, bydd yn neidio yn ôl. Rho gynnig arall arni, ond paid â'i symud mor bell â hynny.

--- /task ---

--- task ---

Ychwanega floc `llithro`{:class="block3motion"} am `2` `eiliad i x: y:`{:class="block3motion"} o dan y bloc `pan amserydd`{:class="block3events"}.

Efallai fydd cyfuserynnau `x`{:class="block3motion"} a `y`{:class="block3motion"} dy brosiect di ychydig yn wahanol.

![Corlun Bws y Ddinas.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
+glide [2] secs to x: [320] y: [-100] // ochr dde'r Llwyfan
```

--- /task ---

--- task ---

**Prawf:** Clicia ar y faner werdd. Bydd y Gath Scratch a'r hipo yn symud i'r bws, a bydd y bws yn gyrru i ffwrdd i'r dde ar ôl pedair eiliad.

--- /task ---

--- task ---

Ychwanega floc `cuddio`{:class="block3looks"} i wneud i'r bws ymddangos fel petai'n gyrru oddi ar y Llwyfan:

![Corlun Bws y Ddinas.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
glide [2] secs to x: [320] y: [-100]
+ hide
```
--- /task ---

--- task ---

**Prawf:** Clicia ar y faner werdd. Bydd y bws nawr yn cuddio ar ôl gyrru i ffwrdd. Wyt ti'n cofio sut i wneud yn siŵr bod corlun yn ailymddangos pan fyddi di'n clicio ar y faner werdd?

--- /task ---

--- task ---

Ychwanega floc `dangos`{:class="block3looks"} at dy sgript `pan fydd y faner werdd wedi'i chlicio`{:class="block3events"} i wneud i'r bws ymddangos pan fyddi di'n rhedeg dy brosiect:

![Corlun Bws y Ddinas.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
set [color v] effect to (50) // rho gynnig ar rifau hyd at 200
+show
```

--- /task ---

--- task ---

**Prawf:** Clicia ar y faner werdd a gwylio dy animeiddiad. Dylai'r bws ymddangos yng nghanol y Llwyfan ac yna gyrru i ffwrdd i'r dde a diflannu.

Ydy pawb ar y bws pan mae'n gadael? Galli di newid faint o amser y mae'r bws yn aros, os bydd angen.

--- /task ---

--- save ---
