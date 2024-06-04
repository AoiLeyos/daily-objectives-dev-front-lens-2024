# Objectifs Journaliers

## Lundi 03/06/2024

### POO (Programmation Orientée Objet) :

- [x] Est-ce que JS est un langage Orienté Objet ? //c'est un langage prototipal qui a était orienté objet.
- [x] Comprendre ce qu'est l'abstraction. //c'est le fait d'utiliser une variable pour réutiliser du code et diminué la latence.
- [x] Comprendre le principe d'instance. //c'est un exemplaire de l'objet ou de la classe , il s'agit de créé un objet a partir d'un modèle.
- [x] Comprendre ce qu'est une classe. // ce sont des fonctions, il est nécessaire de les déclaré avant de l'instacier.
  - [x] Quelles différences entre classes concrètes et abstraites ? //la class concrète possede une existence physique (elle a des objet) alors que la classe abstraite n'a pas d'existence propre ( elle n'a pas d'objet).
  - [x] Comprendre ce qu'est le constructeur (`constructor`). // c'est une methode appelé lors de l'instanciation lorsque l'on utilise le mot clé class "class panda{
    constructor (){
    } }
  - [x] Attributs / Propriétés.
  - [x] Méthodes.
    - [x] Quelle différence avec les fonctions ? elle n'a pas besoin de parametre.
    - [x] Utilité ? 
    - [x] Getters / Setters.
  - [x] Comprendre ce qu'est le constructeur.
- [x] Comprendre ce qu'est un objet.
- [x] Comprendre le principe d'encapsulation :
  - [x] Qu'est ce que l'encapsulation ?
  - [x] À quoi sert l'encapsulation ?
  - [x] Quels sont les différents mot-clés réservés pour l'encapsulation ? //en JS il n'y en a pas mais il y a des convention ou on utilise "_" 
  - [x] Comprendre le principe de "scope" (portée en français) //Ceux sont les portée privée, public et protégée , la privée est uniquement dans la classe et la protégé dans la classe et ses descendant et la public peux etre utilisé partout également a l'exterieur de la class
  - [x] Pourquoi c'est un principe fondamental de la POO. // elle permet de cacher les détails d'implémentation d'objet, elle protége l'intégrité des données et du comportement de l'objet en empechant l'acces direct, elle favorise la modularité du code , on peu utilisé les objets comme des "boites noires" sans avoir a se soucier du fonctionnement internet, cela facilite la réutilisation des objets dans differents contextes et applications,permet le controle d'accès et de la cohérence en définissant un niveau de visibilité (public, protectegé ou privé), ce qui empeche la modification depuis l'exterieur, ce qui leur permet de maintenir leur etat et leur comportement cohérent.Cela permet également de pouvoir modifier un objet interne sans affecter son utilisation par d'autres parties du système, cela facilite l'évolution et la maintenance du système à long terme,l'abstraction permet de fournir une abstraction des objets, en les présentant sous forme d'interfaces simples et faciles à utiliser, cela réduit la complexité perçue par les utilisateurs de l'objet, qui n'ont pas besoin de connaître les détails d'implémentation.