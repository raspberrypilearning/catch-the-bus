## Le bus part

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Un groupe de blocs connectés dans Scratch s'appelle un **script**. Tu vas ajouter un nouveau script pour faire démarrer le bus.
</div>
<div>

![La scène montrant que le bus s'est déplacé vers la droite.](images/bus-leaving.png){:width="300px"}

</div>
</div>

Le bus partira vers la droite quatre secondes après avoir cliqué sur le drapeau vert. Le bloc `quand le chronomètre`{:class="block3events"} exécutera les blocs en dessous après ce délai.

--- task ---

Sélectionne le sprite **City Bus**.

![Le sprite du City Bus.](images/bus-sprite.png)

--- /task ---

--- task ---

Dans le menu bloc `événements`{:class="block3events"}, fais glisser un bloc `quand le volume sonore >`{:class="block3events"} `10` vers la zone Code. Change `volume`{:class="block3events"} en `chronomètre`{:class="block3events"}. Cela lancera un nouveau script :

![Le sprite du City Bus.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] // change 10 to 4
```

--- /task ---

--- task ---

Fais glisser ton bus vers le côté droit de la scène. Ce sera la position `x`{:class="block3motion"} et `y`{:class="block3motion"} vers laquelle le bus glissera ``{:class="block3motion"}.

![](images/bus-right.png)

**Astuce :** Si tu déplaces le bus trop vers la droite, il reculera. Essaye à nouveau, mais ne le déplace pas si loin.

--- /task ---

--- task ---

Ajoute un bloc `glisser`{:class="block3motion"} `2` `secs à x: y:`{:class="block3motion"} sous le bloc `quand le chronomètre`{:class="block3events"}.

Les coordonnées `x`{:class="block3motion"} et `y`{:class="block3motion"} dans ton projet peuvent être un peu différentes.

![Le sprite du City Bus.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
+glide [2] secs to x: [320] y: [-100] // right-hand side of the Stage
```

--- /task ---

--- task ---

**Test :** Clique sur le drapeau vert. Le chat Scratch et l'hippopotame se déplaceront vers le bus, et le bus partira à droite après quatre secondes.

--- /task ---

--- task ---

Ajoute un bloc `cacher`{:class="block3looks"} pour donner l'impression que le bus quitte la scène :

![Le sprite du City Bus.](images/bus-sprite.png)

```blocks3
when [timer v] > [4] 
glide [2] secs to x: [320] y: [-100]
+ hide
```
--- /task ---

--- task ---

**Test :** Clique sur le drapeau vert. Le bus va maintenant sera caché après avoir démarré. Tu te souviens comment faire en sorte qu'un sprite réapparaisse lorsque tu cliques sur le drapeau vert ?

--- /task ---

--- task ---

Ajoute un bloc `montrer`{:class="block3looks"} à ton script `quand le drapeau vert est cliqué`{:class="block3events"} pour faire apparaître le bus lorsque tu exécutes ton projet :

![Le sprite du City Bus.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
set [color v] effect to (50) // try numbers up to 200
+show
```

--- /task ---

--- task ---

**Test :** Clique sur le drapeau vert et regarde ton animation. Le bus devrait apparaître au centre de la scène, puis repartir vers la droite et disparaître.

Est-ce que tout le monde est dans le bus quand il part ? Tu peux modifier le temps d'attente du bus, si nécessaire.

--- /task ---

--- save ---
