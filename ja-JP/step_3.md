## スクラッチキャットがバスに乗る

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
スクラッチキャットをアニメーション化してステージの**右側**に表示し、**ループ**で小さな動きを何度も繰り返してバスまで歩かせます。 
</div>
<div>

！[バスに向かって歩いているスクラッチキャット。](images/cat-catches-bus.png){:width="300px"}

</div>
</div>

### スクラッチキャットを出発地点に移動します。

--- task ---

スプライトペインの **方向** プロパティをクリックします。 `-90`を指すように矢印を動かす 。 **左/右** アイコンをクリックして、回転スタイルを `左右`と し、スクラッチキャットが上下逆さまになるのを防ぎます。

![-90を指す矢印と、「左/右」アイコンが選択されています。](images/sprite-pane-direction.png)

--- /task ---

--- task ---

スクラッチキャットをステージの右下にドラッグします。

![右下隅にネコが配置されたステージ。](images/bottom-right-cat.png)

**ヒント:** スプライトをステージの外に配置しようとすると、スプライトはステージ上の最後の位置に戻ります。

--- /task ---

--- task ---

スクラッチキャットを開始位置に動かすコードを追加します。

![スクラッチキャットのスプライト。](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
```

--- /task ---

--- task ---

**テスト:** スクラッチキャットを新しい場所にドラッグしたら、`x座標を〇〇、y座標を〇〇にする`{:class="block3motion"}ブロックをクリックします。 スクラッチキャットは右下にいつも戻るはずです。

--- /task ---

### スクラッチキャットをアニメーション化する

`繰り返す`{:class="block3control"}ループにコードを追加して、スクラッチキャットが少ないステップを何度も繰り返すようにします。 これにより、スクラッチキャットがアニメーション化されたように見えます。

--- task ---

`10回``繰り返す`{:class="block3control"}ブロックを追加して、次に`10``歩動かす`{:class="block3control"}ブロックをその中にドラッグします。

![「〇歩動かす」ブロックの歩数を10から5に変更して、そのブロックを「繰り返す」ループに挿入している。](images/block-into-loop.gif)

![スクラッチキャットのスプライト。](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
+ repeat (10) // try different numbers
move (5) steps //  5 is a good walking speed
end
```

--- /task ---

--- task ---

**テスト:** 緑色の旗を押します。 スクラッチキャットがバスのところで止まるように、`10``回繰り返す`{:class="block3control"}ブロックの数字を変えてみてください。

--- /task ---

一部のスプライトには複数のコスチュームがあります。 **Scratch Cat**スプライトのコスチュームを使って、スクラッチキャットが歩くアニメーションを作ります。

--- task ---

**コスチューム**タブをクリックします。 **Scratch Cat**スプライトには2つのコスチュームがあり、一緒に使うことで歩く動きを表現できます。

--- /task ---

--- task ---

**コード**タブをクリックします。 `次のコスチューム`{:class="block3looks"}ブロックを追加します。

![スクラッチキャットのスプライト。](images/scratch-cat-sprite.png)

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

**テスト:** 緑色の旗を押すと、スクラッチキャットがバスに向かって歩きます。

--- /task ---

### スクラッチキャットを隠す

--- task ---

バスに到着したときにスクラッチキャットを`隠す`{:class="block3looks"}ブロックを追加します。

![スクラッチキャットのスプライト。](images/scratch-cat-sprite.png)

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

**テスト:** 緑色のフラグをもう一度クリックして、スクラッチキャットが消えることを確かめましょう。

--- /task ---

### スクラッチキャットを表示する

--- task ---

`表示する`{:class="block3looks"}ブロックを追加して、バスに行く前にスクラッチキャットが表示されるようにします。

![スクラッチキャットのスプライト。](images/scratch-cat-sprite.png)

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

**ヒント:** `隠す`{:class="block3looks"}ブロックを使う場合は `表示する`{:class="block3looks"}ブロックも追加して、必要なときにスプライトが表示されるようにしてください。

--- /task ---

--- task ---

**テスト:** 緑色の旗を押してプロジェクトをテストし、スクラッチキャットが表示されることを確認します。

--- /task ---

