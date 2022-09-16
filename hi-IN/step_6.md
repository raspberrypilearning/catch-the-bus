## बस छुटना

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
क्या होगा अगर Scratch Cat बस पकड़ने के लिए पर्याप्त तेजी से नहीं दौड़ी?
</div>
<div>

![Scratch Cat से बस छूट रही हे।](images/cat-misses-bus.png){:width="300px"}

</div>
</div>

### Make Scratch Cat miss the bus

--- task ---

**Scratch Cat** स्प्राइट का चयन करें `wait`{:class="block3control"} ब्लॉक जोड़ें:

![Scratch Cat स्प्राइट।](images/scratch-cat-sprite.png)

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

**टेस्ट:** हरे झंडे पर क्लिक करें। Scratch Cat बहुत धीमी गति से चलेगी और बस छूट जाएगी!

--- /task ---

### Make Scratch Cat catch the Bus

--- task ---

You will want delays of less than one second. 0.5 is half a second, 0.25 is a quarter of a second, and 0.1 is a tenth of a second.

`wait`{:class="block3control"} ब्लॉक में विलंब को बदलें:

![Scratch Cat स्प्राइट।](images/scratch-cat-sprite.png)

```blocks3
wait (0.2) seconds // try 0.1, 0.5, 0.05
```

**टेस्ट:** हरे झंडे पर क्लिक करें, और Scratch Cat तेजी से चलेगी। वह देरी चुनें जो आपको सबसे ज्यादा पसंद हो।

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



