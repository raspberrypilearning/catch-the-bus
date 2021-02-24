## Hippo flies to the bus

The Hippo1 sprite has two costumes with wings in different positions so it can be animated to fly to the bus.

--- task ---

Add the **Hippo1** sprite to your project. 

--- /task ---

The hippo is also too big for the bus!

--- task ---

Change the size the of the **Hippo1** sprite:

![Hippo Sprite pane with size set to 50](images/hippo-sprite-size.png)

--- /task ---

--- task ---
Drag the hippo to the top left of the Stage:

![Hippo sprite at top left of the Stage](images/hippo-sprite-stage.png)

--- /task ---

--- task ---

Add code to get the hippo to its start position:

```blocks3
when flag clicked
go to x: [-165] y: [145] // top left
```

**Tip:** The x and y coordinates in the `go to`{:class="block3motion"} will be the current position of the hippo so you don't need to type them in.

--- /task ---

The hippo is going to fly towards the bus, flapping its wings. 

The hippo will `point towards`{:class="block3motion"} the bus before moving.

--- task ---

Add code to make the hippo fly towards the bus:

```blocks3
when flag clicked
go to x: [-165] y: [145] 
+repeat [100] 
point towards (City Bus v)
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
go to x: [-165] y: [145] 
+ show
repeat [100] 
point towards (City Bus v)
move [3] steps
next costume
end
+ hide
```

--- /task ---

--- task ---
**Test:** Click the green flag to see the hippo fly and enter the bus. 
--- /task ---

--- save ---
