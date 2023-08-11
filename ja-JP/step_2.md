## バスの場面を作る

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
背景を選択し、バスのスプライトを追加します。
</div>
<div>

![学校を背景にしたシティバス.](images/bus-scene.png){:width="300px"}

</div>
</div>

### スタータープロジェクトを開く

--- task ---

[バスに乗るスタータープロジェクト](https://scratch.mit.edu/projects/582214330/editor){:target="_blank"}を開きます。 スクラッチはブラウザの別のタブで開きます。

[[[working-offline]]]

--- /task ---

### 背景を選ぶ

--- task ---

ステージペイン(画面の右下隅) で**背景を選ぶ**をクリック(またはタブレットではタップ) します。:

![背景を選ぶアイコンのスクリーンショット。](images/choose-a-backdrop.png)

--- /task ---

--- task ---

**屋外** カテゴリーをクリックします。 バスの出発地点に合った背景を追加します。

![学校を背景にしたステージ。](images/outdoor-backdrop.png)

--- /task ---

### スプライトを選ぶ

--- task ---

**スプライトを選ぶ**をクリックします。

![スプライトを選ぶメニューのスクリーンショット。](images/choose-sprite-menu.png)

--- /task ---

--- task ---

上部の検索ボックスに`bus`と入力してください:

![スプライトライブラリで強調表示されている検索ボックス。](images/bus-search.png)

プロジェクトに **City Bus** (市バス) のスプライトを追加しましょう。

--- /task ---

### バスの開始位置を決める

--- task ---

ステージの下にあるスプライトリストで**City Bus**スプライトが選択されていることを確認します。

`イベント`{:class="block3events"}ブロックメニューから`緑色の旗が押されたとき`{:class="block3events"}ブロックをコードエリアにドラッグします。

![シティバスのスプライト。](images/bus-sprite.png)

```blocks3
when flag clicked
```

--- /task ---

--- task ---

バスをステージ上の適当な位置にドラッグします。

![ステージ中央下にあるバス。](images/bus-bottom-middle.png)

バスの**x**および**y**座標（位置を表す数値）がステージの下のスプライトペインに表示されます。

![座標がスプライトペインのどこにあるか強調表示するスクリーンショット。](images/coords-sprite-pane.png)

--- /task ---

--- task ---

`x座標を〇〇、y座標を〇〇にする`{:class="block3motion"}ブロックを追加します。

![シティバスのスプライト。](images/bus-sprite.png)

```blocks3
when flag clicked
+go to x: (0) y: (-100)
```

`x座標を〇〇、y座標を〇〇にする`{:class="block3motion"}ブロックの中の数値はバスの現在のx座標とy座標です。 あなたのプロジェクトでは違う数値になっているかもしれません。

--- /task ---

--- task ---

**テスト:** バスをステージ上の好きな場所にドラッグしてから、緑色の旗を押します。 バスは常に開始位置へ移動するはずです。

![バスが画面上でドラッグされ、緑色の旗が押されると中央に戻るアニメーション。](images/drag-bus.gif)

--- /task ---

### バスをキャラクタースプライトの後ろに移動する

--- task ---

**City Bus**スプライトが常にすべてのキャラクタースプライトより後ろになるようにするには、`最前面に移動する`{:class="block3looks"}ブロックを追加し、`最前面`{:class="block3looks"}をクリックして`最背面`{:class="block3looks"}へ変更します。

![シティバスのスプライト。](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
+ go to [back v] layer
```

**ヒント:** `最前面に移動`{:class="block3looks"}ブロックが見つからないときには、`見た目`{:class="block3looks"}ブロックメニューを下にスクロールして探してみてください。

--- /task ---

### バスの色を変える

--- task ---

バスの色も変えられます。

![シティバスのスプライト。](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
+set [color v] effect to (50) // 200までの数
```

--- /task ---

### スクラッチキャットのサイズを変更する

--- task ---

スクラッチキャットは、すべての新しいプロジェクトのスプライトリストに**Sprite1**として表示されます。 スプライトリストの**Sprite1**をクリックして、スクラッチキャットのアニメーションの準備をします。

![スプライトリストで選択されたSprite1のスプライト。](images/sprite1-selected.png)

**ヒント:** 間違えて**Sprite1**（スクラッチキャット）スプライトを削除してしまった場合は、 **スプライトを選ぶ**アイコンをクリックして`cat`を検索します。

--- /task ---

--- task ---

スプライトペインで**大きさ**プロパティをクリックし、スクラッチキャットの大きさを`50`へ変更します。

![スプライトペインの中の大きさプロパティの場所を強調表示するスクリーンショット。](images/sprite-pane-size.png)

--- /task --- 
