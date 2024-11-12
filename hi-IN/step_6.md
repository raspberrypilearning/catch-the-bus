## बस छुटना

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
क्या होगा अगर Scratch Cat बस पकड़ने के लिए पर्याप्त तेजी से नहीं दौड़ी?
</div>
<div>

![Scratch Cat से बस छूट रही हे।](images/cat-misses-bus.png){:width="300px"}

</div>
</div>

### Scratch Cat को बस न पकड़ने दो

--- task ---

**Scratch Cat** स्प्राइट का चयन करें `wait`{:class="block3control"} ब्लॉक जोड़ें:

![Scratch Cat स्प्राइट।](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) 
show
repeat (20) // try different numbers
move (5) steps 
next costume 
+ wait (1) seconds
end
hide
```
--- /task ---

--- task ---

**टेस्ट:** हरे झंडे पर क्लिक करें। Scratch Cat बहुत धीमी गति से चलेगी और बस छूट जाएगी!

--- /task ---

### Scratch Cat को बस पकड़ने दो

--- task ---

आप एक सेकंड से भी कम की देरी चाहते हैं। 0.5 आधा सेकेंड है, 0.25 सेकेंड का एक चौथाई है, और 0.1 सेकेंड का दसवां हिस्सा है।

`wait`{:class="block3control"} ब्लॉक में विलंब को बदलें:

![Scratch Cat स्प्राइट।](images/scratch-cat-sprite.png)

```blocks3
wait (0.2) seconds // try 0.1, 0.5, 0.05
```

**टेस्ट:** हरे झंडे पर क्लिक करें, और Scratch Cat तेजी से चलेगी। वह देरी चुनें जो आपको सबसे ज्यादा पसंद हो।

--- /task ---

### चुनें कि क्या Scratch Cat बस पकड़ती है या बस छूट जाती है

--- task ---

अगर आप चाहते हैं की Scratch Cat **बस ना पकड़ पाए**, तो `hide`{:class= "block3looks"} ब्लॉक को अपने कोड से हटाए ताकि Stage पर Scratch Cat बनी रहे:

!['hide' ब्लॉक को Code एरिया में स्क्रिप्ट से Blocks मेनू तक ड्रैग कर रहें हैं जिससे स्क्रिप्ट से ब्लॉक हट जाये।](images/removing-blocks-at-script-ends.gif)

![Scratch Cat स्प्राइट।](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) 
show
repeat (20) 
move (5) steps 
next costume
wait (0.5) seconds 
end
-hide
```
--- /task ---

--- task ---

यदि आप चाहते हैं कि Scratch Cat **बस को पकड़ ले**, तो बस के निकलने से पहले अधिक प्रतीक्षा करें:

![City Bus स्प्राइट।](images/bus-sprite.png)

```blocks3
when flag clicked 
+wait [4] seconds // change from 4 to 6
glide [2] secs to x: [320] y: [-100] // right-hand side of the Stage
hide
```

आपको `hide`{:class="block3looks"} ब्लॉक को **Scratch Cat** स्प्राइट के कोड में वापस रखना होगा, यदि आपने इसे हटा दिया है और Scratch Cat को सफलतापूर्वक बस पकड़ाना चाहते हैं तो ।

--- /task ---

--- task ---

तब तक बदलाव करें जब तक कि आपको ऐनिमेशन उस तरह से काम करने के लिए न मिल जाए जैसा आप चाहते हैं।

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
किसी प्रोजेक्ट पर काम करते समय, आप अक्सर वापस जाते हैं और नए विचार प्राप्त होने पर अपना कोड बदलते या सुधारते हैं। 
</p>



