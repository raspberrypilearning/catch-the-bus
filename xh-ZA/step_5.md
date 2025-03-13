## Ibhasi iyahamba

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Yongeza ezinye iibhloki ukwenza ibhasi ihambe.
</div>
<div>

![Iqonga libonisa ukuba ibhasi iye ekunene.](images/bus-leaving.png){:width="300px"}

</div>
</div>

### Yenza ibhasi inengupopayi

--- task ---

Khetha i-sprite esiyi **Ibhasi yeSixeko**.

![Isi-Sprite esiyiIbhasi yesiXeko.](images/bus-sprite.png)

--- /task ---

--- task ---

Yongeza ikhowudi yokwenza ibhasi ihambe iye ekunene imizuzwana emine emva kokuba iflegi eluhlaza icofiwe.

![Isi-Sprite esiyiIbhasi yesiXeko.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // change 1 to 4
```

--- /task ---

--- task ---

Tsalela ibhasi yakho kwicala lasekunene eQongeni. Isalathiso  u`x`{:class="block3motion"} kunye no `y`{:class="block3motion"} yindawo apho ibhasi izaku `tyibilika`{:class="3motion"} khona.

![](images/bus-right.png)

**Ingcebiso:** Ukuba uhambise ibhasi kude kakhulu ukuya ekunene, izakubuyela umva. Zama kwakhona, kodwa ungayihambisi kakhulu ngoku.

--- /task ---

--- task ---

Yongeza ibhulokhi u`tyibilika`{:class="block3motion"} emi-`2` `imizuzu ukuya ku-x: no-y:`{:class="block3motion"} ezantsu kwebhulokhi ka `linda`{:class="block3motion"}.

Ulungelelaniso u-`x` no-`y` kwiprojekhti yakho lungohluka kancinci kwaye luzakuba ngqo kulendawo utsalele ibhasi yakho kuyo.

![Isi-Sprite esiyiIbhasi yesiXeko.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // change 1 to 4
+glide [2] secs to x: [320] y: [-100] // right-hand side of the Stage
```

--- /task ---

--- task ---

**Uvavanyo:** Cofa kwiflegi eluhlaza. Ikati kaScratch kunye nemvubu ziya kufudukela ebhasini, kwaye ibhasi iya kuhamba iye ekunene emva kwemizuzwana emine.

--- /task ---

### Fihla kwaye ubonise iBus

--- task ---

Yongeza ibhulokhi `fuhla`{:class="block3motion"} ukuze wenze ibhasi yakho ibengathi iyahamba:

![Isi-Sprite esiyiIbhasi yesiXeko.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // change 1 to 4
glide [2] secs to x: [320] y: [-100]
+ hide
```
--- /task ---

--- task ---

**Uvavanyo:** Cofa kwiflegi eluhlaza. Ibhasi ngoku iza kuzimela emva kokuba ihambile. Uyakhumbula ukuba ungaqinisekisa njani ukuba i-sprite siphinde sivele xa ucofa iflegi eluhlaza?

--- /task ---

--- task ---

Yongeza ibhulakhi `bonisa`{:class="block3motion"}

![Isi-Sprite esiyiIbhasi yesiXeko.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
set [color v] effect to (85) // try numbers up to 200
+show
```

--- /task ---

--- task ---

**Uvavanyo:** Cofa kwiflegi eluhlaza kwaye ubukele oopopayi bakho. Ibhasi kufuneka ivele embindini weQonga kwaye emva koko iqhube iye ekunene kwaye inyamalale.

Ingaba wonke umntu ukhwele kwibhasi xa ihamba? Ungatshintsha ubude bexesha ibhasi elilindayo, ukuba dinga njalo.

--- /task ---
