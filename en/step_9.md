## Upgrade your project

Now you can add a sprite of your choice to your animation. You will need to add code to make your sprite `go to`{:class="block3motion"} a start position `point`{:class="block3motion"} in the right direction and then `repeat`{:class="block3control"} `move`{:class="block3motion"} and `next costume`{:class="block3looks"} blocks to reach the bus.

**Tip:** When you click 'Choose a sprite', you can hover over a sprite to see its costumes and find a sprite that works well for animation. 

![Bus with Maker Festival text](images/bus-upgrade.png){:width="300px"}

You can use any of the blocks you learned about in this project as well as those you already know:

```blocks3
when flag clicked

when [timer v] > [5]

go to x: [0] y: [0] // drag sprite to choose x and y

show

hide

glide [2] secs to x: [0] y: [-100] // bottom middle of Stage

repeat [30]
end

point towards (City Bus v)

point in direction (180) // point down

set rotation style [left-right v]

move [3] steps

next costume

start sound [clown honk v]

wait [0.1] seconds // short delay

set [color v] effect to [50] // up to 200
```

You can also 'remix' the project to make any changes you like. You could add sound effects to the bus or other sprites. You could set the colour effect of the bus. Maybe one of the sprites misses the bus and doesn't hide. 

--- collapse ---

---
title: Completed project
---

You can view the [completed project](https://scratch.mit.edu/projects/486719199/){:target="_blank"}.

--- /collapse ---

--- save ---
