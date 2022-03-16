## Creëer je busscène

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Je kiest een achtergrond en voegt een bus-sprite toe.
</div>
<div>

![De stadsbus op de achtergrond van de school.](images/bus-scene.png){:width="300px"}

</div>
</div>

--- task ---

Open het [Neem de bus startproject](https://scratch.mit.edu/projects/582214330/editor){:target="_blank"}. Scratch wordt in een nieuw browsertabblad geopend.

[[[working-offline]]]

--- /task ---

--- task ---

Klik (of tik op een tablet) op **Kies een achtergrond** in het speelveld-paneel (in de rechterbenedenhoek van het scherm):

![](images/choose-a-backdrop.png)

--- /task ---

--- task ---

Klik op de categorie **Buiten**. Voeg een achtergrond toe die een goed startpunt is voor je bus:

![Het speelveld met de achtergrond van de School.](images/outdoor-backdrop.png)

--- /task ---

--- task ---

Klik op **Kies een Sprite**:

![](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Typ `bus` in het zoekvak bovenaan:

![Het zoekvak gemarkeerd in de Sprite-bibliotheek.](images/bus-search.png)

Voeg de **City Bus** sprite toe aan je project.

--- /task ---

 In Scratch voer je projecten uit door op de groene vlag boven het speelveld te klikken. De bus moet in de startpositie staan als er `op de groene vlag wordt geklikt`{:class="block3events"}.

--- task ---

Zorg ervoor dat de **City Bus** is geselecteerd in de Sprite lijst onder het speelveld.

Sleep een `wanneer op de groene vlag wordt geklikt`{:class="block3events"} blok uit het `Gebeurtenissen`{:class="block3events"} blokkenmenu naar het huidige sprite paneel:

![De stadsbus-sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
```

--- /task ---

--- task ---

Sleep de bus naar een goede positie op het speelveld:

![De bus onderaan in het midden van het speelveld.](images/bus-bottom-middle.png)

De **x** en **y** coördinaten (de getallen die worden gebruikt om de positie te beschrijven) van de bus worden weergegeven in het Sprite-venster onder het podium:

![](images/coords-sprite-pane.png)


--- /task ---

--- task ---

Voeg een `ga naar x: y:`{:class="block3motion"} blok toe:

![De stadsbus-sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
+go to x: (0) y: (-100)
```

De getallen in het `ga naar x: y:`{:class="block3motion"} blok zijn de huidige x- en y-coördinaten van de bus. De getallen in jouw project kunnen een beetje anders zijn.

--- /task ---

--- task ---

**Test:** Sleep de bus naar een willekeurige plek in het speelveld en klik vervolgens op de groene vlag. De bus zou altijd naar de startpositie moeten gaan.

--- /task ---

Als je de bus sleept, staat deze voor de Scratch kat.

--- task ---

Om ervoor te zorgen dat de **City Bus** altijd achter alle karakter sprites staat, voeg je een `ga naar laag voorgrond`{:class="block3looks"}-blok toe en klik je vervolgens op `voorgrond`{:class="block3looks"} en verander het in `achtergrond`{:class="block3looks"}:

![De stadsbus-sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
+ go to [back v] layer
```

**Tip:** Als je het `ga naar laag voorgrond`{:class="block3looks"} blok niet kunt zien, moet je naar beneden scrollen in het `Uiterlijken`{:class="block3looks"} blokkenmenu.

--- /task ---

--- task ---

Je kunt de kleur van de bus wijzigen:

![De stadsbus-sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
+set [color v] effect to (50) // probeer getallen tot 200
```

--- /task ---

--- task ---

De Scratch kat verschijnt in alle nieuwe Scratch-projecten als **Sprite1** in de Sprite-lijst. Klik op de **Sprite1** sprite in de Sprite-lijst om de Scratch kat te kunnen animeren:

![De Sprite1-sprite die is geselecteerd in de Sprite-lijst.](images/sprite1-selected.png)

**Tip:** Als je per ongeluk de **Sprite1** (Scratch kat) hebt verwijderd, kun je op **Kies een Sprite** klikken en zoeken naar `cat`.

--- /task ---

Op dit moment is de Scratch kat te groot om in de bus te passen.

--- task ---

Klik in het Sprite-venster op de **Grootte** en wijzig de grootte van de Scratch kat in `50`:

![](images/sprite-pane-size.png)

--- /task --- 

--- save ---
