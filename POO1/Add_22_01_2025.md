##     Evaluations d’expression de création d’objet :
%
 Allocation mémoire + création de la référence
•   Initialisation standard par le système
•   Exécution successives des constructeurs
•   Retour de la référence

## this
%
this désigne l’objet courant.

this(...) : Permet à un constructeur d’en appeler
un autre de la même classe.
Doit être utilisé obligatoirement comme première instruction dans le corps du constructeur appelant.

## Variable locale :
%
•   se déclare dans un bloc de code.
•   a une portée limitée au bloc de code.
•   initialisée par le développeur.
•   a une durée de vie égale à la durée d’exécution du bloc de code.
•   est stockée dans la pile.

## Variable d’instance :
%
•   se déclare hors de tout bloc de code mais dans une classe.
•   a une portée étendue à toute la classe.
•   initialisée par le système.
•   a une durée de vie égale à celle de l’objet.
•   est stockée dans le tas (heap).

## Classe non mutable
%
Classe dont les instances ne peuvent pas modifier
leur état. La classe String est un exemple de classe non mutable.

## Equivalence d’objets
%
Deux objets sont dits équivalents lorsqu’ils ont le
même type et le même état courant.

## Exception
%
Objet qui signale une situation anormale lors de l’exécution
d’un programme. La machine Java provoque l’arrêt du flot d’exécution normal
et propage l’erreur au code appelant avec possibililté de recuperation de l’erreur.

## Classe enveloppe
%
Classe qui enveloppe et permet de représenter des
valeurs de types primitifs à l’aide d’objets non mutables.

    •   String
    •   Integer
    •   Short
    •   Byte
    •   Character
    •   Double
    •   Long
    •   Float
    •   Boolean

## Surcharge de méthode
%
On dit qu’une méthode m est surchargée lorsqu’il
existe dans une même classe plusieurs méthodes différentes de même nom m.
Dans ce cas, seule la liste de leurs paramètres permet de les distinguer.

## Requête
%
Opération définie sur A et à valeur dans autre que A.

## Générateurs
%
• créateur : générateur (donc à valeur dans A) constant ou définie sur un
       autre ensemble que A.
     • commandes : générateur (donc à valeur dans A) défini sur un ensemble
       produit dont l’un des facteurs est A.

## Type de Données Abstrait (TDA)
%
 Un TDA est définit par un ensemble
d’éléments, un ensemble d’opérations qui s’appliquent sur ses éléments, ainsi
qu’une sémantique pour ces opérations.

## Opération
%
 Fonction qui s’applique sur une partie de A et/ ou à valeurs dans A.

## Préconditions
%
Les préconditions expriment quelles sont les valeurs des arguments qui sont utilisables avec une opération donnée. Une précondition est un ensemble de contraintes qui portent sur l’état du système juste avant l’appel de la méthode. C’est une contrainte pour le client qui doit placer le système dans un état vérifiant cette précondition avant d’appeler la méthode.

## Axiome
%
Les axiomes sont des règles qui définissent la sémantique des opérations.

## Postconditions
%
Ensemble de contraintes qui portent sur l’état du système juste avant le retour d’appel de méthode. C’est une contrainte pour le fournisseur qui doit placer le système dans un état vérifiant cette postcondition.

## Fonction d’Abstraction
%
Fonction permettant d’associer à une instance
de la classe l’élément qui lui correspond naturellement dans le TDA à un instant donné.

## Invariant de Représentation
%
Conjonction d’expressions booléennes qui
caractérisent les valeurs autorisées pour l’état interne des instances de la classe.
