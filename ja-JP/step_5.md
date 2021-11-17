## バスの出発

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
スクラッチでは、つながったブロックのグループを**スクリプト**と呼びます。 バスを出発させるスクリプトを追加します。
</div>
<div>

![バスが右に移動したことを示すステージ。](images/bus-leaving.png){:width="300px"}

</div>
</div>

緑のフラグが押されてから4秒後にバスが右に走ります。 `タイマー`{:class="block3events"}ブロックは、この時間の経過後にこの下のブロックを実行します。

--- task ---

**City Bus**スプライトを追加します。

![シティバスのスプライト。](images/bus-sprite.png)

--- /task ---

--- task ---

`イベント`{:class="block3events"}ブロックメニューから`音量 >`{:class="block3events"} `10``のとき`{:class="block3events"} ブロックをコードエリアにドラッグする。 `音量`{:class="block3events"}を `タイマー`{:class="block3events"}に変更します。 これにより、新しいスクリプトが開始されます。

![シティバスのスプライト。](images/bus-sprite.png)

```blocks3
when [timer v] > [4] // 10から4に変更
```

--- /task ---

--- task ---

バスをステージの右側にドラッグします。 これはバスの行先を`X`{:class="block3motion"}`Y`{:class="block3motion"}座標に`変える`{:class="block3motion"}ことができます。

![](images/bus-right.png)

**ヒント:** バスを右に移動しすぎるとジャンプして戻ります。 もう一度トライしてください。あんまり遠くまで動かさないように。

--- /task ---

--- task ---

`タイマー`{:class="block3events"} ブロックの下に`2``秒でx座標、y座標を変える`{:class="block3motion"} ブロックを追加します。

`X`{:class="block3motion"}と `Y`{:class="block3motion"}の値が少し違うかもしれません。

![シティバスのスプライト。](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
+glide [2] secs to x: [320] y: [-100] // ステージの右側
```

--- /task ---

--- task ---

**テスト:** 緑色のフラグをクリックします。 スクラッチキャットとカバがバスに向かって移動して4秒後にバスが右に走ります。

--- /task ---

--- task ---

`隠す`{:class="block3looks"}ブロックを追加して、バスがステージから走り出すように見せます。:

![シティバスのスプライト。](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
glide [2] secs to x: [320] y: [-100]
+ hide
```
--- /task ---

--- task ---

**テスト:** 緑色のフラグを押します。 バスは運転を終えると隠れます。 緑のフラグを押したときにスプライトが再び表示されるようにする方法を覚えていますか？

--- /task ---

--- task ---

`表示する`{:class="block3looks"}ブロックを `緑のフラグが押されたとき`{:class="block3events"}に追加して、プロジェクトの実行時にバスを表示します。

![シティバスのスプライト。](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
set [color v] effect to (50) // 200までの数
+show
```

--- /task ---

--- task ---

**テスト:** 緑色のフラグを押すと、アニメーションが見れます。 バスはステージの中央に表示され、右に走って消え去ります。

バスが出るとき、みんなバスに乗っていますか？ 必要に応じてバスが待っている時間を変えることをできます。

--- /task ---

--- save ---
