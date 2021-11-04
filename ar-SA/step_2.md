## إنشاء مشهد الحافلة الخاص بك

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
ستختار خلفية وتضيف كائن حافلة.
</div>
<div>

! [حافلة المدينة على خلفية المدرسة.] (images / bus-scene.png) {: width = "300px"}

</div>
</div>

--- task ---

افتح [المشروع الابتدائي للحاق بالحافلة](https://scratch.mit.edu/projects/582214330/editor){:target="_blank"}. سيتم فتح Scratch في علامة تبويب متصفح أخرى.

[[[working-offline]]]

--- /task ---

--- task ---

انقر (أو على جهاز لوحي ، اضغط) على **اختر خلفية** في جزء المنصة (في الركن الأيمن السفلي من الشاشة):

![](images/choose-a-backdrop.png)

--- /task ---

--- task ---

انقر فوق أيقونة **الخلفية**. أضف خلفية تشكل نقطة انطلاق جيدة لحافلتك:

![المنصة مع خلفية المدرسة.](images/outdoor-backdrop.png)

--- /task ---

--- task ---

انقر فوق **اختر كائن**:

![](images/choose-sprite-menu.png)

--- /task ---

--- task ---

اكتب `حافلة` في مربع البحث في الأعلى:

![مربع البحث المميز في مكتبة الرموز.](images/bus-search.png)

أضف **حافلة المدينة** إلى مشروعك.

--- /task ---

 في Scratch ، تقوم بتشغيل المشاريع من خلال النقر على العلم الأخضر أعلى المنصة. يجب أن تكون الحافلة في موضع البداية `عندما يتم النقر على العلم الأخضر`{: class = "block3events"}.

--- task ---

تأكد من تحديد **حافلة مدينة** في قائمة كائن أسفل المنصة.

اسحب كتلة `عند نقر العلم الأخضر`{: class = "block3events"} من قائمة كتلة `الاحداث`{:class="block3motion"} الى مساحة التعليمات البرمجية:

![كائن باص المدينة.](images/bus-sprite.png)

```blocks3
when flag clicked
```

--- /task ---

--- task ---

اسحب الحافلة إلى موضع جيد على المنصة:

![الحافلة في منتصف الجزء السفلي من المنصة.](images/bus-bottom-middle.png)

يتم عرض **×** و **y** (الأرقام المستخدمة لوصف الموضع) للحافلة في جزء الرموز أسفل المنصة:

![](images/coords-sprite-pane.png)


--- /task ---

--- task ---

أضف `انتقل إلى كتلة x: y:`{: class = "block3motion"}:

![كائن باص المدينة.](images/bus-sprite.png)

```blocks3
when flag clicked
+go to x: (0) y: (-100)
```

الأرقام الموجودة في `الذهاب إلى كتلة x: y:`{: class = "block3motion"} هي إحداثيات x و y الحالية للحافلة. قد تكون الأرقام في مشروعك مختلفة بعض الشيء.

--- /task ---

--- task ---

**اختبار:** اسحب الحافلة إلى أي مكان على المنصة ، ثم انقر فوق العلم الأخضر. يجب أن تذهب الحافلة دائمًا إلى موضع البداية.

--- /task ---

عندما تسحب الحافلة ، تذهب أمام كائن القطة.

--- task ---

للتأكد من أن **حافلة مدينة** دائمًا ما يكون خلف جميع الكائنات`انتقل إلى الطبقة الأمامية`{: class = "block3looks"} ، ثم انقر على `front`{: class = "block3looks"} وقم بتغييره إلى `رجوع`{: class = "block3looks"}:

![كائن باص المدينة.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
+ go to [back v] layer
```

**نصيحة:** إذا لم تتمكن من رؤية `انتقل إلى`{: class = "block3looks"} ، فأنت بحاجة إلى التمرير لأسفل في `Looks`{: class = "block3looks"}.

--- /task ---

--- task ---

يمكنك تغيير لون الحافلة:

![كائن باص المدينة.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
+set [color v] effect to (50) // try numbers up to 200
```

--- /task ---

--- task ---

يظهر كائن القطة في جميع مشاريع Scratch الجديدة كـ **Sprite1** في قائمة Sprite. انقر فوق **Sprite1** في قائمة Sprite للاستعداد لتحريك القطة:

![تم تحديد كائن Sprite1 في قائمة Sprite.](images/sprite1-selected.png)

**نصيحة:** إذا قمت بحذف **Sprite1** (كائن القطة) عن **اختر كائن** والبحث عن `cat`.

--- /task ---

في الوقت الحالي ، تعد كائن القطة كبيرة جدًا بحيث لا يمكن وضعها في الحافلة.

--- task ---

في جزء كائن ، انقر فوق **الحجم** وقم بتغيير حجم القطة إلى `50`:

![](images/sprite-pane-size.png)

--- /task ---

--- save ---
