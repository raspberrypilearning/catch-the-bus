## Créer ta scène de bus

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Tu choisiras un arrière-plan et ajouteras un sprite de bus.
</div>
<div>

![Le City Bus sur le fond de l'école.](images/bus-scene.png){:width="300px"}

</div>
</div>

### Ouvrir le projet de démarrage

--- task ---

Ouvre le [projet de démarrage Prendre le bus ](https://scratch.mit.edu/projects/582214330/editor){:target="_blank"}. Scratch s'ouvrira dans un autre onglet du navigateur.

[[[working-offline]]]

--- /task ---

### Choisir un arrière-plan

--- task ---

Clique (ou sur une tablette, appuie) sur **Choisir un arrière-plan** dans le volet Scène (en bas à droite de l'écran) :

![Une capture d'écran de l'icône Choisir un arrière-plan.](images/choose-a-backdrop.png)

--- /task ---

--- task ---

Clique sur la catégorie **Outdoors**. Ajoute un arrière-plan qui constitue un bon point de départ pour ton bus :

![La scène avec l'arrière plan de l'école.](images/outdoor-backdrop.png)

--- /task ---

### Choisir un sprite

--- task ---

Clique sur **Choisir un Sprite**:

![Une capture d'écran du menu Choisir un sprite.](images/choose-sprite-menu.png)

--- /task ---

--- task ---

Tape `bus` dans la zone de recherche en haut :

![Le champ de recherche mis en surbrillance dans la bibliothèque de sprites.](images/bus-search.png)

Ajoute le sprite **City Bus** à ton projet.

--- /task ---

### Définir une position de départ à ton bus

--- task ---

Assure-toi que le sprite **City Bus** est sélectionné dans la liste Sprite sous la scène.

Fais glisser un bloc `quand le drapeau vert est cliqué`{:class="block3events"} du menu bloc `Événements`{:class="block3events"} vers la zone Code :

![Le sprite City Bus.](images/bus-sprite.png)

```blocks3
when flag clicked
```

--- /task ---

--- task ---

Fais glisser le bus vers une bonne position sur la scène :

![Le bus en bas au milieu de la scène.](images/bus-bottom-middle.png)

Les coordonnées **x** et **y** (les nombres utilisés pour décrire la position) du bus sont affichées dans le panneau Sprite sous la scène :

![Une capture d'écran mettant en évidence l'emplacement des coordonnées dans le panneau sprite.](images/coords-sprite-pane.png)

--- /task ---

--- task ---

Ajoute un bloc `aller à x: y:`{:class="block3motion"} :

![Le sprite City Bus.](images/bus-sprite.png)

```blocks3
when flag clicked
+go to x: (0) y: (-100)
```

Les nombres dans le bloc `aller à x : y :`{:class="block3motion"} sont les coordonnées x et y actuelles du bus. Les chiffres de ton projet peuvent être un peu différents.

--- /task ---

--- task ---

**Test :** Fais glisser le bus n'importe où sur la scène, puis clique sur le drapeau vert. Le bus doit toujours aller à sa position de départ.

![Animation montrant le bus glissé sur l'écran et revenant au centre lorsque le drapeau vert est cliqué.](images/drag-bus.gif)

--- /task ---

### Déplacer le bus derrière les sprites des personnages

--- task ---

Pour t'assurer que le sprite **City Bus** est toujours derrière tous les sprites des personnages, ajoute un bloc `aller à l'avant plan`{:class="block3looks"}, puis clique sur `avant`{:class="block3looks"} et change-le en `arrière`{:class="block3looks"} :

![Le sprite City Bus.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
+ go to [back v] layer
```

**Astuce :** Si tu ne peux pas voir le bloc `aller à l'avant plan`{:class="block3looks"}, tu dois faire défiler les blocs du menu `Apparence`{:class="block3looks"}.

--- /task ---

### Modifier la couleur du bus

--- task ---

Tu peux modifier la couleur du bus :

![Le sprite City Bus.](images/bus-sprite.png)

```blocks3
when flag clicked
go to x: (0) y: (-100)
go to [back v] layer
+set [color v] effect to (50) // try numbers up to 200
```

--- /task ---

### Redimensionner le chat Scratch

--- task ---

Le chat Scratch apparaît dans tous les nouveaux projets Scratch en tant que **Sprite1** dans la liste des Sprites. Clique sur le sprite **Sprite1** dans la liste Sprite pour te préparer à animer le chat Scratch :

![Le sprite Sprite1 sélectionné dans la liste Sprite.](images/sprite1-selected.png)

**Astuce :** Si tu as accidentellement supprimé le sprite **Sprite1** (le chat Scratch), tu peux cliquer sur l'icône **Choisir un Sprite** et rechercher `cat`.

--- /task ---

--- task ---

Dans le panneau Sprite, clique sur la propriété **taille** et modifie la taille du chat Scratch à `50` :

![Une capture d'écran mettant en évidence l'emplacement de la propriété taille dans le panneau Sprite.](images/sprite-pane-size.png)

--- /task --- 
