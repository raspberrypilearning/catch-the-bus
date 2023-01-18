## De bus vertrekt

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Voeg meer blokken toe om de bus weg te laten rijden.
</div>
<div>

![Het speelveld laat zien dat de bus naar rechts is verplaatst.](images/bus-leaving.png){:width="300px"}

</div>
</div>

### Animeer de bus

--- task ---

Selecteer de **City Bus** sprite.

![De City Bus sprite.](images/bus-sprite.png)

--- /task ---

--- task ---

Voeg code toe om de bus vier seconden nadat op de groene vlag is geklikt naar rechts te laten rijden.

![De City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // verander 1 naar 4
```

--- /task ---

--- task ---

Sleep je bus naar de rechterkant van het speelveld. Dit wordt de `x`{:class="block3motion"} en `y`{:class="block3motion"} positie van de bus waarnaar deze moet `schuiven`{:class="block3motion"}.

![](images/bus-right.png)

**Tip:** Als je de bus te ver naar rechts beweegt, springt hij terug. Probeer het opnieuw, maar verplaats hem niet te ver.

--- /task ---

--- task ---

Voeg een `schuif in`{:class="block3motion"} `2` `sec. naar x: y:`{:class="block3motion"} blok toe onder het `wacht`{:class="block3events"} blok.

De `x`{:class="block3motion"} en `y`{:class="block3motion"} in jouw project kunnen een beetje anders zijn dan exacte positie waar je de bus naar toe hebt gesleept.

![De City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // verander 1 naar 4
+glide [2] secs to x: [320] y: [-100] // rechterkant van het speelveld
```

--- /task ---

--- task ---

**Test:** Klik op de groene vlag. De Scratch kat en het nijlpaard gaan naar de bus, en de bus rijdt na vier seconden naar rechts.

--- /task ---

### Laat de bus verdwijnen en verschijnen

--- task ---

Voeg een `verdwijn`{:class="block3looks"} blok toe om de bus van het speelveld te laten verdwijnen:

![De City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked 
wait [4] seconds // verander 1 naar 4
glide [2] secs to x: [320] y: [-100]
+ hide
```
--- /task ---

--- task ---

**Test:** Klik op de groene vlag. De bus zal zich nu na het wegrijden verbergen. Weet je nog hoe je ervoor kunt zorgen dat een sprite weer verschijnt als je op de groene vlag klikt?

--- /task ---

--- task ---

Voeg een `verschijn`{:class="block3looks"}-blok toe aan je `wanneer op de groen vlag wordt geklikt`{:class="block3events"} script om de bus te laten verschijnen wanneer je jouw project uitvoert:

![De City Bus sprite.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
set [color v] effect to (85) // probeer getallen tot 200
+show
```

--- /task ---

--- task ---

**Test:** Klik op de groene vlag en bekijk je animatie. De bus moet in het midden van het speelveld verschijnen en dan naar rechts rijden en verdwijnen.

Zit iedereen in de bus als deze vertrekt? Indien nodig kun je de tijd dat de bus wacht wijzigen.

--- /task ---
