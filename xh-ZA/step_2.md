## Yenza owakho umboniso

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Khetha umfanekiso wangemva kwaye ufake ne si-sprite esiyi bhasi.
</div>
<div>

![Ibhasi yesiXeko kumbosi wangemva kweSikolo.](images/bus-scene.png){:width="300px"}

</div>
</div>

### Vula iprojekthi yokuqalisa

--- task ---

Vula [iprojekthi yokuqalisa ethi Leqa ibhasi](https://scratch.mit.edu/projects/582214330/editor){:target="_blank"}. uScratch uya kuvula kwenye ithebhu yesikhangeli.

[[[working-offline]]]

--- /task ---

### Khetha umfanekiso wangasemva

--- task ---

Cofa (okanye kwithebhulethi, chwetha) ku **Khetha umfanekiso wangemva** kwisahlulo seqonga (kwikona esezantsi ekunene kwekhusi):

![Umfanekiso wekhusi ka khetha umfanekiso wangasemva.](images/choose-a-backdrop.png)

--- /task ---

--- task ---

Cofa kudididi lwa**Ngaphandle**. Yongeza umfanekiso wangemva ozakwenza isiqalo esihle sebhasi yakho:

![Iqonga ilinomfanekiso weSkolo ngasremva.](images/outdoor-backdrop.png)

--- /task ---

### Khetha iSprite

--- task ---

Cofa ku **Khetha i-Sprite**:

![Umfanekiso wekhusi ka khetha imenyu ye-sprite.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Chwetheza `ibhasi` kwibhokisi yokukhangela phezulu:

![Ibhokisi yokukhangela iphawulwe kwithala leencwadi leSprite.](images/bus-search.png)

Yongeza **Ibhasi yeSixeko** esisprite kwiprojekthi yakho.

--- /task ---

### Nika ibhasi yakho indawo yokuqala

--- task ---

Qinisekisa ukuba isprite esiy**Ibhasi yesiXeko** sikhethiwe kuluhlu lwezi-Sprite ngezantsi kweqonga.

Tsala ibhlokhi ethi `xa iflegi eluhlaza icofiwe`{:class="block3events"} esuka kwiibhloko zemenyu `Iziganeko`{:class="block3events"} uyibeke kwindawo yeKhowudi:

![Isi-Sprite esiyiIbhasi yesiXeko.](images/bus-sprite.png)

```blocks3
when flag clicked
```

--- /task ---

--- task ---

Tsala ibhasi uyibeke kwindawo elungileyo eqongeni:

![Ibhasi esezantsi embindini weQonga.](images/bus-bottom-middle.png)

Ulungelelaniso luka-**x** kunye no-**y** (amanani asetyenzisiweyo ukuchaza indawo) yebhasi abonisiwe kwipheyini ye-Sprite ngezantsi kweQonga:

![Umfanekiso wekhusi ophawulayo apho ulungelelwaniso lubekwe khona kwipheyini yesprite.](images/coords-sprite-pane.png)

--- /task ---

--- task ---

Yongeza ibhloko ka `yiya ku-x: y:`{:class="block3motion"}:

![Isi-Sprite esiyiIbhasi yesiXeko.](images/bus-sprite.png)

```blocks3
when flag clicked
+go to x: (0) y: (-100)
```

Amanani akwibhloki `yiya ku-x: y:`{:class="block3motion"} amelane nolungelelwaniso luka-x kunye no-y lwebhasi. Amanani kwiprojekthi yakho anokwahluka.

--- /task ---

--- task ---

**Uvavanyo:** Tsala ibhasi ukuya naphi na eQongeni, emva koko ucofe kwiflegi eluhlaza. Ibhasi kufuneka isoloko isiya kwindawo yayo yokuqala.

![Upopayi obonisa ibhasi irhuqwa ijikeleze isikrini kwaye itsibela umva ukuya embindini xa iflegi eluhlaza icofiwe.](images/drag-bus.gif)

--- /task ---

### Hambisa ibhasi iyemva kwe-sprites zabalinganiswa

--- task ---

Ukuqinisekisa ukubaisprite **Ibhasi yeSixeko** sisoloko singasemva kwabo bonke abalinganiswa, faka ibhulokhi `yiya kumaleko ongaphambili` ulandele ngokucofa `phambili`{:class="block3looks"} uyitshinste ngokucofa `umva`{:class="block3looks"}:

![Isi-Sprite esiyiIbhasi yesiXeko.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
+ go to [emva v] layer
```

**Ingcebiso:** Ukuba awukwazi ukubona ibhloki ethi `yiya kumaleko ongaphambili`{:class="block3looks"}, kumele uskrole uye ezantsi kwimenyu blokhi `Imbhonakalo`{:class="block3looks"}.

--- /task ---

### Tshintsha umbala webhasi

--- task ---

Ungawutshintsha umbala webhasi:

![Isi-Sprite esiyiIbhasi yesiXeko.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [emva v] layer
+set [umbala v] effect to (50) // zama amanani ukuya kuma- 200
```

--- /task ---

### Tshintsha ubungakanani bekati kaScratch

--- task ---

Ikati kaSprite ibonakala kuzo zonke iiprojekthi zeScratch ezintsha njenge **Sprite1** kuluhlu lweSprite. Cofa kwi **Sprite1** sprite kuluhlu lweSprite ukuze ulungele ukwenza upopayi kweSprite seKati:

![I-Sprite1 sprite ekhethiweyo kuluhlu lweSprite.](images/sprite1-selected.png)

**Ingcebiso:** Ukuba ucime ngempazamo isprite u**Sprite1** (ikati kaScratch), unga cofa ku **Khetha i-Sprite** ukhangele u`kati`.

--- /task ---

--- task ---

Kwipheyini yeSprite, cofa **Ubungakanani** ipropathi kwaye utshintshe ubungakanani beScratch Cat uyenze u`50`:

![Umfanekiso wekhusi oqaqambisa indawo yepropathi yobungakanani kwipheyini yeSprite.](images/sprite-pane-size.png)

--- /task --- 
