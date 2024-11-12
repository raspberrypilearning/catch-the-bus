## Y bws yn gadael

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Gelwir grŵp o flociau cysylltiedig yn Scratch yn **script**. Byddi di'n ychwanegu sgript newydd i wneud i'r bws yrru i ffwrdd.
</div>
<div>

![Y Llwyfan yn dangos bod y bws wedi symud i'r dde.](images/bus-leaving.png){:width="300px"}

</div>
</div>

### Animate the Bus

--- task ---

Select the **City Bus** sprite.

![The City Bus sprite.](images/bus-sprite.png)

--- /task ---

--- task ---

Add code to make the bus drive off to the right four seconds after the green flag is clicked.

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] // newid 10 i 4
```

--- /task ---

--- task ---

Drag your bus to the right-hand side of the Stage. This is the `x`{:class="block3motion"} and `y`{:class="block3motion"} position that the bus will `glide`{:class="block3motion"} to.

![](images/bus-right.png)

**Tip:** If you move the bus too far to the right, it will jump back. Try again, but don't move it so far.

--- /task ---

--- task ---

Add a `glide`{:class="block3motion"} `2` `secs to x: y:`{:class="block3motion"} block under the `wait`{:class="block3control"} block.

Ychwanega floc `llithro`{:class="block3motion"} am `2` `eiliad i x: y:`{:class="block3motion"} o dan y bloc `pan amserydd`{:class="block3events"}.

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
+glide [2] secs to x: [320] y: [-100] // ochr dde'r Llwyfan
```

--- /task ---

--- task ---

**Test:** Click on the green flag. The Scratch Cat and hippo will move to the bus, and the bus will drive off to the right after four seconds.

--- /task ---

### Hide and show the Bus

--- task ---

Add a `hide`{:class="block3looks"} block to make the bus seem to drive off the Stage:

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
glide [2] secs to x: [320] y: [-100]
+ hide
```
--- /task ---

--- task ---

**Test:** Click on the green flag. The bus will now hide after driving off. Do you remember how to make sure that a sprite reappears when you click on the green flag?

--- /task ---

--- task ---

Add a `show`{:class="block3looks"} block to your `when green flag clicked`{:class="block3events"} script to make the bus appear when you run your project:

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
set [color v] effect to (50) // rho gynnig ar rifau hyd at 200
+show
```

--- /task ---

--- task ---

**Test:** Click on the green flag and watch your animation. The bus should appear in the centre of the Stage and then drive off to the right and disappear.

Is everyone on the bus when it leaves? You can change the amount of time that the bus waits, if you need to.

--- /task ---
