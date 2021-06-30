## The bus leaves

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
A group of connected blocks in Scratch is called a **script**. You will add a new script to make the bus drive off.
</div>
<div>
![The Stage showing that the bus has moved to the right.](images/bus-leaving.png){:width="300px"}
</div>
</div>

The bus will drive off to the right five seconds after the green flag is clicked. The `when timer`{:class="block3events"} block will run the blocks below it after this time delay.

--- task ---

Select the **City Bus** sprite.

![The City Bus sprite.](images/bus-sprite.png)

--- /task ---

--- task ---

From the `Events`{:class="block3events"} blocks menu, drag a `when loudness >`{:class="block3events"} `10` block to the Code area. Change `loudness`{:class="block3events"} to `timer`{:class="block3events"}. This will start a new script:

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] // change 10 to 4
```

--- /task ---

--- task ---

Drag your bus to the right-hand side of the Stage. This will be the `x`{:class="block3motion"} and `y`{:class="block3motion"} position that the bus will `glide`{:class="block3motion"} to.

![](images/bus-right.png)

**Tip:** If you move the bus too far to the right, it will jump back. Try again, but don't move it so far.

--- /task ---

--- task ---
Add a `glide`{:class="block3motion"} `2` `secs to x: y:`{:class="block3motion"} block under the `when timer`{:class="block3events"} block. 

The `x`{:class="block3motion"} and `y`{:class="block3motion"} coordinates in your project might be a bit different.

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
+glide [2] secs to x: [320] y: [-100] // right-hand side of the Stage
```

--- /task ---

--- task ---
**Test:** Click on the green flag. The Scratch Cat and hippo will move to the bus, and the bus will drive off to the right after five seconds. 
--- /task ---

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
set [color v] effect to (50) // try numbers up to 200
+show
```

--- /task ---

--- task ---
**Test:** Click on the green flag and watch your animation. The bus should appear in the centre of the Stage and then drive off to the right and disappear. 

Is everyone on the bus when it leaves? You can change the amount of time that the bus waits, if you need to.
--- /task ---

--- save ---
