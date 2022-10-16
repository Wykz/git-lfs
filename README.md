# git-lfs

Bonjour à tous, aujourd'hui je vais vous montrer comment upload un fichier de plus de 100 mb sur github.

Tout d'abord il faut savoir que quand vous essayez d'upload un fichier qui fait + de 25Mb sur github version web, une erreur surviendra et vous devrez passez sur GitHub Desktop.

Si vous êtes passé par GitHub Desktop et qu'il vous est impossible d'upload un fichier de 100Mb, ce repo est fait pour vous.


## Première étape

Il vous faudra d'abord installer Git:

Version Windows: [Git For Windows](https://gitforwindows.org/)
Version MacOS: [Git for MacOS](https://git-scm.com/download/mac)
Version Linux: [Git for Linux](https://git-scm.com/download/linux)


Et enfin il vous faudra installer [Git LFS](https://github.com/git-lfs/git-lfs/releases/tag/v3.2.0).

## Deuxième étape

Une fois ceci fait, cloner ou créer votre repo avec GitHub Desktop

![image](https://zupimages.net/up/22/41/jgfx.png)

et mettez votre fichier qui fait + de 100Mb dans le dossier du repo.

## Troisième étape

Une fois ceci fait, lancer Git dans le dossier du repo et tapez:

``git lfs install``

ensuite ``git lfs track '*.votre extension de fichier'`` (remplacez le ``votre extension de fichier`` par l'extension de votre fichier ex: zip, exe)

puis ``git lfs push --all origin main`` (remplacez le ``main`` par la branche ou vous voulez upload votre fichier)

et enfin ``git push -u origin main`` (remplacez le ``main`` par la branche ou vous voulez upload votre fichier).

Ensuite vous pouvez appuyer sur ``Commit to``:

![image1](https://zupimages.net/up/22/41/61uf.png)

et vous pouvez enfin appuyer sur ``Push origin``:

![push](https://zupimages.net/up/22/41/1me2.png)

Et il vous faut juste attendre que le fichier s'upload et le tour est joué !

N'oubliez pas de mettre une étoile à ce repo si cela vous a plu.
