# Étape 1 - Créer le repo sur Github, puis le cloner

Allez dans repositories copier le lien SSH, et le cloner dans le terminal de notre machine.

## Étape 2 - Supprimer le dossier .git/

Une fois le projet cloné sur votre machine, on se rend dans le dossier (avec le Terminal Git Bash de préférence). Dans le dossier du projet on va complètement supprimer (toujours avec le terminal) le dossier .git/. C'est un dossier cacher on va donc utiliser la commande "ls -a3 pour le trouver, puis ensuite pour supprimer le dossier ".git/" on utilise la commande "rm -r" .

### Étape 3 - Créer le second repo

On commence par se rendre sur la page des repositories de l'orga puis vous allez créer un nouveau repo que vous allez nommer S01E14-atelier-github-votrepseudo-solution.Cette fois-ci on ne coche pas la case Add a README file puisque le fichier existe déjà dans le dossier du projet.

### Étape 4 - Relier le nouveau repo Github au projet local

On retourne donc sur son terminal, en faisant évidemment attention de bien se placer dans le dossier de notre projet.

Puis on effectue les commandes indiquées (comme ci-dessous), en remplaçant bien sûr le lien SSH par celui de votre propre repo.

Une fois dans le dossier du projet :

* git init
* git add README.md
* git commit -m "first commit"
* git remote add origin git@github.com:O-clock-DWA-Session1/test-charly.git (à remplacer par votre lien SSH)
git push -u origin master

Et voilà, le dossier du projet devrait être bien relié à votre nouveau repo sur Github.

### Eape6 - SAUVEGARDER LE TOUT SUR GITHUB. 

Commande a rentrer dans le terminal : 
* git add
* git commit -m "initiation"
* git push
