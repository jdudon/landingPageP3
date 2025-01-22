# landingPageP3

Bienvenue dans ce projet collaboratif ! Suivez ce guide pour travailler efficacement avec votre équipe en utilisant GitHub Desktop.

## 🚀 Structure du Projet
### 🗂 Arborescence des Fichiers
Votre projet est organisé de la manière suivante :
```html
/project-root
│
├── index.html         # La page d'accueil (Landing Page)
├── documentation.html # Une page dédiée à la documentation
├── style.css          # Fichier pour le style CSS
├── script.js          # Fichier pour les interactions JavaScript
├── /medias            # Dossiers d'images et vidéos utilisées
└── README.md          # Ce fichier d'instructions
```
- index.html : La page principale de votre site (landing page).
- documentation.html : Une page où vous expliquerez les fonctionnalités et la structure du projet.
- style.css : Le fichier contenant le style du projet. Toutes les couleurs, espacements, et bordures doivent être centralisés en utilisant des variables CSS.
- script.js : Le fichier pour ajouter des interactions dynamiques (ex. : événements au clic, animations).
### 📛 Nommage des Fichiers
Respectez les conventions suivantes pour nommer vos fichiers :

- Les noms doivent être en minuscules.
- Utilisez des Majuscules pour séparer les mots (ex. : pageAbout.html).
- Pas d'espaces ni de caractères spéciaux.
### 🎨 Instructions pour le CSS
Pour uniformiser le design, vous devez utiliser des variables CSS dans le fichier style.css. Voici un exemple :

```css
:root {
  /* Couleurs */
  --primary-color: #3498db;
  --secondary-color: #2ecc71;

  /* Bordures */
  --border-radius: 5px;

  /* Espacements */
  --padding: 10px;
  --margin: 15px;
}

/* Exemple d'utilisation */
button {
  background-color: var(--primary-color);
  border-radius: var(--border-radius);
  padding: var(--padding);
  margin: var(--margin);
}
```
💡 **À faire** : Définissez vos propres variables pour correspondre au design que vous choisissez.

## 🌿 Collaboration avec GitHub Desktop
![image](/readmeImg.webp)
### 🛠 Étapes pour Travailler en Équipe
1. Clonez le dépôt depuis GitHub Desktop :

    - Ouvrez GitHub Desktop.
    - Cliquez sur File > Clone Repository... et sélectionnez votre projet.
2. Créez une branche pour votre travail :

    - Allez dans Branch > New Branch....
    - Donnez à votre branche un nom clair, basé sur la tâche que vous faites, par exemple :
    - feature/navbar-alice
    - fix/footer-bob
3. Travaillez sur votre branche :

    - Modifiez les fichiers directement sur votre machine.
    - Sauvegardez régulièrement vos modifications avec un commit.
4. Faites un commit :

    - Dans GitHub Desktop, allez dans l'onglet Changes.
    - Vérifiez les fichiers modifiés.
    - Ajoutez un message clair dans le champ "Summary" (ex. : "Ajout du menu de navigation").
    - Cliquez sur Commit to [nom-de-votre-branche].
5. Poussez vos modifications :

    - Cliquez sur Push Origin pour envoyer vos modifications sur GitHub.
6. Ouvrez une Pull Request (Merge Request) :

    - Sur GitHub Desktop, cliquez sur Branch > Create Pull Request.
    - Donnez un titre clair à votre Pull Request et cliquez sur Create Pull Request.

#### 🔄 Fusions Quotidiennes
- **Chacun doit fusionner sa branche dans main au moins 2 fois par jour.**
- Avant de fusionner :
    - Vérifiez que tout fonctionne bien sur votre branche.
    - Poussez vos modifications avec Push Origin.

💡 **Astuce**: Si d'autres membres de l'équipe ont fusionné avant vous, mettez à jour votre branche avec leurs changements :

- Cliquez sur Fetch Origin dans GitHub Desktop.
- Résolvez les conflits si nécessaire.

💡 **Illustration des Étapes**
1. Cloner le projet :

    Cliquez sur File > Clone Repository... et choisissez votre projet GitHub.
2. Créer une branche :

    Dans GitHub Desktop : Branch > New Branch....
    Exemple : feature/navbar.
3. Faire un commit :

Cliquez sur l’onglet Changes, ajoutez un message de commit, puis cliquez sur Commit to [branche].
4. Créer une Pull Request :

Allez dans Branch > Create Pull Request.
Une fois la Pull Request créée, **attendez qu’elle soit fusionnée dans main**.

#### 📋 Checklist pour chaque élève
 [] Créer une branche.
 [] Travailler sur une fonctionnalité.
 [] Faire un commit avec un message clair.
 [] Pousser vos modifications.
 [] Créer une Pull Request pour fusionner dans main.