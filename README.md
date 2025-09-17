# TP - travail en équipe

## Introduction

### Prérequis

Chaque élève doit avoir créé un compte sur `https://github.com/`

### Groupes et rôles

L'exercice est à réaliser en groupes **de 3 à 4 élèves** (ça peut être plus, mais pas moins de 3), chaque groupe ayant **un meneur identifié** (groupes constitués par ailleurs). Le meneur est le joueur #1, les autres membres du groupe sont numérotés 2, 3, 4.

### Critères

pour l'évaluation de votre travail on tiendra compte entre autres 

* du respect des consignes; par exemple si vous n'utilisez pas le nom de dépôt préconisé, ou un autre fichier de départ, vous partez avec un  handicap…
* de la propreté du dépôt obtenu; ce qui nous intéresse quand on constuit un dépôt, ce n'est pas seulement d'arriver avec le bon fichier à la fin, mais aussi que l'histoire que retracent les commits soit conforme à ce qui est demandé

## Étape 1  - création du dépôt sur github - (à faire par le meneur)

### Résultat attendu :

* le meneur a créé un dépôt sur github, sous le nom `git-homework`, c'est-à-dire donc en pratique sous un nom comme `https://github.com/lemeneur/git-homework`
* ce dépôt contient un seul commit avec un seul fichier `README.md`, dont le contenu est **produit** par le code Python suivant

```python
# copier dans le fichier README.md
# les lignes produites par ce code

# mettez ici le nombre de personnes dans votre groupe

how_many_people = 4

for i in range(1, how_many_people + 1):
    print(f"{i:02d} Nom:")
    print(f"{i:02d} github:")
```

## Étape 2 - droits d'accès - (toujours à faire par le meneur)

Dans cette étape le meneur donne les droits en écriture aux membres de son groupe.

### Indice

Depuis la page projet, allez dans l'onglet `Settings`, puis `Collaborators`.

## Étape 3 - clonage chez tout le monde

Ceux qui n'ont pas ce dépôt sur leur ordinateur personnel le clônent depuis github.

```{admonition} Indice
Le bouton vert `Code` dans la page du projet sur github ![](the-code-button.png)
```

## Étape 4 - modification locale du *NOM*

Chacun édite le fichier `README.md` pour **remplir son NOM** dans la ligne correspondant à son numéro dans le groupe.
Chacun crée localement un commit avec ce changement dans le fichier.

Assurez-vous que le commit contient bien votre nom (dans la rubrique `Author` de `git log`) pour que l'on puisse vous accorder les points lors de l'évaluation.

```{admonition} Indice

Pour utiliser correctement votre nom et votre email lors de création des commits, regardez du côté de

* `git config --global user.name` et
* `git config --global user.email`.
```

## Étape 5 - tout le monde pousse

Chacun pousse son commit dans le dépôt sur github; dans cette étape, arrangez-vous pour que ce soit **le meneur qui pousse son commit en premier**.

```{admonition} Indices

* Utilisez la commande `git push` pour envoyer vos commits sur le dépôt distant.
* Si vous avez des soucis pour pousser votre commit, revoyez dans le cours [le notebook sur le push](https://git.info-mines.paris/synchro-push-nb/).
```

## Étape 6 - tout le monde tire

Chacun tire depuis github; vous devez tous vous retrouver avec les lignes *Nom* renseignées.

## Étape 7 - chacun renseigne son id github

Comme à l'étape 4, mais cette fois vous renseignez votre pseudo github dans la ligne correspondant à votre numéro.

Et vous créez un commit, comme à l'étape 4.

## Étape 8 - chacun pousse

Comme à l'étape 5, sauf que cette fois ce **n'est pas le meneur qui pousse en premier**.

```{admonition} Indice
Le même qu'à l'étape 5
```

## Étape 9 - le groupe publie son dépôt

chaque groupe envoie un mail à son enseignant
en indiquant l'URL du dépôt construit par le groupe sur github
