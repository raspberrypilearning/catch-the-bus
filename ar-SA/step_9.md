## قم بترقية مشروعك

الآن ، يمكنك إضافة كائن من اختيارك إلى الرسوم المتحركة الخاصة بك. ستحتاج إلى إضافة رمز لجعل الكائن الخاص بك ` ينتقل إلى ` {: class = "block3motion"} موضع بداية ، ` نقطة ` {: class = "block3motion"} في اليمين ، ثم ` كرر ` {: class = "block3control"} ` حرك ` {: class = "block3motion"} و ` الزي التالي ` {:class="block3looks"} للوصول إلى الحافلة.

**نصيحة:** عند النقر فوق **اختيار الكائن**، يمكنك وضع مؤشر الماوس فوق كائن لرؤية أزياءه ، أو على بعض الأجهزة المحمولة ، يمكنك النقر مع الاستمرار على الكائن لرؤية أزياءه (إذا كان هناك نافذة تنبثق عندما تنقر مع الاستمرار على كائن ما ، انقر على جانب الشاشة لإغلاق النافذة ورؤية الأزياء). يمكن أن يساعدك النظر إلى أزياء الكائنات في العثور على كائن يعمل جيدًا للرسوم المتحركة.

![نقوش متحركة أخرى تتحرك نحو حافلة بها نص "Maker Festival".](images/bus-upgrade.png){:width="300px"}

يمكنك استخدام أي من الكتل التي تعلمتها في هذا المشروع ، بالإضافة إلى تلك التي تعرفها بالفعل:

```blocks3
when flag clicked

when [timer v] > [5]

go to x: [0] y: [0] // drag the sprite to choose x and y

show

hide

glide [2] secs to x: [0] y: [-100] // bottom middle of the Stage

repeat [30]
end

point towards (City Bus v)

point in direction (180) // point down

set rotation style [left-right v]

move [3] steps

next costume

start sound [clown honk v]

wait [0.1] seconds // short delay

set [color v] effect to [50] // up to 200
```

--- collapse ---
---
المشروع المكتمل
---

يمكنك عرض [مشروع مكتمل هنا](https://scratch.mit.edu/projects/486719199/){: target = "_ blank"}.

--- /collapse ---

يمكنك أيضًا "إعادة مزج" المشروع لإجراء أي تغييرات تريدها. يمكنك إضافة مؤثرات صوتية إلى الحافلة أو نقوش متحركة أخرى ، أو ضبط تأثير لون الحافلة. يمكن أن تفوت إحدى الكائنات الحافلة ولا تختبئ.

شكر خاص الى المصمم الرقمي Lyla لإرسال هذه الترقية الرائعة!

![مشروع به حافلة بألوان براقة.](images/Lyla-bus.gif)

--- save ---
