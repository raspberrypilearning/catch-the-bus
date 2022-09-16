## バスの場面を作る

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Choose a backdrop and add a bus sprite.
</div>
<div>

![学校を背景にしたシティバス.](images/bus-scene.png){:width="300px"}

</div>
</div>

### Open the starter project

--- task ---

[バスに乗るスタータープロジェクト](https://scratch.mit.edu/projects/582214330/editor){：target = "_blank"}を開きます。 スクラッチはブラウザの別のタブで開きます。

[[[working-offline]]]

--- /task ---

### Choose a Backdrop

--- task ---

ステージペイン(画面の右下隅) で**背景を選ぶ**をクリック(またはタブレットではタップ) します。:

![A screenshot of the choose a backdrop icon.](images/choose-a-backdrop.png)

--- /task ---

--- task ---

**背景**(はいけい) アイコンをクリックします。 バスの出発地点に合った背景を追加します。

![学校を背景にしたステージ。](images/outdoor-backdrop.png)

--- /task ---

### Choose a Sprite

--- task ---

**スプライトを選ぶ**をクリックします。

![A screenshot of the choose a sprite menu.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

上部の検索ボックスに`bus`と入力してください:

![スプライトライブラリで強調表示されている検索ボックス。](images/bus-search.png)

プロジェクトに **City Bus** (市バス) のスプライトを追加しましょう。

--- /task ---

### Give your bus a starting position

--- task ---

Make sure that the **City Bus** sprite is selected in the Sprite list below the Stage.

Drag a `when green flag clicked`{:class="block3events"} block from the `Events`{:class="block3events"} blocks menu to the Code area:

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
```

--- /task ---

--- task ---

Drag the bus to a good position on the Stage:

![The bus at the bottom middle of the Stage.](images/bus-bottom-middle.png)

The **x** and **y** coordinates (the numbers used to describe the position) of the bus are shown in the Sprite pane below the Stage:

![A screenshot highlighting where the coordinates are located in the sprite pane.](images/coords-sprite-pane.png)

--- /task ---

--- task ---

Add a `go to x: y:`{:class="block3motion"} block:

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
+go to x: (0) y: (-100)
```

The numbers in the `go to x: y:`{:class="block3motion"} block are the current x and y coordinates of the bus. The numbers in your project might be a bit different.

--- /task ---

--- task ---

**Test:** Drag the bus to anywhere on the Stage, and then click on the green flag. The bus should always go to its starting position.

![Animation showing the bus being dragged around the screen and jumping back to the centre when the green flag is clicked.](images/drag-bus.gif)

--- /task ---

### Move the bus behind the character sprites

--- task ---

To make sure that the **City Bus** sprite is always behind all the character sprites, add a `go to front layer`{:class="block3looks"} block, then click on `front`{:class="block3looks"} and change it to `back`{:class="block3looks"}:

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
+ go to [back v] layer
```

**Tip:** If you cannot see the `go to front layer`{:class="block3looks"} block, you need to scroll down in the `Looks`{:class="block3looks"} blocks menu.

--- /task ---

### Change the bus colour

--- task ---

You can change the colour of the bus:

![The City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
+set [color v] effect to (50) // try numbers up to 200
```

--- /task ---

### Resize the Scratch Cat

--- task ---

The Scratch Cat appears in all new Scratch projects as **Sprite1** in the Sprite list. Click on the **Sprite1** sprite in the Sprite list to get ready to animate the Scratch Cat:

![The Sprite1 sprite selected in the Sprite list.](images/sprite1-selected.png)

**Tip:** If you have accidentally deleted the **Sprite1** (Scratch Cat) sprite, you can click on the **Choose a Sprite** icon and search for `cat`.

--- /task ---

--- task ---

In the Sprite pane, click in the **Size** property and change the Scratch Cat's size to `50`:

![A screenshot highlighting the location of the size property in the Sprite pane.](images/sprite-pane-size.png)

--- /task --- 
