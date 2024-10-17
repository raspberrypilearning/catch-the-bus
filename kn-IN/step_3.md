## ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಬಸ್ ಹಿಡಿಯುತ್ತದೆ

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Animate the Scratch Cat to appear on the **right-hand side** of the Stage and walk to the bus by repeating a small movement many times in a **loop**. 
</div>
<div>

! [ಬಸ್ಸಿನತ್ತ ನಡೆಯುತ್ತಿರುವ ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್.] (images/cat-catches-bus.png) {: ಅಗಲ = "300px"}

</div>
</div>

### ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಅನ್ನು ಅವರ ಆರಂಭಿಕ ಸ್ಥಾನಕ್ಕೆ ಕಳಿಸಿರಿ

--- task ---

ಸ್ಪ್ರೈಟ್ ಪೇನ್‌ನಲ್ಲಿರುವ ** Direction ** ಪ್ರಾಪರ್ಟಿ ಅನ್ನು ಕ್ಲಿಕ್ ಮಾಡಿ. `-90`ಕ್ಕೆ ಆರೋ ಅನ್ನು ತಿರುಗಿಸಿ. ನಂತರ, ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ತಲೆಕೆಳಗಾಗಿ ತಿರುಗುವುದನ್ನು ನಿಲ್ಲಿಸಲು ತಿರುಗುವಿಕೆಯ ಶೈಲಿಯನ್ನು `ಎಡ-ಬಲ` ಕ್ಕೆ ಬದಲಿಸಲು **Left/Right** ಐಕಾನ್ ಮೇಲೆ ಕ್ಲಿಕ್ ಮಾಡಿ:

![ಬಾಣ -90 ಕ್ಕೆ ಸೂಚಿಸಲಿ ಮತ್ತು 'ಎಡ/ಬಲ' ಐಕಾನ್ ಅನ್ನು ಆಯ್ಕೆ ಮಾಡಿ.](images/sprite-pane-direction.png)

--- /task ---

--- task ---

ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಅನ್ನು ಸ್ಟೇಜ್ ನ ಕೆಳಗಿನ ಬಲಭಾಗಕ್ಕೆ ಎಳೆಯಿರಿ.

![The Stage with the cat positioned in the bottom-right corner.](images/bottom-right-cat.png)

**Tip:** If you try to position a sprite off the Stage, it will move back to its last position on the Stage.

--- /task ---

--- task ---

Add code to get the Scratch Cat to their starting position:

![The Scratch Cat sprite.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
```

--- /task ---

--- task ---

**Test:** Drag the Scratch Cat to a new position, then click on your `go to x: y:`{:class="block3motion"} block. The Scratch Cat should move back to the bottom right-hand side each time.

--- /task ---

### ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಅನ್ನು ಅನಿಮೇಟ್ ಮಾಡಿ

You will add code in a `repeat`{:class="block3control"} loop to make the Scratch Cat repeat a small number of steps many times. This will make the Scratch Cat appear animated.

--- task ---

Add a `repeat`{:class="block3control"} `10` block, then drag a `move`{:class="block3motion"} `10` `steps`{:class="block3motion"} block inside it:

![Changing the number of steps in the 'move' block from 10 to 5, then inserting the block into the 'repeat' loop.](images/block-into-loop.gif)

![The Scratch Cat sprite.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
+ repeat (10) // try different numbers
move (5) steps //  5 is a good walking speed
end
```

--- /task ---

--- task ---

**Test:** Click on the green flag. Try changing the numbers in the `repeat`{:class="block3control"} `10` block so that the Scratch Cat stops at the bus.

--- /task ---

Some sprites have more than one costume. You will use the **Scratch Cat** sprite's costumes to create an animation of the Scratch Cat walking.

--- task ---

Click on the **Costumes** tab. The **Scratch Cat** sprite has two costumes, and together, they can be used to make a walking movement.

--- /task ---

--- task ---

Click on the **Code** tab. Add a `next costume`{:class="block3looks"} block inside the `repeat`{:class="block3control"} block:

![The Scratch Cat sprite.](images/scratch-cat-sprite.png)

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

**Test:** Click on the green flag, and the Scratch Cat will walk to the bus.

--- /task ---

### Hide the Scratch Cat

--- task ---

Add a block to `hide`{:class="block3looks"} the Scratch Cat when they reach the bus:

![ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಸ್ಪ್ರೈಟ್.](images/scratch-cat-sprite.png)

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

**ಪರೀಕ್ಷೆ:** ಹಸಿರು ಧ್ವಜದ ಮೇಲೆ ಮತ್ತೊಮ್ಮೆ ಕ್ಲಿಕ್ ಮಾಡಿ, ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಈಗ ಕಣ್ಮರೆಯಾಗಿರುವುದನ್ನು ನೀವು ನೋಡುತ್ತೀರಿ.

--- /task ---

### Show the Scratch Cat

--- task ---

Add a `show`{:class="block3looks"} block so that the Scratch Cat appears before they walk to the bus:

![The Scratch Cat sprite.](images/scratch-cat-sprite.png)

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

**Tip:** When you use a `hide`{:class="block3looks"} block, you need to also add a `show`{:class="block3looks"} block to make sure that a sprite is visible when it needs to be.

--- /task ---

--- task ---

**Test:** Click on the green flag to test your project, and make sure that the Scratch Cat appears.

--- /task ---

