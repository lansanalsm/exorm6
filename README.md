### EXO RM6 

un projet de test de git et github

####Quelques commandes git : 


### Les branch GIT
1 - Affichage de la liste des branch y compris la branche courante


``` 
git branch
```

2- creer une nouvelle branch


```bash
git branch monTravail
```

3 - supprimer une branch


```bash
git branch -D  monTravail
```
NB: prudence avec cette commande


4 - changer de branch

```bash
git checkout monTravail
```

5 - creer une nouvelle branche et y se placer immediatement

```bash
 git checkout -b monTravail
```

### Commit et Push
1 -  pour cloner ce projet taper la commande suivante :

```bash
git clone https://github.com/lansanalsm/exorm6
```

2 -  pour afficher les changements qui n'ont pas ete commit

```bash
git status
``` 
3 - Pour ajouter tous les changements

```bash
git add .
``` 

4- Pour faire un commit, taper la commande suivante:

```bash
git commit -m "massange"
```

5- Pour faire un push 

```bash
git push origin [nom_de_la_branche]
```

### Envoyer un encien projet sur github

1-  se placer dans le dossier du projet

```bash
cd /chemin/vers/le/projet
```

2 - initialiser le projet (git)

```bash
git init
```

3- ajouter le repos git 

```bash
git remote add origin https://github.com/utilisateur/projet.git
```
NB: le repo `https://github.com/utilisateur/projet.git` doit etre créer

4 - puis envoyer le code sur le repo

```
    git add .
    git commit -m "initialisation"
    git push origin -u master
```