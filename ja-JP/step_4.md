## カバはバスに向かって飛ぶ

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
バスに向かって飛ぶカバのスプライトを追加します。
</div>
<div>

![バスに向かって飛ぶカバ。](images/hippo-flies.png){:width="300px"}

</div>
</div>

### カバの開始位置を決める

--- task ---

**Hippo1**スプライトをプロジェクトに追加します。

**Hippo1**スプライトの**大きさ**を変更します。

![大きさが50に設定されたHippo1スプライトのスプライトペイン。](images/hippo-sprite-size.png)

--- /task ---

--- task ---

カバをステージの左上にドラッグします。

![ステージの左上にあるHippo1スプライト。](images/hippo-sprite-stage.png)

--- /task ---

--- task ---

カバを開始位置に動かすコードを追加します。

```blocks3
when flag clicked
go to x: [-200] y: [150] // 上部の左側です
```

**ヒント:** `x座標を〇〇、y座標を〇〇にする`{:class="block3motion"}ブロックの中の`x`{:class="block3motion"}座標と`y`{:class="block3motion"}座標はカバの現在の位置になるので、値を入力する必要はありません。

--- /task ---

### カバを羽ばたかせて飛ばす

--- task ---

**City Bus**に向けてカバを飛ばすコードを追加します。

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+repeat [100] 
point towards (City Bus v) // 「マウスのポインター」から変更
move [3] steps
next costume
+end
```

--- /task ---

--- task ---

**テスト:** 緑色の旗を押すと、カバがバスに向かって飛んでいきます。 `〇回繰り返す`{:class="block3control"}ブロックの数字を変えると、カバをちょうどよいところで止めることができます。

--- /task ---

### バスの表示と非表示

--- task ---

`表示する`{:class="block3looks"}ブロックと `隠す`{:class="block3looks"}ブロックを追加します。

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

**テスト:** 緑色の旗を押します。 カバが飛んでいってバスに乗ります。

--- /task ---
