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

## Modification de l'historique (Attention à ne faire que si l'historique n'a pas encore été synchronisé avec le remote)

- **`git reset --hard`** : *Effacer les changements ds l'historique et working tree*
- **`git reset --soft`** : *Effacer les changements ds l'historique et mais conserver les changements ds le working tree*