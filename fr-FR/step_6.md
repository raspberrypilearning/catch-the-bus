## Rater le bus

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Et si le chat Scratch ne courait pas assez vite pour prendre le bus ?
</div>
<div>

![Le chat Scratch ratant le bus.](images/cat-misses-bus.png){:width="300px"}

</div>
</div>

### Faire rater le bus au chat Scratch

--- task ---

Sélectionne le sprite **chat Scratch** et ajoute un bloc `attendre`{:class="block3control"} :

![Le sprite chat Scratch.](images/scratch-cat-sprite.png)

```blocks3
when flag clicked
go to x:(200) y:(-150) 
show
repeat (20) // essaye différents nombres
move (5) steps 
next costume 
+ wait (1) seconds
end
hide
```
--- /task ---

--- task ---

**Test :** Clique sur le drapeau vert. Le chat Scratch marchera trop lentement et ratera le bus !

--- /task ---

### Faire en sorte que le chat Scratch prenne le bus

--- task ---

Il te faudra des délais de moins d'une seconde. 0,5 correspond à une demi-seconde, 0,25 à un quart de seconde et 0,1 à un dixième de seconde.

Modifie le délai dans le bloc`attendre`{:class="block3control"} :

![Le sprite chat Scratch.](images/scratch-cat-sprite.png)

```blocks3
wait (0.2) seconds // essaye 0.1, 0.5, 0.05
```

**Test :** Clique sur le drapeau vert, et le chat Scratch marchera plus vite. Choisis le délai que tu aimes le plus.

--- /task ---

### Choisir si le chat Scratch prend ou rate le bus

--- task ---

Si tu veux que le chat Scratch **rate le bus**, supprime le bloc `cacher`{:class="block3looks"} de ton code afin que le chat Scratch reste sur la scène :

![Fais glisser le bloc "masquer" du script dans la zone Code vers le menu Blocs pour supprimer le bloc du script.](images/removing-blocks-at-script-ends.gif)

![Le sprite chat Scratch.](images/scratch-cat-sprite.png)

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

Si tu veux que le chat Scratch **prenne le bus**, fais attendre le bus plus longtemps avant qu'il ne parte :

![Le sprite City Bus.](images/bus-sprite.png)

```blocks3
when flag clicked 
+wait [4] seconds // passer de 4 à 6
glide [2] secs to x: [320] y: [-100] // côté droit de la scène
hide
```

Tu devras remettre le bloc `cacher`{:class="block3looks"} dans le sprite **chat Scratch** si tu l'as supprimé et que tu souhaites que le chat Scratch réussi à prendre le bus.

--- /task ---

--- task ---

Apporte des modifications jusqu'à ce que l'animation fonctionne comme tu le souhaites.

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Lorsque tu travailles sur un projet, tu reviens souvent en arrière pour modifier ou améliorer ton code à mesure que tu as de nouvelles idées. 
</p>



