# TP - travail en équipe

## Introduction

### Prérequis

Chaque élève doit avoir créé un compte sur `https://github.com/`

### Groupes et rôles

L'exercice est à réaliser en groupes **de 3 à 4 élèves** (ça peut être plus, mais pas moins de 3)  
Chaque groupe a **un meneur identifié**; le meneur est le joueur #1  
les autres membres du groupe s'attribuent avant de commencer un numéro 2, 3, ou 4.

### Critères

pour l'évaluation de votre travail on tiendra compte entre autres 

* de la **propreté du dépôt obtenu**; ce qui nous intéresse quand on construit un dépôt, ce n'est pas seulement d'arriver avec le bon fichier à la fin, mais aussi que l'**histoire** que retracent les commits soit **conforme** à ce qui est demandé
* du **respect des consignes**; par exemple si vous n'utilisez pas le nom de dépôt préconisé, ou un autre fichier de départ, vous partez avec un  handicap…

## Étape 1  - création du dépôt sur github - (à faire par le meneur)

### Résultat attendu :

* le meneur crée un dépôt sur github, sous le nom `git-teamwork`,  
  c'est-à-dire donc en pratique sous un nom comme `https://github.com/lemeneur/git-teamwork`
* ce dépôt contient un seul commit avec un seul fichier `README.md`, dont le contenu est **produit** par le code Python suivant

```python
# copier dans le fichier README.md
# les lignes produites par ce code

# mettez ici le nombre de personnes dans votre groupe

how_many_people = 4

print("# the teamwork TP\n")

for i in range(1, how_many_people + 1):
    print(f"{i:02d} Nom:")
    print(f"{i:02d} github:")
```

> [!TIP]
> * On peut faire l'exercice avec un repo public ou privé, c'est au choix du groupe; toutefois si vous choisissez privé, il vous faudra inviter le professeur à accéder au dépôt à la fin de l'exercice;
> * Au moment de la création du repo: **ne choisissez pas** d'initialiser le dépôt avec un `README`, ni avec un `.gitignore`, ni avec une `license`; cela impliquerait la création d'un premier commit automatique, ce qui n'est pas ce que l'on veut ici.
> * Pendant ce temps-là, les autres peuvent s'amuser à créer de leur coté un repo `git-teamwork` vide sur leur compte github, mais sans rien y mettre dedans, pour voir à quoi ça ressemble.

## Étape 2 - droits d'accès - (toujours à faire par le meneur)

Dans cette étape le meneur donne les droits en écriture aux membres de son groupe.

> [!TIP]
> Depuis la page projet, allez dans l'onglet `Settings`, puis `Collaborators`.

## Étape 3 - clonage chez tout le monde

Les autres membres du groupe clônent depuis github.

> [!TIP]
> - Le bouton vert `Code` dans la page du projet sur github ![](the-code-button.png)
> - Pensez à bien choisir 'SSH' avant de copier l'URL du dépôt.

## Étape 4 - modification locale du *NOM*

Chacun édite le fichier `README.md` pour remplir son NOM dans **la ligne correspondant à son numéro** dans le groupe.
Chacun crée localement un commit avec ce changement dans le fichier.

Assurez-vous que le commit contient bien votre nom (dans la rubrique `Author` de `git log`) pour que l'on puisse vous accorder les points lors de l'évaluation.

> [!TIP]
> Pour utiliser correctement votre nom et votre email lors de création des commits, regardez du côté de  
> `git config --global user.name`  
> `git config --global user.email`

## Étape 5 - tout le monde pousse

Chacun pousse son commit dans le dépôt sur github; dans cette étape, arrangez-vous pour que ce soit **le meneur qui pousse son commit en premier**.

> [!TIP]
> * Utilisez la commande `git push` pour envoyer vos commits sur le dépôt distant.
> * Si vous avez des soucis pour pousser votre commit, revoyez dans le cours [le notebook sur le push](https://git.info-mines.paris/synchro-push-nb#label-pull-before-push).

## Étape 6 - tout le monde tire

Chacun tire depuis github; vous devez tous vous retrouver avec les lignes *Nom* renseignées.

## Étape 7 - chacun renseigne son id github

Comme à l'étape 4, mais cette fois vous renseignez votre pseudo github dans la ligne correspondant à votre numéro.

Et vous créez un commit, comme à l'étape 4.

## Étape 8 - chacun pousse

Comme à l'étape 5, sauf que cette fois ce **n'est pas le meneur qui pousse en premier**.

> [!TIP]
> Le même qu'à l'étape 5

## Étape 9 - le groupe publie son dépôt

chaque groupe envoie un mail à son enseignant
en indiquant l'URL du dépôt construit par le groupe sur github

## Epilogue

- Si vous êtes en avance, refaites l'exercice avec un autre meneur dans le groupe
- Si vous obtenez un dépôt plein de spaguettis, recommencez l'exercice en faisant bien attention à chaque étape
- Si vous avez créé un dépôt vide lors de l'étape 1, supprimez le de votre compte github (onglet `Settings` du dépôt, tout en bas de la page, bouton `Delete this repository`)
