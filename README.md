# DesignPatternJava
Patron de conception en java

23 design pattern : 
Interfaces : ADAPTER, FACADE, COMPOSITE, BRIDGE

Responsabilité : SINGLETON, OBSERVER, MEDIATOR, PROXY, CHAIN OF RESPONSIBILITY,
FLYWEIGHT

Construction : BUILDER, FACTORY METHOD, ABSTRACT FACTORY, PROTOTYPE, MEMENTO

Opérations : TEMPLATE METHOD, STATE, STRATEGY, COMMAND, INTERPRETER

Extensions : DECORATOR, ITERATOR, VISITOR


Si vous envisagez de -> Appliquez le pattern : 

• ADAPTER : Adapter l’interface d’une classe pour qu’elle corresponde à l’inter-
face attendue par un client. 
fait en dérivant la classe ou implémentant une interface.

exemple : JTable dans Swing

• FACADE : Fournir une interface simple pour un ensemble de classes. Simplification d'un sous sytème. A ne pas confondre avec une démo.

exemple : 

• COMPOSITE : Définir une interface qui s’applique à la fois à des objets individuels
et à des groupes d’objets(faut faire gaffe au cyles)

exemple : 


• BRIDGE ou Driver : Découpler une abstraction de son implémentation de sorte que les
deux puissent varier indépendamment

exemple : drivers JDBC

• SINGLETON : Centraliser la responsabilité au niveau d’une instance de classe. 
Différence avec une classe statique : singleton : gestion état / junit / lazy load. Static : perf


• OBSERVER Libérer un objet de la "conscience" de connaître les objets qui en
dépendent. Dépendance 1,n entre un objet et ses observeurs quand l'objet change d'état. 

exemple : interface utilisateur


• MEDIATOR : Centraliser la responsabilité au niveau d’une classe qui supervise la
façon dont les objets interagissent. permet de faire des relations entre objet (type BDD) sans que les objets ait a se reférencer les uns les autres. (bijection, l'injection est facile a faire en java, mais le retour est a prendre en charge dans un médiator). 


• PROXY : Laisser un objet agir au nom d’un autre objet. 
 
 
• CHAIN OF RESPONSABILITY : Autoriser une requête à être transmise le long d’une chaîne d’objets
jusqu’à celui qui la traitera 
 exemple : logger (niveau error / info ...)

• FLYWEIGHT : Centraliser la responsabilité au niveau d’objets partagés de forte
granularité. en partageant la partie immuable de l'objet. 

• BUILDER : construction des objets pas à pas. (en dehosr de la classe a instancier). Permet par exemple de le faire à la suite des la reception des inputs d'un utilisateurs. Permet de garantir la validité d'un objet avant de l'instancier.

• FACTORY : L’objectif du pattern FACTORY METHOD est de laisser un autre développeur définir
l’interface permettant de créer un objet, tout en gardant un contrôle sur le
choix de la classe à instancier.
exemple : iterator

• ABSTRACT FACTORY : L’objectif du pattern ABSTRACT FACTORY, ou KIT, est de permettre la création
de familles d’objets ayant un lien ou interdépendants.


• PROTOTYPE : fourniture d'objet par copie sur un exemple. typique pour les objet lent a créer

• MEMENTO : stockage et la restauration d'un état d'un objet.


OPERATION

• TEMPLATE MEHOD : implémentation d'un algo dans une méthode, en laissant à d'autres classe le soin de définir certaines étapes de l'algo. 
exemple : comparator

• STATE : comportement différent selon les état d'un objet
ia dans zhovort.

• STRATEGY : encapsulation des approches (ou stratgies) alternatives dans des classes distinctes qui implémentent chacune une opération communes (proche du template méthod). 


• COMMAND : encapsulation d'une requete dans un objet.

• INTERPRETER

extensions : 

• DECORATOR : permet de définir dynamiquement le comportement de certains objets.
• ITERATOR : accès aux éléments d'une collection de manière sequentiel.
• VISITOR : 
• 
• 


