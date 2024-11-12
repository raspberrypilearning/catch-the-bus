## बस चुकली

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
जर स्क्रॅच मांजर बस पकडण्याइतपत वेगाने धावली नाही तर?
</div>
<div>

![स्क्रॅच मांजरची बस चुकली](images/cat-misses-bus.png){:width="300px"}

</div>
</div>

### Make Scratch Cat miss the bus

--- task ---

**स्क्रॅच कॅट** स्प्राइट निवडा आणि `प्रतीक्षा`{:class="block3control"} ब्लॉक जोडा:

![स्क्रॅच मांजर स्प्राइट.](images/scratch-cat-sprite.png)

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

**चाचणी:** हिरव्या ध्वजावर क्लिक करा. स्क्रॅच मांजर खूप हळू चालेल आणि बस चुकवेल!

--- /task ---

### Make Scratch Cat catch the Bus

--- task ---

You will want delays of less than one second. 0.5 is half a second, 0.25 is a quarter of a second, and 0.1 is a tenth of a second.

`प्रतीक्षा`{:class="block3control"} ब्लॉकमधील विलंब बदला:

![स्क्रॅच मांजर स्प्राइट.](images/scratch-cat-sprite.png)

```blocks3
wait (0.2) seconds // try 0.1, 0.5, 0.05
```

**चाचणी:** हिरव्या ध्वजावर क्लिक करा आणि स्क्रॅच मांजर वेगाने चालेल. तुम्हाला सर्वात जास्त आवडणारा विलंब निवडा.

--- /task ---

### Choose if Scratch Cat catches or misses the bus

--- task ---

जर तुम्हाला स्क्रॅच कॅटने **बस**चुकवायची असेल, तर तुमच्या कोडमधून `hide`{:class="block3looks"} ब्लॉक काढून टाका जेणेकरून स्क्रॅच मांजर स्टेजवर राहील:

![स्क्रिप्टमधून ब्लॉक काढण्यासाठी कोड एरियामधील स्क्रिप्टमधून ब्लॉक मेनूवर 'लपवा' ब्लॉक ड्रॅग करा.](images/removing-blocks-at-script-ends.gif)

![स्क्रॅच कॅट स्प्राइट.](images/scratch-cat-sprite.png)

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

जर तुम्हाला स्क्रॅच कॅटने **बस**पकडायची असेल, तर बस निघण्यापूर्वी जास्त वेळ थांबा:

![सिटी बस स्प्राइट.](images/bus-sprite.png)

```blocks3
when flag clicked 
+wait [4] seconds // change from 4 to 6
glide [2] secs to x: [320] y: [-100] // right-hand side of the Stage
hide
```

जर तुम्ही `hide`{:class="block3looks"} ब्लॉक काढून टाकला असेल आणि स्क्रॅच कॅट यशस्वीपणे बस पकडू इच्छित असाल तर तो परत **स्क्रॅच कॅट** स्प्राइटच्या कोडमध्ये टाकणे गरजेचे आहे.

--- /task ---

--- task ---

तुम्‍हाला हवे तसे अॅनिमेशन मिळेपर्यंत बदल करा.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
एखाद्या प्रकल्पावर काम करत असताना, तुम्ही अनेकदा परत जाता आणि तुम्हाला नवीन कल्पना मिळाल्यामुळे तुमचा कोड बदलतो किंवा सुधारतो. 
</p>



