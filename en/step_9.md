## Upgrade your project

Now you can add a sprite of your choice to your animation. You will need to add code to make your sprite `go to`{:class="block3motion"} a start position `point`{:class="block3motion"} in the right direction and then `repeat`{:class="block3control"} `move`{:class="block3motion"} and `next costume`{:class="block3looks"} blocks to reach the bus.

**Tip:** When you click 'Choose a sprite', you can hover over a sprite to see its costumes and find a sprite that works well for animation. 

You can use any of the blocks you learned about in this project as well as those you already know:

<code class="blocks" style="background-color: white">when flag clicked</code><code class="blocks" style="background-color:white">when [timer v] > [5]</code><code class="blocks" style="background-color:white">go to x: [0] y: [0] // drag sprite to choose x and y</code><code class="blocks" style="background-color:white">show</code><code class="blocks" style="background-color:white">hide</code><code class="blocks" style="background-color:white">glide [2] secs to x: [0] y: [-100] // bottom middle of Stage</code><code class="blocks" style="background-color:white">repeat [30]</code><code class="blocks" style="background-color:white">point towards (City Bus v)</code><code class="blocks" style="background-color:white">point in direction (180) // point down</code><code class="blocks" style="background-color:white">set rotation style [left-right v]</code><code class="blocks" style="background-color:white">move [3] steps</code><code class="blocks" style="background-color:white">next costume</code><code class="blocks" style="background-color:white">start sound [clown honk v]</code><code class="blocks" style="background-color:white">wait [0.1] seconds // short delay</code><code class="blocks" style="background-color:white">set [color v] effect to [50] // up to 200</code>



You can also 'remix' the project to make any changes you like. You could add sound effects to the bus or other sprites. You could set the colour effect of the bus. 

<script>
scratchblocks.renderMatching("code.blocks", {
  inline: true,
  style:     'scratch3',   // Optional, defaults to 'scratch2'.
  // Repeat `style` and `languages` options here.
});
</script>


