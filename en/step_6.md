## Missing the bus

What if Scratch cat didn't run fast enough to catch the bus?

--- task ---

#Slow the run to a walk

![Scratch cat sprite](images/scratch-cat-sprite.png)

```blocks3
when [timer v] > (3) // wait 3 seconds
go to x:(-200) y:(-150) // bottom left
show
repeat (30) // try different numbers
move (5) steps //  5 is a good walking speed
+ wait (0.5) seconds
next costume 
end
hide
```

--- /task ---

--- task ---

#Don't hide the cat when the bus leaves

![Scratch cat sprite](images/scratch-cat-sprite.png)

```blocks3
when [timer v] > (3) // wait 3 seconds
go to x:(-200) y:(-150) // bottom left
repeat (30) // try different numbers
move (5) steps //  5 is a good walking speed
wait (0.5) seconds
next costume 
end
```

--- /task ---

To change the speed of the costume changes you can add a wait inside the movement loops for the cat or hippo.
You will want delays of less that one second. 0.5 is half a second. 0.25 is a quarter of a second and 0.1 is a tenth of a second. 
Try changing the numbers to get the animation effect you want. 
Try changing the number of steps the sprite moves each time and the number of times the loop repeats.

--- save ---


