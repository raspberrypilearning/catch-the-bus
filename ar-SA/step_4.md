## فرس النهر يطير إلى الحافلة

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
ستضيف كائن فرس النهر الذي يطير إلى الحافلة.
</div>
<div>

![فرس النهر يطير إلى الحافلة.](images/hippo-flies.png){:width="300px"}

</div>
</div>

الكائن **** له زيين بأجنحة في مواضع مختلفة ، لذلك يمكن تحريك الكائن ليطير إلى الحافلة.

--- task ---

أضف الكائن **فرس النهر** إلى مشروعك.

تغيير **الحجم** لـكائن **فرس النهر**:

![جزء للكائن فرس النهر ، مع ضبط الحجم على 50.](images/hippo-sprite-size.png)

--- /task ---

--- task ---

اسحب فرس النهر إلى أعلى الجانب الأيسر من المنصة.

![كائن فرس النهر الموجود أعلى الجانب الأيسر من المنصة.](images/hippo-sprite-stage.png)

--- /task ---

--- task ---

أضف الكود لإيصال فرس النهر إلى موضع البداية:

```blocks3
when flag clicked
go to x: [-200] y: [150] // أعلى الجانب الأيسر
```

**نصيحة:** سيكون `×`{:class="block3motion"} و `y`{:class="block3motion"} في الجزء `انتقل إلى كتلة x: y:`{:class="block3motion"} الموقع الحالي لفرس النهر ، لذلك لا تحتاج إلى كتابته.

--- /task ---

سوف يطير فرس النهر باتجاه الحافلة ، يرفرف بجناحيه.

فرس النهر سوف `يحدد الاتجاه نحو`{:class="block3motion"} الحافلة قبل التحرك.

--- task ---

أضف الكود لجعل فرس النهر يطير باتجاه **باص المدينة**:

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+repeat [100] 
point towards (City Bus v) // تغيير من مؤشر الماوس
move [3] steps
next costume
+end
```

--- /task ---

--- task ---

**اختبار:** انقر على العلم الأخضر وتأكد من أن فرس النهر يطير إلى الحافلة. يمكنك تغيير الرقم في `تكرار`{:class="block3control"} لإيقاف فرس النهر في المكان الصحيح تمامًا.

--- /task ---

الآن ، سيدخل فرس النهر الحافلة.

--- task ---

أضف `إظهار`{:class="block3looks"} و `إخفاء`{:class="block3looks"}:

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

**اختبار:** انقر فوق العلم الأخضر. سوف يطير فرس النهر ويدخل الحافلة.

--- /task ---

--- save ---
