# Double Pendule

Simulation interactive d'un double pendule, en un seul fichier HTML, qui tourne directement dans le navigateur.

## ▶️ [Ouvrir la simulation](https://jdv38.github.io/double-pendule/)

Lien direct : https://jdv38.github.io/double-pendule/

## Le principe

Un double pendule, c'est un pendule accroché au bout d'un autre pendule. Malgré sa simplicité, c'est l'un des exemples les plus connus de **système chaotique** : une différence minuscule dans les angles de départ suffit pour obtenir, au bout de quelques secondes, des trajectoires complètement différentes.

Les équations du mouvement sont intégrées numériquement avec la méthode de Runge-Kutta d'ordre 4 (RK4), et l'animation est rendue en temps réel dans un canvas.

## Fonctionnalités

- **Physique réglable** : gravité, frottement, longueurs et masses des deux bras, vitesse du temps.
- **Préréglages** : Calme, Chaotique, Forte friction, Masse lourde, Temps rapide.
- **Trace de la trajectoire** : dégradé, couleur fixe, couleur selon la vitesse ou arc-en-ciel, pour une masse ou les deux.
- **Graphique d'énergie** : énergie potentielle, cinétique et totale au fil du temps. Sans frottement, le total reste à peu près constant ; avec frottement, il diminue.
- **Espace des phases** : tracé de θ₂ en fonction de θ₁ pour distinguer un mouvement régulier du chaos.
- **Export et partage** : image PNG ou SVG, copie de l'image, lien de partage, sauvegarde des réglages.
- Interface en français et en anglais.

## Utilisation

| Action | Effet |
|---|---|
| Glisser une masse | Choisir les angles de départ |
| Glisser le fond | Déplacer la vue |
| Molette | Zoomer |
| Double-clic | Recentrer |
| `Espace` | Lancer / mettre en pause |
| `R` | Remettre la pose de départ |
| `C` | Effacer la trace |
| `F` | Plein écran |
| `P` | Afficher / masquer le panneau |
| `H` | Aide |

## Lancer en local

Aucune installation n'est nécessaire : téléchargez `index.html` et ouvrez-le dans un navigateur.
