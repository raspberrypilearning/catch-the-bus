## Create your bus scene

You will choose a backdrop and add a bus sprite.

--- task ---

Open a [new Scratch project](http://rpf.io/scratch-new){:target="_blank"}. Scratch will open in another browser tab.

--- collapse ---
---
title: Working offline
---
To set up Scratch for offline use visit [our Scratch guide](https://learning-admin.raspberrypi.org/en/projects/getting-started-scratch/1){:target="_blank"}.
--- /collapse ---

--- /task ---

--- task ---

Click (or tap) on **Choose a Backdrop** from the Stage pane:

![Scratch editor showing Choose a Backdrop selected in the bottom right corner](images/choose-a-backdrop.png)

--- /task ---

--- task ---

Click  the **Outdoors** category. Find a backdrop that makes a good starting point for a bus tour. We chose the School backdrop. Where will your characters start their journey?

Click on the backdrop to add it to your project: 

![Stage with outdoor backdrop](images/outdoor-backdrop.png)

--- /task ---

--- task ---

Click on 'Choose a sprite'. 

![Choose a sprite menu](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Type 'bus' in the search box at the top:

![Sprite search showing bus](images/bus-search.png)

Add the **City Bus** sprite to your project.

--- /task ---

You want the bus to be in its start position when you run your project. To do this you use a `when green flag clicked`{:class="block3events"} block which runs the blocks underneath it when you click on the green flag above the stage.

--- task ---
Make sure the **Scratch Tour Bus** sprite is selected in the Sprite list below the Stage.

Drag a `when green flag clicked`{:class="block3events"} block from the `Events`{:class="block3events"} Blocks menu to the Code area. 

![Bus sprite](images/bus-sprite.png)

```blocks3
when flag clicked
```

**Tip:** The image in the top right of the Code area shows which sprite you are adding code to.

![Highlighted image of sprite in Code area](images/sprite-in-code-area.png)
https://prod.liveshare.vsengsaas.visualstudio.com/join?8AC44D247CF4D45B0E626B815D91225D6C7E

--- /task ---

Oh no, our bus is not parked in a good spot!

![bus in the middle of Stage](images/bus-in-middle.png)

--- task ---

Drag the bus to a good position in the middle of the stage at the bottom:

![bus at bottom middle of Stage](images/bus-bottom-middle.png)

The x and y coordinates of the bus show in the Sprite pane below the Stage:

![x and y coordinates of bus in the Sprite pane](images/coords-sprite-pane.png)


--- /task ---

--- task ---
Drag a `go to x: () y: ()`{:class="block3motion"} block from the `Motion`{:class="block3motion"} block menu, and place it under your first code block.

Your code should look like this:

```blocks3
when flag clicked
+go to x: (0) y: (-100)
```

The numbers in the `go to x: () y: ()`{:class="block3motion"} are the current x and y coordinates of the bus. Your numbers might be slightly different. 

--- /task ---

--- task ---

**Test:** Drag the bus to anywhere on the Stage and then click the green flag. The bus should always go to its starting position at the bottom middle of the Stage.

--- /task ---

--- save ---

