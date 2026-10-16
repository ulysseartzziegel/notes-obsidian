--------------------------------------------------

1. CRÉATION

--------------------------------------------------

1. Se connecter sur https://github.com

2. En haut à droite, cliquer sur le "+" puis sur "New repository".

--------------------------------------------------

2. CONFIGURATION

--------------------------------------------------

- Nom du dépôt : Entrer le nom du projet.

- Visibilité : Choisir "Public" 

- Initialisation : Cocher "Add a README file" 
--------------------------------------------------

3. VALIDATION ET COMMANDES

--------------------------------------------------

Cliquer sur "Create repository".

Pour utiliser le dépôt sur l'ordinateur (via terminal) :

* Récupérer un dépôt vide :

git clone https://github.com/ulysseartzziegel/ulysseaz2.git

* Lier un dossier existant :

git init

git add .

git commit -m "commit"

git remote add origin https://github.com/ulysseartzziegel/ulysseaz2.git

git push -u origin main