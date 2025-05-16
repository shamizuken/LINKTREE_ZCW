**Sarah's Linktree** 👩🏻‍💻

Ce LinkTree personnalisé à été développé dans le cadre de mon cours de ZCW.

## Aperçu. 🖥️
![APERCU](https://github.com/user-attachments/assets/ada7c886-5dca-4cf8-ac29-8a3522d838ca)

J'y ai mis : 
- Une vidéo que Mel aime bien (parce que j'avais pas d'autres idées).
- Une de mes chansons préférées.
- Une listes des animes que je regarde.
- Mes profils sur Github, Letterboxd et Goodreads.

## Objectifs et exigences du projet. 🎯

- Créer un Linktree uniquement en HTML et CSS.
- Respecter le principe Mobile First.
- Interface responsive sans scrolling.
- Respecter les balises sémantiques.
  
Intégrer :
- 1 image de profil,
- 1 titre,
- 1 sous-titre,
- 3 boutons de lien,
- 3 icônes,
- 1 footer,
- Ajouter 3 animations CSS.
  
## Technologies utilisées. 🤖

- HTML.
- CSS.
- ChatGPT comme aide.

## Structure des fichiers. 🗂️
```bash

├── index.html               # Structure HTML du LinkTree
├── style.css                # Feuille de style principale
├── akira.jpg                # Image de profil
├── github.png               # Logo GitHub
├── goodreads.png            # Logo Goodreads
├── letterboxd.png           # Logo Letterboxd

```

## Aperçu de mon CSS. 💫

Dans mon CSS, il y a : 
- Des dégradés animés et un effet d'étoile dynamique.
- Des animations de survols et un effet de fade-in.
- Un design responsive.
- Un effet de sway sur la photo de profil.

  Extrait de mon code :
  ```css

  body {
  background: radial-gradient(circle, rgba(55, 11, 34, 1) 0%, rgba(74, 0, 85, 1) 35%, rgba(159, 45, 98, 1) 70%, rgba(106, 27, 77, 1) 100%);
  background-size: 400% 400%;
  animation: gradientAnimation 20s ease infinite, starryBackground 1s linear infinite;
  }
  ...
  
```

```
## Déploiement. 🔗

Voir mon projet : https://shamizuken.github.io/LINKTREE_ZCW/
