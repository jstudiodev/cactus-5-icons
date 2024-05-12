# Cactus 5 - Material Icon Pack

## Nouveau Pack d'Icônes Matérielles pour Cactus 5.

### Qu'est-ce que Cactus ?
Cactus 5 est une extension open source pour le jeu de gestion d'entreprise en ligne **My-Industry**.
_Version actuelle de Cactus : **v1.20.25**_

### Qu'apporte ce nouveau pack d'icônes ?
1. Ce nouveau pack d'icônes enrichit les icônes déjà présentes sur le site de Cactus.
2. Les icônes contenues dans ce nouveau pack sont enregistrées au format SVG, ce qui permet une utilisation moins lourde (vitesse de téléchargement plus rapide) ainsi qu'un rendu de meilleure qualité (rendu vectoriel).

### Comment Utiliser les icônes issues du Material UI Icon Pack ?
Pour utiliser les nouvelles icônes matérielles de Cactus 5, plusieurs options sont disponibles.

#### 1. L'inclusion "brute" :
Vous pouvez choisir d'inclure l'icône de manière "brute" dans le code HTML de la page, en incluant le code SVG de l'icône.
_Exemple :_
```html
<div class="ui-material-icon">
    <svg height="100%" stroke-miterlimit="10">...</svg>
</div>
```

_Vous pouvez aussi passer par une inclusion PHP (plus esthétique dans le code) :_
```html
<div class="ui-material-icon">
    <?php include 'material-icon-pack/1.0.0/p_machine_a_recycler.svg' ?>
</div>
```

#### 2. L'Inclusion via la balise `<img>` :
Vous pouvez choisir d'inclure l'icône comme une image PNG/JPG/etc...
_Exemple :_
```html
<img class="ui-material-icon" src="material-icon-pack/1.0.0/p_machine_a_recycler.svg" width="48" alt="..." />
```

_Vous pouvez aussi passer par une inclusion PHP (en cas de pré-traitement de la page côté serveur) :_
```html
<img class="ui-material-icon" src="<?php echo 'material-icon-pack/1.0.0/p_machine_a_recycler.svg' ?>" width="48" alt="..." />
```

#### 3. Utilisation des icônes comme une Web Font :
_Fonctionnalité à venir..._

**© 2024 - Cactus 5, Tous droits reservés.** Toute utilisation sans accord de **Cactus** des fichiers contenus dans ce répertoire est interdite.
