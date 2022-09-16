## Perdendo o ônibus

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
E se o Gato Scratch não for rápido o suficiente para pegar o ônibus?
</div>
<div>

![O Gato Scratch perdendo o ônibus.](Images/cat-misses-bus.png){:width="300px"}

</div>
</div>

### Make Scratch Cat miss the bus

--- task ---

Selecione o **Gato Scratch** e adicione um bloco `aguarde`{:class="block3control"}:

![O ator do Gato Scratch.](images/scratch-cat-sprite.png)

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

**Teste:** Clique na bandeira verde. O Gato Scratch vai andar muito devagar e vai perder o ônibus!

--- /task ---

### Make Scratch Cat catch the Bus

--- task ---

You will want delays of less than one second. 0.5 is half a second, 0.25 is a quarter of a second, and 0.1 is a tenth of a second.

Altere o atraso no bloco `aguarde`{:class="block3control"}:

![O ator do Gato Scratch.](images/scratch-cat-sprite.png)

```blocks3
wait (0.2) seconds // try 0.1, 0.5, 0.05
```

**Teste:** Clique na bandeira verde e o Gato Scratch vai andar mais rápido. Escolha o tempo de atraso que você quiser.

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



