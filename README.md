
# How_to_center_a_div

Ce projet démontre comment centrer un `div` à la fois verticalement et horizontalement dans un conteneur en utilisant Flexbox en CSS.

## Structure du projet

Le répertoire contient les fichiers suivants :
└── ananijoel-how_to_center_a_div/
    ├── index.html
    ├── style.css
    └── README.md

# Description du projet et instructions (ce fichier)
## Comment ça fonctionne

Le `div` nommé `wrapper` est centré à l'intérieur du `div` conteneur en utilisant Flexbox. Le conteneur occupe toute la fenêtre, et le `wrapper` est positionné au centre, aussi bien horizontalement que verticalement.

### Détails CSS :
- Le `container` utilise `display: flex`, avec `align-items: center` et `justify-content: center` pour centrer son contenu.
- Le `wrapper` a une taille fixe de `25%` de la hauteur et de la largeur de la fenêtre, une couleur de fond, des coins arrondis et une ombre subtile.

### Structure HTML :

```html
<!DOCTYPE html>
<html lang="fr">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Comment centrer un div</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="container">
		<div class="wrapper"></div>
	</div>
</body>
</html>
````

### Styles CSS :

```css
*{
	box-sizing: border-box;
	overflow: hidden;
}

body{
	height: 100vh;
	width: 100vw;
	background-color: #FEFCE9;
}

.container{
	width: 100%;
	height: 100%;
	display: flex;
	align-items: center;
	justify-content: center;
}

.wrapper{
	height: 25%;
	width: 25%;
	background-color: #FFE629;
	border-radius: 20px;
	box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}
```

## Comment exécuter

1. Clonez ou téléchargez ce répertoire.
2. Ouvrez le fichier `index.html` dans votre navigateur pour voir le `div` centré.