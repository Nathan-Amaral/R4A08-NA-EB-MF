# Exercice 1

### Partie 1 ###

## Question 1

Quelle est la commande pour créer l'image à partir de ce dockerfile ?

docker build -t docker-ex1 .


## Question 2

Quel est le retour de la commande ?
(tout ce qui s'est affiché lors de la construction de l'image)

Sending build context to Docker daemon  3.072kB
Step 1/1 : FROM alpine
 ---> 4e2a7d60c29f
Successfully built 4e2a7d60c29f
Successfully tagged docker-ex1:latest


## Question 3
Lors de la construction de l'image, nous n'avons pas défini de nom. Un nom lui a été affecté automatiquement.
Il est présent dans le retour de la commande de construction de l'image.

Quel est-il ?

Docker lui attribue un nom par défaut sous forme d'un identifiant unique (ID). Par exemple, l'ID de l'image peut ressembler à ceci : 4e2a7d60c29f

## Question 4
Quelle est la commande pour ajouter un nom personnalisé (ici : docker-ex1)

docker tag 4e2a7d60c29f docker-ex1

### Partie 2 ###
