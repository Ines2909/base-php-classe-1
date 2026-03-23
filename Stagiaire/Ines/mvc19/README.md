# Exercice MVC | mvc -19

## Marche à suivre préparation TI1

### Phase 1

1) On part de votre ordinateur
- Création d'un dossier sur votre ordinateur : `git init`
- Création d'un `repositoriy` sur `github` : `git remote add origin KEY@SSH`

#### Ou

2) On part de `github`
- On créer un `fork` du `repository` "**upstream**" sur `github`
- On clone le `fork` du `repository` depuis `github` (Utilisation de `SSH` de préférence) sur votre ordinateur mais **pas  dans un projet existant ni un endroit suivi par une synchronisation(OneDrive,Dropbox, ICloud etc..., )** 

#### Ensuite

- Ajout de l'upstream (pour le `pull request` final): `git remote add upstream KEY@SSH`
- Création du `.gitignore` vide (**!Important**)
- Dossiers vide ? `.gitkeep`
- Informer sur le projet ? `README.md`

### Phase 2

Création des dossiers important du site pour le MVC (Model View Controller)
- `public` Dossier accessible à tous (**Frontend**)
- `model` Il gère l'accès aux données (**Backend**)
- `view` Dossier contenant les vues (templates **Backend**)
- `controller` Dossier qui gère le lien entre la `view` et les `model` (Entre **Backend** et  **Middle-end**)
- `datas` - nos fichiers de préparation du travail