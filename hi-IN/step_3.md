## Scratch Cat बस पकड़ती है

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Animate the Scratch Cat to appear on the **right-hand side** of the Stage and walk to the bus by repeating a small movement many times in a **loop**. 
</div>
<div>

![Scratch Cat बस तक जाती हुई।](images/cat-catches-bus.png){:width="300px"}

</div>
</div>

### Scratch Cat को उसकी शुरुआती स्थिति में लाएं

--- task ---

Sprite वाले हिस्से में **Direction** प्रॉपर्टी  पर क्लिक करें। `-90` को इंगित करने के लिए तीर घुमाएँ। फिर,  बीच में दिए गए **Left/Right** आइकन पर क्लिक करें रोटेशन शैली को `left-right` में बदलने के लिए जिससे Scratch Cat को उल्टा होने से रोका जा सके:

![-90 की ओर इशारा करते हुए तीर और 'बाएं/दाएं' आइकन सीलेक्ट हो गया हे।](images/sprite-pane-direction.png)

--- /task ---

--- task ---

Scratch Cat को Stage के नीचे दाईं ओर ड्रैग करें।

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

### Scratch Cat को एनिमेट करें

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

Click on the **Code** tab. Add a `next costume`{:class="block3looks"} block:

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

बस में पहुंचने पर Scratch Cat को `hide`{:class="block3looks"} करने के लिए एक ब्लॉक जोड़ें:

![Scratch Cat स्प्राइट।](images/scratch-cat-sprite.png)

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

**टेस्ट:** फिर से हरे झंडे पर क्लिक करें, और आप देखेंगे कि Scratch Cat अब गायब हो गई है।

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

