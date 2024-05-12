# Cactus 5 - Material Icon Pack

## Nouveau Pack d'Icônes Matérielles pour Cactus 5.

### Qu'est-ce que Cactus ?
Cactus 5 est une extension open source pour le jeu de gestion d'entreprise en ligne **My-Industry**.
*Version actuelle de Cactus : **v1.20.25** *

### Qu'Apporte ce Nouveau Pack d'Icônes ?
1. Ce nouveau pack d'icônes enrichit les icônes déjà présentes sur le site de Cactus.
2. Les icônes contenues dans ce nouveau pack sont enregistrées au format SVG, ce qui permet une utilisation moins lourde (vitesse de téléchargement plus rapide) ainsi qu'un rendu de meilleure qualité (rendu vectoriel).

### Comment Utiliser les Icônes Issues du Material UI Icon Pack ?
Pour utiliser les nouvelles icônes matérielles de Cactus 5, plusieurs options sont disponibles.

#### 1. L'Inclusion "Brute" :
Vous pouvez choisir d'inclure l'icône de manière "brute" dans le code HTML de la page, en incluant le code SVG de l'icône.
*Exemple : *
```html
<div class="ui-material-icon">
    <svg height="100%" stroke-miterlimit="10">...</svg>
</div>
```

*Vous pouvez aussi passer par une inclusion PHP (plus esthétique dans le code) : *
```html
<div class="ui-material-icon">
    <?php include 'material-icon-pack/1.0.0/p_machine_a_recycler.svg' ?>
</div>
```

#### 2. L'Inclusion via la Balise `<img>` :
Vous pouvez choisir d'inclure l'icône comme une image PNG/JPG/etc...
*Exemple : *
```html
<img class="ui-material-icon" src="material-icon-pack/1.0.0/p_machine_a_recycler.svg" width="48" alt="..." />
```

*Vous pouvez aussi passer par une inclusion PHP (en cas de pré-traitement de la page côté serveur) : *
```html
<img class="ui-material-icon" src="<?php echo 'material-icon-pack/1.0.0/p_machine_a_recycler.svg' ?>" width="48" alt="..." />
```

#### 3. Utilisation des Icônes Comme une Web Font :
*Fonctionnalité à Venir...*