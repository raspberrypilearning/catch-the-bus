## ಬಸ್ ತಪ್ಪುವುದು

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಬಸ್ ಹಿಡಿಯುವಷ್ಟು ವೇಗವಾಗಿ ಓಡದಿದ್ದರೆ ಹೇಗೆ?
</div>
<div>

! [ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಬಸ್ ಅನ್ನು ಕಳೆದುಕೊಂಡಿದೆ.] (images/cat-misses-bus.png) {: ಅಗಲ = "300px"}

</div>
</div>

### Make Scratch Cat miss the bus

--- task ---

**ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್** ಸ್ಪ್ರೈಟ್ ಅನ್ನು ಆಯ್ಕೆ ಮಾಡಿ ` wait `{: class = "block3control"} ಬ್ಲಾಕ್ ಅನ್ನು ಸೇರಿಸಿ:

![ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಸ್ಪ್ರೈಟ್.](images/scratch-cat-sprite.png)

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

**ಪರೀಕ್ಷೆ:** ಹಸಿರು ಧ್ವಜದ ಮೇಲೆ ಕ್ಲಿಕ್ ಮಾಡಿ. ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ತುಂಬಾ ನಿಧಾನವಾಗಿ ನಡೆದು ಬಸ್ಸನ್ನು ಕಳೆದುಕೊಳ್ಳುತ್ತದೆ!

--- /task ---

### Make Scratch Cat catch the Bus

--- task ---

You will want delays of less than one second. 0.5 is half a second, 0.25 is a quarter of a second, and 0.1 is a tenth of a second.

` wait `{: class = "block3control"} ಬ್ಲಾಕ್‌ನಲ್ಲಿ ವಿಳಂಬವನ್ನು ಬದಲಾಯಿಸಿ:

![ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ಸ್ಪ್ರೈಟ್.](images/scratch-cat-sprite.png)

```blocks3
wait (0.2) seconds // try 0.1, 0.5, 0.05
```

**ಪರೀಕ್ಷೆ:** ಹಸಿರು ಧ್ವಜದ ಮೇಲೆ ಕ್ಲಿಕ್ ಮಾಡಿ, ಸ್ಕ್ರಾಚ್ ಕ್ಯಾಟ್ ವೇಗವಾಗಿ ನಡೆಯುತ್ತದೆ. ನೀವು ಹೆಚ್ಚು ಇಷ್ಟಪಡುವ ವಿಳಂಬವನ್ನು ಆರಿಸಿ.

--- /task ---

### Choose if Scratch Cat catches or misses the bus

--- task ---

If you want the Scratch Cat to **miss the bus**, remove the `hide`{:class="block3looks"} block from your code so that the Scratch Cat stays on the Stage:

![Dragging the 'hide' block from the script in the Code area to the Blocks menu to remove the block from the script.](images/removing-blocks-at-script-ends.gif)

![The Scratch Cat sprite.](images/scratch-cat-sprite.png)

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

If you want the Scratch Cat to **catch the bus**, make the bus wait longer before it leaves:

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked 
+wait [4] seconds // change from 4 to 6
glide [2] secs to x: [320] y: [-100] // right-hand side of the Stage
hide
```

You will need to put the `hide`{:class="block3looks"} block back in the **Scratch Cat** sprite's code if you have removed it and want the Scratch Cat to successfully catch the bus.

--- /task ---

--- task ---

Make changes until you get the animation to work the way that you want it to.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
When working on a project, you often go back and change or improve your code as you get new ideas. 
</p>



