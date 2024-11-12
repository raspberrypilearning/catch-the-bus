## Yr hipo yn hedfan i'r bws

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Byddi di'n ychwanegu corlun hipo sy'n hedfan i'r bws.
</div>
<div>

![Yr hipo yn hedfan i'r bws.](images/hippo-flies.png){:width="300px"}

</div>
</div>

### Give the Hippo a starting position

--- task ---

Add the **Hippo1** sprite to your project.

Ychwanega'r corlun **City Bus** at dy brosiect.

![The Sprite pane for the Hippo1 sprite, with the size set to 50.](images/hippo-sprite-size.png)

--- /task ---

--- task ---

Drag the hippo to the top left-hand side of the Stage.

![The Hippo1 sprite on the top left-hand side of the Stage.](images/hippo-sprite-stage.png)

--- /task ---

--- task ---

Add code to get the hippo to their starting position:

```blocks3
when flag clicked
go to x: [-200] y: [150] // top left-hand side
```

Ychwanega god i roi'r hipo yn ei safle dechreuol:

--- /task ---

### Make the Hippo flap its wings and fly

--- task ---

Bydd yr hipo yn hedfan tuag at y bws, gan fflapio ei adenydd.

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

**Test:** Click on the green flag and check that the hippo flies to the bus. You can change the number in the `repeat`{:class="block3control"} block to get the hippo to stop in just the right place.

--- /task ---

### Show and hide the bus

--- task ---

**Prawf:** Clicia ar y faner werdd a gwirio bod yr hipo yn hedfan i'r bws. Galli di newid y rhif yn y bloc `ailadrodd`{:class="block3control"} i gael yr hipo i stopio yn yr union le cywir.

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

--- /task ---

--- task ---

**Test:** Click on the green flag. The hippo will fly and enter the bus.

--- /task ---
