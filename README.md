Démineur 
Jeu de Démineur avec interface graphique, développé en Python avec PyQt5. Le joueur choisit une taille de grille, révèle des cases et place des drapeaux afin de repérer les bombes.
Fonctionnalités
- Trois niveaux : 5 × 5, 15 × 15 et 30 × 30 cases.
- Bombes réparties aléatoirement à la création de chaque grille (environ 20 % des cases).
- Calcul du nombre de bombes autour de chaque case.
- Clic gauche : révéler une case ; sur une case marquée, retirer le drapeau selon le comportement actuel du code.
- Clic droit : placer ou retirer un drapeau.
- Révélation automatique des cases sûres voisines lorsqu'une case de valeur zéro est ouverte.
- Chronomètre avec bouton de pause/reprise.
- Bouton Recommencer et dialogue proposant de rejouer en fin de partie.
Prérequis
- Python 3 (version compatible avec les bibliothèques installées).
- Bibliothèques : PyQt5, numpy, pandas.
