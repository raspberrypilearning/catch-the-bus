## Hippo flies to the bus

You will add a Hippo sprite that flies to the bus.

![Hippo flying to the bus](images/hippo-flies.png){:width="300px"}

The Hippo1 sprite has two costumes with wings in different positions so it can be animated to fly to the bus.

--- task ---

Add the **Hippo1** sprite to your project. 

Change the size the of the **Hippo1** sprite:

![Hippo Sprite pane with size set to 50](images/hippo-sprite-size.png)

--- /task ---

--- task ---
Drag the hippo to the top left of the Stage:

![Hippo sprite at top left of the Stage](images/hippo-sprite-stage.png)

--- /task ---

--- task ---

Add code to get the hippo to their start position:

```blocks3
when flag clicked
go to x: [-200] y: [150] // top left
```

**Tip:** The x and y coordinates in the `go to`{:class="block3motion"} will be the current position of the hippo so you don't need to type them in.

--- /task ---

The hippo is going to fly towards the bus, flapping their wings. 

The hippo will `point towards`{:class="block3motion"} the bus before moving.

--- task ---

Add code to make the hippo fly towards the **City Bus**:

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+repeat [100] 
point towards (City Bus v) // change from mouse-pointer
move [3] steps
next costume
+end
```

--- /task ---

--- task ---
**Test:** Click the green flag to see the hippo fly to the bus. You can change the number of repeats to get the hippo to stop in just the right place. 
--- /task ---

Now the hippo is going to enter the bus.

--- task ---

Add `show`{:class="block3looks"} and `hide`{:class="block3looks"} blocks:

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+ show
repeat [90] 
point towards (City Bus v)
move [3] steps
next costume
end
+ hide
```

**Tip:** When you use a `hide`{:class="block3looks"} block you will need to also add a `show`{:class="block3looks"} block to make sure the sprite is visible when it needs to be.

--- /task ---

--- task ---
**Test:** Click the green flag to see the hippo fly and enter the bus. 
--- /task ---

--- save ---
