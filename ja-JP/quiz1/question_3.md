--- question ---
---
legend: 質問3/3
---

犬を走らせるために**繰り返す**を使っているスクリプトはどれですか？

![犬がステージの左から右に走るアニメーション。](images/dog-run.gif)

--- choices ---

- (x)
```blocks3
when flag clicked
repeat (5)
move (5) steps
next costume
```

  --- feedback ---

そうです！ `繰り返す`{:class="block3control"}コードブロックはループを使って犬を走らせます。

  --- /feedback ---

- ( )
```blocks3
when flag clicked 
next costume
move (5) steps
```

  --- feedback ---

このコードは犬を動かしますが、動くのは一度だけです。 ここにループがないのでコードは繰り返されません。

  --- /feedback ---

- ()
```blocks3
when flag clicked
next costume
move (5) steps
next costume
move (5) steps
next costume
move (5) steps
next costume
move (5) steps
next costume
move (5) steps
```

  --- feedback ---

このコードは犬を走らせますが、ループを使っていません。 ループを使うと多くの場合コードが短くなります。

  --- /feedback ---

- ( )
```blocks3
when this sprite clicked 
next costume
move (5) steps
```

  --- feedback ---

ここにはループがないので犬が動くのは一度だけです。 犬を走らせるにはループを追加する必要があります。

  --- /feedback ---

--- /choices ---

--- /question ---
