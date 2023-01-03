# WORKSHOP Créer un Formulaire de saisie avec APP SCRIPT

## Le but de ce Workshop :

Le but est de découvrir un peu le langage Appscript developpé par Google. Mais que à la fin vous puissiez réaliser un formulaire de saisie d’information sur une feuille de calcul et stocker ces données dans une feuille de Google Sheet.

## Prérequis 
Avoir à disposition un compte Google ou Microsoft pour faire ce Workshop.


## Étape 1 :

Aller sur https://docs.google.com/spreadsheets et crée une nouvelle feuille de calcul « INFO » et créé de colonne (Nom Prénom) en position A1 et B2 et en dessous mettre votre nom prénom.

![alt text](https://github.com/kvn703/WORKSHOP_FORMULAIRE_HUB/blob/main/ETAPE%201.png)
<img src="[ETAPE%201.jpg](https://github.com/kvn703/WORKSHOP_FORMULAIRE_HUB/blob/main/ETAPE%201.png)" width="200"/>
 

## Étape 2 : Récupérer une donnée sur la feuille de calcul en utilisant la fonction GETRANGE

Pour ouvrir un éditeur de texte, appuyer sur l’icône « Extensions » puis « Appscript ».
Une fois dessus, créer une fonction GetInfo() qui doit récupérer votre nom et prénom depuis la feuille INFO et renvoie votre nom et prénom sur la console.


## Étape 3 : Ajouter des données sur une ligne avec la fonction SETVALUE

Créer une fonction AddHoppyName() qui ajoute sur la ligne suivant « Le chat » « Hoppy »

![alt text](https://github.com/kvn703/WORKSHOP_FORMULAIRE_HUB/blob/main/ETAPE%203.png)

## Étape 4 : Ajouter des données sur une ligne avec la fonction APPENDROW

Créer une fonction AddName(nom, prenom) qui prend en paramètre 2 chaines de caractères (nom et prénom). Cette fonction doit ajouter le nom et prénom à la ligne suivant sans utiliser la fonction Setvalue.

## Étape 5 : Supprimer une ligne

1.	Créer une fonction RemoveRow() qui doit supprimer la ligne numéro 3
2.	Ensuite, créer une fonction RemoveName(Nom) qui prend en paramètre une chaîne de caractères et devra supprimer la ligne ayant le nom associé.




## Étape 6 : Créer un bouton

1.	Pour créer un bouton, aller sur « Insertion »  « dessin »  dessiner votre dessin et appuyer sur « Enregistrer et fermer ».
2.	Une fois fait, il va falloir mettre une action sur ce bouton. Lorsqu’on appuie sur ce bouton on veut que cela ajoute à la ligne suivante « Astek » et « APE ». Et donc associer une fonction à ce bouton pour qu’à chaque on clique dessus, cette action se passe.

![alt text](https://github.com/kvn703/WORKSHOP_FORMULAIRE_HUB/blob/main/ETAPE%206.png)


## À VOUS DE JOUER MAINTENANT !

Avec toutes ces étapes réalisées, il est le moment de faire notre formulaire.
Donc c’est un formulaire de saisie sur la feuille « INFO » qui devra demander les informations suivantes :
-	Nom
-	Prénom
-	Date de Naissance (dd/mm/yyyy)
-	Adresse mail
-	Sexe
Et valider ces informations en appuyant sur un bouton « Valider », devra ajouter ces informations dans la feuille « Base de données »

ATTENTION, on ne peut pas ajouter deux mêmes personnes. 

De plus, ajouter un bouton « Supprimer » qui devra supprimer via une recherche de nom et prénom la ligne dans la feuille « Base de données ». 

Voici un exemple de la mise en forme du Formulaire

![alt text](https://github.com/kvn703/WORKSHOP_FORMULAIRE_HUB/blob/main/EXEMPLE.png)
