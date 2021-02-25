
## Scratch Cat catches the bus

You will animate the Scratch cat to walk to the bus by repeating a small movement many times in a **loop**. 

--- task ---

Drag Scratch cat to the bottom right edge of the Stage.

**Tip:** If you try to position a sprite off Stage it will move back to its last Stage position. 

--- /task ---

--- task ---

Drag a `go to x: y:`{:class="block3motion"} block to the Code area: 

![Scratch cat sprite](images/scratch-cat-sprite.png)

```blocks3
go to x:(200) y:(-150) // bottom right
```

--- /task ---

--- task ---

**Test:** Drag Scratch cat to a new position then click on your `go to x: y:`{:class="block3motion"} block. Scratch cat should move back to the bottom right each time.

--- /task ---

To animate Scratch cat you will add code to repeat a small amount of steps many times in a loop. 

--- task ---

Add a `repeat 10`{:class="block3control"} block then drag a `move 10 steps`{:class="block3motion"} block inside it: 

![Animated gif inserting a block into a loop](images/block-into-loop.gif)

![Scratch cat sprite](images/scratch-cat-sprite.png)

```blocks3
go to x:(200) y:(-150) // bottom right
+ repeat (30) // try different numbers
move (5) steps //  5 is a good walking speed
end
```

--- /task ---

--- task ---

**Test:** Click on your code to test it. Try changing the numbers so Scratch cat stops at the bus.

--- /task ---

Some sprites have more than one costume. You will use Scratch cat's costumes to create a walking animation.   

--- task ---

Click on the Costumes tab. Scratch cat has two costumes and together they can be used to make a walking movement. 

--- /task ---

--- task ---

Click back to the Code tab. Add a `next costume`{:class="block3looks"} block and click on your code to test it:

![Scratch cat sprite](images/scratch-cat-sprite.png)

```blocks3
go to x:(200) y:(-150) // bottom right
repeat (30) // try different numbers
move (5) steps //  5 is a good walking speed
+ next costume 
end
```
--- /task ---

--- task ---

**Test:** Click on the code to see the Scratch walk to the bus. 

--- /task ---

Now we want Scratch cat to enter the bus. Sprites can hide and show themselves so they are not always visible on the Stage. You will get Scratch cat to hide so it looks like it is catching the bus.

--- task ---

Add a block to `hide`{:class="block3looks"} Scratch cat when it reaches to the bus:

![Scratch cat sprite](images/scratch-cat-sprite.png)

```blocks3
go to x:(200) y:(-150) // bottom right
repeat (30) // try different numbers
move (5) steps //  5 is a good walking speed
next costume 
end
+ hide
```

--- /task ---

--- task ---

**Test:** Click on your code again, and you will see that Scratch cat has now disappeared.

--- /task ---

To get Scratch cat back and run the animation again, you need Scratch cat to show.

--- task ---

Add a `show`{:class="block3looks"} block so Scratch cat appears before walking to the bus:

![Scratch cat sprite](images/scratch-cat-sprite.png)

```blocks3
go to x:(200) y:(-150) // bottom right
+ show
repeat (30) // try different numbers
move (5) steps //  5 is a good walking speed
next costume 
end
hide
```

--- /task ---

Clicking on the code blocks in the Code area is useful for testing your code. Now you will make the code run 3 seconds after the green flag is clicked.

--- task ---

From the `Events`{:class="block3events"} Blocks menu drag a 'when loudness > 10' and connect it to the top of your code. Click on 'loudness' to change it to 'timer' and change the wait time to '3' seconds.

![Scratch cat sprite](images/scratch-cat-sprite.png)

```blocks3
+ when [timer v] > (3) // wait 3 seconds
go to x:(200) y:(-150) // bottom right
show
repeat (30) // try different numbers
move (5) steps //  5 is a good walking speed
next costume 
end
hide
```

--- /task ---

--- task ---

**Test:** Test your code again. This time instead of clicking on the blocks use the green flag to start your project and reset the timer. 

--- /task ---

--- save ---
