# Git

- **`git config --global`** : *Modifier la configauration globale*
- **`git init`** : *Intialiser GIT*
- **`git status`** : *Voir l'état des fichier du working tree*
- **`git log`** : *Voir l'historique (commits)*
- **`git add`** : *Ajouter des fichiers dans le staging*
- **`git commit -m "message"`** : *Créer un « point de sauvegarde » avec un message dans l'historique*
- **`git rm --cached`** : *Retirer un/des fichier(s) du staging*
- **`git checkout`** : *Naviguer entre les branches/commits/tags*
- **`git revert`** : *Créer des commmits inverses pour revenir en arrière*
- **`git stash`** : *Créer un brouillon*
- **`git stash apply`** : *Appliquer le brouillon*
- **`git stash pop`** : *Appliquer le brouillon et le retirer de la liste de brouillons*

## Modification de l'historique (Attention à ne faire que si l'historique n'a pas encore été synchronisé avec le remote)

- **`git reset --hard`** : *Effacer les changements ds l'historique et working tree*
- **`git reset --soft`** : *Effacer les changements ds l'historique et mais conserver les changements ds le working tree*

### Rebase squash
- **`git rebase -i`** : *Permet de écraser des commits sur un autre commit*

### Remote
- **`git remote add origin urlDuRemote`** : *Permet de créer un lien vers un remote distant*
- **`git push origin --all`** : *Synchroniser depuis local vers remote*
- **`git clone`**: *Cloner un projet situé sur un remote*
- **`git fetch`**: *Rapatrie les derniers changements du serveur sans modifier le working tree*
- **`git pull`**: *git fetch + git merge*

### Branches
- **`git branch`**: *Voir les branches (la branche marquée avec * c'est la branche courante)*
- **`git branch nouvelleBranche`**: *Créer une branche*
- **`git checkout -b nouvelleBranche`**: *Créer une branche + checkout sur branche*
- **`git branch -d brancheASupprimer`**: *Supprimer une branche*