EXERCICE 1:

Description

Ce projet illustre le polymorphisme en Java à travers une hiérarchie de classes :
Forme (super-classe) et ses sous-classes Cercle, Rectangle, et Triangle.
Chaque sous-classe redéfinit la méthode dessiner(), permettant d’appeler la bonne version automatiquement grâce à la liaison dynamique.

Fonctionnement

Le programme crée un tableau hétérogène de formes (Forme[]) et appelle la méthode dessiner() sur chacune d’elles.
Chaque appel invoque la version spécifique à la classe réelle de l’objet.

<img width="1840" height="844" alt="image" src="https://github.com/user-attachments/assets/29678976-2914-4cf0-96df-8f1609bb5721" />

EXERCICE 2:

Description

Ce projet démontre le polymorphisme en Java à travers une hiérarchie de classes représentant différents types de médias : Audio, Video, et LiveStream, dérivées de la super-classe Media.
Tous les objets sont stockés dans un même tableau, et leurs méthodes lire() et getDuree() sont appelées de manière uniforme grâce à la liaison dynamique.

Fonctionnement

Le programme crée une bibliothèque multimédia contenant différents types de médias, les lit un par un, puis calcule la durée totale (hors flux en direct).

<img width="1865" height="628" alt="image" src="https://github.com/user-attachments/assets/9b162b2b-ecc3-4d87-be36-d70f41dc9d59" />

EXERCICE 3:

Objectif:

Illustrer l’utilisation combinée de :
L’héritage
Les classes abstraites
Les méthodes génériques
Le but est de manipuler uniformément différents types d’employés (Développeur, Manager) à travers une même interface abstraite (Personne).

Fonctionnement:

Chaque classe hérite de Personne et redéfinit la méthode calculerSalaire() :
Développeur → +10 % de prime
Manager → +30 % de prime
La méthode générique Utils.listerPersonnes() affiche les salaires de tous les employés, quelle que soit leur sous-classe.

<img width="1573" height="348" alt="image" src="https://github.com/user-attachments/assets/b9657775-8e04-4ced-8e6f-80412630a3ee" />


