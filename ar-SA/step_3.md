## قط سكراتش يلحق بالحافلة

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
سوف تقوم بتحريك القطة لتظهر على **الجانب الأيمن** من المنصة والمشي إلى الحافلة بتكرار حركة صغيرة عدة مرات في **حلقة**. 
</div>
<div>

! [القط يمشي إلى الحافلة.] (images / cat-catches-bus.png) {: width = "300px"}

</div>
</div>

### اجعل كائن القط في وضع البداية

--- task ---

انقر فوق **الاتجاه** في جزء كائن. تدوير السهم للإشارة إلى `-90`. بعد ذلك ، انقر على **يسار / يمين** في المنتصف لتغيير نمط الدوران إلى `يسار - يمين` لإيقاف القط رأسًا على عقب:

![تم تحديد السهم الذي يشير إلى -90 ورمز "يسار / يمين".](images/sprite-pane-direction.png)

--- /task ---

--- task ---

اسحب القط إلى أسفل الجانب الأيمن من المنصة.

![المنصة مع وضع القطة في الركن الأيمن السفلي.](images/bottom-right-cat.png)

**نصيحة:** إذا حاولت وضع كائن بعيدًا عن المنصة ، فسوف يعود إلى آخر موضع له على المنصة.

--- /task ---

--- task ---

أضف تعليمة برمجية لإحضار القط إلى موضع البداية:

![كائن القط.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
```

--- /task ---

--- task ---

**اختبار:** اسحب القط إلى موضع جديد ، ثم انقر فوق `انتقل إلى الموضع س: ص:`{:class="block3motion"}. يجب أن يعود القط إلى الجانب الأيمن السفلي في كل مرة.

--- /task ---

### تحريك القط

ستضيف تعليمة برمجية في حلقة `كرِّر مرة`{:class="block3control"} لتجعل القط يكرر عددًا صغيرًا من الخطوات عدة مرات. هذا سيجعل القط يظهر متحركًا.

--- task ---

أضف `كرِّر مرة`{:class="block3control"} `10` ، ثم اسحب كتلة `حركة`{:class="block3motion"} كتلة `10` `خطوات`{:class="block3motion"} بداخلها:

![تغيير عدد الخطوات في كتلة "النقل" من 10 إلى 5 ، ثم إدخال الكتلة في حلقة "التكرار".](images/block-into-loop.gif)

![كائن القط.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) // bottom right-hand side
+ repeat (10) // try different numbers
move (5) steps //  5 is a good walking speed
end
```

--- /task ---

--- task ---

**اختبار:** انقر فوق العلم الأخضر. حاول تغيير الأرقام بحيث يتوقف القط في الحافلة.

--- /task ---

تحتوي بعض الكائنات على أكثر من زي واحد. سوف تستخدم كائن **Scratch Cat** لإنشاء رسم متحرك لمشي القطة.

--- task ---

انقر فوق علامة التبويب **المظاهر**. **كائن القط** له زيان ، ويمكن استخدامهما معًا للقيام بحركة المشي.

--- /task ---

--- task ---

انقر فوق علامة التبويب **المقاطع البرمجیة**. Add a `next costume`{:class="block3looks"} block inside the `repeat`{:class="block3control"} block:

![كائن القط.](images/scratch-cat-sprite.png)

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

**اختبار:** انقر فوق العلم الأخضر ، وسيقوم القط بالسير إلى الحافلة.

--- /task ---

### إخفاء القط

--- task ---

أضف كتلة إلى `إخفاء`{: class = "block3looks"} القط عند وصولهم إلى الحافلة:

![كائن القط.](images/scratch-cat-sprite.png)

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

**اختبار:** انقر فوق العلم الأخضر مرة أخرى ، وسترى أن القط قد اختفى الآن.

--- /task ---

### أظهار القط

--- task ---

أضف `اظهر`{:class="block3looks"} بحيث تظهر القطة قبل أن يمشوا إلى الحافلة:

![كائن القط.](images/scratch-cat-sprite.png)

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

**نصيحة:** عند استخدام `إخفاء`{:class="block3looks"} ، تحتاج أيضًا إلى إضافة كتلة `اظهر`{:class="block3looks"} للتأكد من أن الكائن مرئي عند الحاجة أن تكون.

--- /task ---

--- task ---

**اختبار:** انقر فوق العلم الأخضر لاختبار مشروعك ، وتأكد من ظهور القط.

--- /task ---

