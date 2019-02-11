
La POO avec JAVA
===

**LUNDI :**
veille sur la Programmation Orientée Objet(POO)

Exercice 8 : (projet TP8-Poo sur les notions de classes et d'objets, constructeurs, attributs (static ou pas), méthodes(static ou pas), encapsulation)

8.1 : crée une première classe Ville avec pour attributs nom, pays, nbHabitants, définir au moins 1 constructeur. Après quoi, un programme de test dans le main pour instancier votre classe et obtenir le résultat suivant : Ville v1 = new Ville("TOULOUSE" , "FRANCE" , 500000); répétez l'instanciation de votre classe avec plusieurs villes v2,v3... puis afficher les attributs de chaque ville.

8.2 : Toujours dans votre classe Ville, mettez en place vos accesseurs(getter et setter) pour empecher l'utilisateur de changer vos attributs sans votre approbation, par ex, en empechant ce genre de modif ici : v1.nbHabitants = -200.

8.3 : crée une méthode pour afficher les attributs d'une ville tel que v1.display() aura pour résultat : <ville de TOULOUSE en FRANCE avec 500000 habitants>

8.4 : Trouver un moyen de compter le nombre d'instance de votre classe Ville. v1,v2 et v3 ici veut dire qu'il y a 3 objets donc 3 instances.

8.5 : Dans le même projet(TP8-Poo) crée la classe Personne avec pour attributs nom, prénom, âge, adresse et une méthode d'affichage : Personne p1 = new Personne("dupont","henri",51,"3 rue des rosiers à Nice");
p1.display() aura pour résultat : <dupont henri 51ans habitant 3 rue des rosiers à Nice>

8.6 : Ajouter à votre classe Personne un attribut VilleNaissance qui est un objet de type Ville.

8.7 : Reprenez le TP7-concessionnaire et utiliser la POO pour refaire l'exercice

8.8 : crée la classe Fraction qui représente les fractions tel que Fraction r1 = new Fraction(5,2); La aussi, ajouter une méthode d'affichage [5/2] Quelle solution pour la fraction [5/0] ?

8.8 : ajouter à votre classe Fraction une méthode addition de 2 fractions 

++ vos programmes doivent précisemment répondre aux besoins exprimé

++ en cas de doute sur l'énoncé, n'hésitez pas à solliciter votre client pour des précisions

++ s'habituer à réaliser les exercices en anglais

++ respecter les règles d'écriture de code (maj-min)

++ Vous pouvez utiliser les outils d'Eclipse pour générer du code

++ Les noms de classe, attributs, méthodes et variables doivent être explicite et compréhensible de tous

++ attention à l'indentation

++ commenter vos codes

++ une fois tous ces critères respectés, vous pouvez mettre votre projet sur github et partager le lien


**MARDI :**
veille sur la notion d'héritage   

Exercice 9 : (TP9-héritage, visibilité, package, class Object/toString())

9.1 : Dans votre projet TP9, commencer cette fois ci par créer un package "co.simplon.towns" puis dans celui ci une classe Capitale qui hérite de la classe Ville avec comme particularité d'avoir un monument -> Paris est une Ville avec un monument la tour Eiffel (n'oublier d'ajouter la classe Ville dans votre package) puis ajouter une classe de Test avec un main dans votre package afin d'instancier plusieurs capitale, les modifier via les accesseurs et les afficher in fine via la méthode toString().

9.2 : Créer un package "co.simplon.peoples" puis Ecrire la classe Employe qui hérite de Personne tel qu'un Employé est une Personne avec comme particularité d'être dans une entreprise avec un salaire. Puis créer une classe Test et dans votre main, utiliser un tableau de 10 instances d'Employe à parcourir pour afficher les informations de chaque employé la aussi à l'aide de la méthode toString(). Reproduisez le même test avec une liste, qu'en déduisez-vous ?

9.3 : Créer un package "co.simplon.shapes" et Ecrire les classes Triangle, Carré et Cercle avec leurs attributs à trouver, ajouter une méthode qui calcule l'air d'une forme géométrique. Que constatez vous ?

**MERCREDI :**
veille sur les notions de classe abstraites et les interfaces

? Interview croisé dynamique sur le polymorphisme ?

Exercice 10 : méthodes et classes Abstraites

10.1 : Reprendre l'exercice 9.3 et trouver un moyen d'éviter les redondances de code en utilisant l'héritage

10.2 : Trouver un moyen d'éviter l'instanciation de la classe Shape (forme géométrique)

10.3 : Réaliser un tableau d'objet ou une liste de Shape contenant des triangles, cerles et carrés instanciés avant d'être ajouté, parcourir vos objets puis afficher

10.4 : Refaire la même chose avec l'exercice 9.4 et mettre en oeuvre classe absraite et polymorphisme

**JEUDI :**
veille sur git-github avec Eclipse

Kata : Vous travaillez pour un vendeur d'imprimantes et vous les livrer avec des drivers (listes de méthodes) qui permettent au systeme d'exploitation d'utiliser votre imprimante comme il se doit aussi quelles sont les méthodes que l'exploitant (linux,windows,android...) doit obligatoirement redefinir pour exploiter correctement votre imprimante.

REVISIONS

**VENDREDI :**
veille sur le génie logiciel

11.1 : (package "co.simplon.transports") Reprendre l'exercice 8.6 et utiliser l'héritage pour gérer l'agrandissement du parc de voitures de notre concessionnaire comprenant plusieurs type de moyen de transport (utilitaire, familiale, moto, 4*4, camions, berline, bateau, avion)


Terminer tous les exercices de la semaine et les mettre sur GitHub une fois fonctionnels avec tous les critères respectés.
