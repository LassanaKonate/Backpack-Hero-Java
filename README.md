# Backpack Hero - Jeu d'aventure en Java

Ce projet a été réalisé dans le cadre de la Licence 3 Informatique à l'**Université Gustave Eiffel**. Il s'agit d'un jeu d'aventure où le joueur explore des donjons et combat des monstres en gérant l'organisation de son sac à dos.

## 🛠️ Caractéristiques Techniques
* **Architecture :** Utilisation du modèle **MVC** pour structurer le projet.
* **Interface Graphique :** Réalisée avec la librairie **Zen**.
* **Moteur de Combat :** Gestion du tour par tour, de l'énergie et des effets de statut.
* **Génération de Niveaux :** Système automatique garantissant l'accessibilité des salles.
* **Persistance :** Mise en place d'un **Hall of Fame** avec sauvegarde des trois meilleurs scores.

---

## 📖 Manuel de l'Utilisateur

### 1. Comment lancer le jeu
1. Ouvrez un terminal dans le dossier du jeu.
2. Tapez la commande suivante : `java -jar BackpackHero.jar`
3. La fenêtre du jeu s'ouvre automatiquement.

### 2. Explorer le Donjon
Dirigez votre héros sur une grille pour trouver la sortie de chaque étage.
* **Se déplacer :** Utilisez les touches **Z, Q, S, D** ou cliquez directement sur une salle voisine à la souris.
* **Types de salles :**
    * **Combat :** Contient des monstres.
    * **Trésor :** Contient des coffres d'équipement.
    * **Marchand :** Pour échanger votre or contre du matériel.
    * **Guérisseur :** Pour soigner vos blessures contre quelques pièces.
    * **Sortie :** Indispensable pour passer au niveau suivant.

### 3. Organiser ton Sac à Dos
Le rangement est la clé du succès !
* **Poser un objet :** Cliquez sur une case vide du sac.
* **Rotation :** Appuyez sur **R** pour faire pivoter un objet.
* **Valider :** Appuyez sur **A** pour confirmer un choix.
* **Tout ranger :** Appuyez sur **O** pour vider le sac et tout replacer.
* **Statistiques :** Appuyez sur **I** pour voir l'état du sac dans la console.

### 4. Le Combat
* **Attaquer :** Cliquez sur une arme dans votre sac.
* **Cibler :** Cliquez sur un ennemi pour voir ses points de vie.
* **Fin de tour :** Cliquez sur le bouton rouge "Fin de Tour" quand votre énergie est épuisée.

### 5. Records (Hall of Fame)
À la fin de la partie, si votre score est suffisant, vous intégrerez le tableau des records.
