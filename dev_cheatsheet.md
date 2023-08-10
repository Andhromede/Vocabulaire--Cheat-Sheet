# ≡ CheatSheet du développeur
*(pour une recherche rapide, tapper CTRL + F et entrez le mot désiré)*

<br>

## ✎ UTILITÉ DES BOUCLES :
➢ **FOR** : Si on connait le nombre d'itération à l'avance.

➢ **WHILE** : Si on ne connait pas le nombre d'itération à l'avance.

➢ **DO WHILE** : Pour executer du code au moins une fois avant de boucler.

➢ **FOR IN** _(js)_ : Pour parcourir les propriétés "énumérables" d'un objet.

➢ **FOR OF** _(js)_ : Pour parcourir les propriétés d'un "itérable" (tableau, string, etc).


<br> 

---

## ✎ LES TYPES DE VARIABLES :
### <u>Les Primitifs _(ou type simple)_ :</u>
➢ **Int** : Nombre entier.

➢ **Float** : Nombre à virgule.

➢ **Boolean** : True ou False.

➢ **Char** : 1 seul charactère.

➢ **Byte** : Donnée 8 bits.

➢ **Undefined** _(js)_ : Déclaré mais non définie.

➢ **Null** _(js)_ : Un objet qui ne contient rien.

<br>

---

### <u>Les Référencés _(ou type complèxe)_ :</u>
➢ **String** : Une chaine de charactère.

➢ **Array** : Un tableau (itérable).

➢ **Object** : Structure de données représentant une entité avec des propriétés et des méthodes.

➢ **List** : Similaire aux tableaux, mais de taille dynamique et pouvant stocker des éléments de différents types.

➢ **Tuple** : Similaires aux listes, mais immuable (ne peut pas être modifié une fois créé).

<br>

---

### <u>Les Spéciaux :</u>
➢ **Pointeur** : Variable qui stock l'adresse mémoire d'une autre [variable](#variable).

➢ **Enumération** : Stock un ensemble de constantes nommées.

<br>

---

### <u>Les Génériques :</u>
➢ <b id="classe">Classe</b> : Contient des [propriétés](#propriete), les [attributs](#attribut) et des [méthodes](#methode).

➢ **Interface** : Contrat qui spécifient un ensemble de [méthodes](#methode) qu'une [classe](#classe) doit implémenter.


<br>

---

## ✎ LES TERMES TECHNIQUES :
### <u>Programmation orienté objet (POO) :</u>
➢ **Decorateur** :  Patron de conception structurel qui permet de "décorer" un objet en y ajoutant des méthodes ou en modifiant le comportement de méthodes existantes.

➢ <b id="encapsulation">Encapsulation</b> : Restriction de l'accès direct aux composants ([attributs](#attribut)/[methodes](#methode)) d'un objet. Elle permet donc de cacher les détails internes d'une classe et d'exposer uniquement ce qui est nécessaire.

➢ <b id="attribut">Attribut</b> (variable membre) : [Variable](#variable) associée à une [classe](#classe) ou à une instance de classe et qui représente les [propriétées](#propriete) ou caractéristiques d'un objet.

➢ <b id="methode">Methode</b> : [Fonction](#fonction) définie à l'intérieur d'une [classe](#classe) et qui représente les actions qu'un objet peut réaliser.

➢ **Constructeur** : [Méthode](#methode) spéciale d'une [classe](#classe) appelée lors de création d'une instance de classe.

➢ **Destructeur** : [Méthode](#methode) spéciale d'une [classe](#classe) appelée lors de la destruction d'une instance.

➢ **Accesseur** (Getter) : [Méthode](#methode) utilisée pour obtenir la valeur d'un [Attribut](#attribut) "protégé".

➢ <b id="classAbstraite">Classe Abstraite</b> : [classe](#classe) qui ne peut pas être [instanciée](#instance) directement et sert généralement de base pour d'autres classes.

➢ **Méthode abstraite** : [Méthode](#methode) déclarée mais non [implémentée](#implementation) dans une [classe abstraite](#classAbstraite) (elle doit toutefois être implémentée par toutes les [sous-classes](#sousClass) non abstraites).

➢ **Visibilité** : Définit si (ou comment) un [attribut](#attribut) ou une [methode](#methode) est accessible en dehors de la [classe](#classe) ([public](#public), [private](#private), [protected](#protected)).

➢ **Mutateur** (Setter) : [Méthode](#methode) utilisée pour définir ou modifier la valeur d'un [attribut](#attribut).

➢ **Surcharger** (Overloading) : Définir plusieurs [methodes](#methode) ou [fonctions](#fonction) avec le même nom mais avec des [paramètres](#parametre) différents.

➢ <b id="instance">Instance</b> : Objet individuel créé à partir d'une [classe](#classe).

➢ **Instantiation** : Processus de création d'un objet à partir d'une [classe](#classe).

➢ **Abstraction** :  Pratique de cacher les détails complexes et de présenter uniquement les caractéristiques essentielles.

➢ <b id="propriete">Propriete</b> (interface) : Synonyme d'[attribut](#attribut), c'est une caractéristique ou une donnée membre d'une classe.

➢ <b id="superClass">SuperClasse</b> : Une classe dont d'autres [classes](#classe) héritent des caractéristiques. Aussi appelée classe mère ou classe parente.

➢ <b id="sousClass">Sous-classe</b> : Une classe qui hérite des caractéristiques d'une autre [classe](#classe). Aussi appelée classe fille ou classe dérivée.   

➢ <b id="heritage">Heritage</b> : Mécanisme par lequel une [classe](#classe) peut hériter des [attributs](#attribut) et des [methodes](#methode) d'une autre classe.

➢ **Composition** : Une forme de relation où une [classe](#classe) contient une [instances](#instance) d'une autre classe comme [attributs](#attribut).

➢ **Association** : Relation entre deux [classes](#classe) ou l'une utilise les fonctionnalités de l'autre mais sans dépendance très forte.

➢ <b id="dependance">Dépendance</b> : Lien entre 2 classes où l'une dépend de l'autre pour son fonctionnement.

➢ **Factory** (Fabrique) : Patron de conception pour créer des objets sans spécifier la [classe](#classe) exacte à instancier.

➢ **Singleton** : Patron de conception qui restreint l'instanciation d'une [classe](#classe) à un seul objet.

➢ **Agrégation** : Forme spéciale d'association où une [classe](#classe) contient une référence à un objet d'une autre classe, mais sans en prendre la propriété complète.

➢ **Interface** : Déclaration de [méthodes](#methode) sans [implémentations](#implementation) que les [classes](#classe) doivent quand à elle implémenter. Elle permet à différents objets d'être traités comme des [instances](#instance) d'une interface commune, indépendamment de leur classe d'origine.

➢ <b id="polymorphisme">Polymorhpisme</b> : Capacité de prendre plusieurs formes pour des objets de classes différentes afin d'être traités comme des objets d'une classe commune.

<br>

---

### <u>Modificateurs d'accès (classes) :</u>
➢ <b id="public">Public</b> : Accessible depuis n'importe quelle autre [classe](#classe), qu'elle soit dans le même paquet/module ou non.

➢ <b id="private">Private</b> : Accessible uniquement à l'intérieur de la [classe](#classe) où il est défini (pas de modif exterieur).

➢ <b id="protected">Protected</b> : Accessible dans la [classe](#classe) où il est défini, ainsi que dans ses [sous-classes](#sousClass) et toutes les classes du même paquet/module. (intermédiaire entre [public](#public) et [private](#private)).  

➢ <b id="static">Static</b> : Appartient à la [classe](#classe) elle-même plutôt qu'à une [instance](#instance) de la classe. Toutes les instances de la classe partagent le même attribut [static](#static). Il peut être combiné avec d'autres modificateurs d'accès (ex: [public](#public) static, [private](#private) static). 

<br>

---

### <u>Variables/Fonctions :</u>
➢ **Argument** : Valeur ou référence passée à une [fonction](#fonction) ou procédure lors de son appel.

➢ **Callback** : Fonction passée en tant qu'argument à une autre [fonction](#fonction) et qui sera ensuite exécutée à un moment donné.

➢ **Conditionnelle** : Structure permettant d'exécuter du code en fonction d'une condition.

➢ <b id="fonction">Fonction</b> : Série d'étapes ou d'instructions organisées de manière séquentielle, destinées à accomplir une tâche ou à réaliser un objectif spécifique. Celle-ci doit obligatoirement retourner une valeur (contrairement a la [procédure](#prodecure)). Son objectif étant d'etre réutilisable et d'éviter les duplication de code.

➢ <b id="listeLiee">Liste liée</b> : Collection d'éléments ordonnés où chaque élément [pointe](#pointeur) vers le suivant.

➢ **Paramètre** : [Variable](#variable) utilisée dans la déclaration d'une [Fonction](#fonction) (ou [procédure](#prodecure)) pour recevoir une valeur lors de l'appel de cette dernière.

➢ <b id="procedure">Procedure</b> : [Fonction](#fonction) qui ne retourne pas de valeur.

➢ **Recurssion** : (récursivité) Mécanisme où une [Fonction](#fonction) s'appelle elle-même. Une fonction récursive doit obligatoirement posséder une condition d'arret afin d'évite une boucle infinis.

➢ <b id="variable">Variable</b> : Emplacement de stockage pour une valeur.

<br>

---

### <u>L'Architecture :</u>
➢ <b id="api">API</b> (Application Programming Interface) : Ensemble de [Fonctions](#fonction) et [Procédures](#procedure) qui permettent la création d'applications.

➢ **API Endpoint** : URL spécifique où une [API](#api) peut être accessible et où les opérations peuvent être effectuées.

➢ **Arbre** : Structure de données hiérarchique composée de [nœuds](#noeud), où chaque nœud a un parent (sauf le nœud racine) et 0 ou n enfants.

➢ **Design Pattern** (Pattern) : Façon répétitive ou habituelle de faire quelque chose (bonne pratique).

➢ **Implémentation** : Réalisation concrète d'une méthode, fonction, classe ou interface définie.

➢ **Injection** (de [dépendance](#dépendance)) : Technique consistant à insérer des objets dans une classe.

➢ **Injection** (de code) : Technique par laquelle un attaquant peut insérer ou "injecter" du code malveillant dans un système (ex: injection SQL ou de JS). 

➢ **MVC** (Model-View-Controller) : Modèle architectural pour développer des logiciels en séparant la logique métier, l'interface utilisateur et le contrôle de l'application.

➢ <b id="noeud">Nœud</b> : Élément individuel d'une structure de données, comme un [arbre](#arbre) ou une [Liste liée](#listeLiee).

➢ **Refactoring** : Processus de restructuration du code existant sans changer son comportement externe afin d'améliorer sa lisibilité, sa structure ou sa complexité.

➢ **REST** (Representational State Transfer) : Style architectural pour la conception de services de réseau, souvent utilisé pour construire des ([API](#api)) web. 

➢ **Sémantique** : Balises HTML qui ont un sens ou une signification spécifique (par exemple, ```<header>, <footer>``` etc).

<br>

---

### <u>Les données/transferts :</u>
➢ **Bande passante** : Capacité maximale de transfert de données d'un point à un autre.

➢ **Cache** : Stockage temporaire de données pour des récupérations rapides.

➢ <b id="client">Client</b> : Programme ou système (ex : navigateur) qui demande un service ou des ressources à un autre système distant, généralement appelé [serveur](#serveur).

➢ **Compilation** : Processus de transformation du code source de haut niveau (C#, Java, etc.) en un code machine ou en un code intermédiaire exécutable par un ordinateur.

➢ **Concurrence** : Exécution simultanée de plusieurs séquences d'opérations.

➢ **Debordement de pile** (Stack Overflow) : Erreur qui se produit lorsque la [pile](#pile) atteint sa capacité maximale.

➢ **Deploiement** : Processus de mise en ligne (production) ou de distribution d'une application/système pour qu'elle soit opérationnelle.

➢ **Deserialisation** : Processus de conversion d'une représentation sérialisée en une structure de données/objet (inverse de la [sérialisation](#serialisation)).

➢ **File (Queue)** : Structure de données basée sur le principe Premier Entré, Premier Sorti (PEPS).

➢ **Garbage Collection** : Processus automatisé de récupération de la mémoire qui n'est plus référencée ou utilisée dans un programme.

➢ **GraphQL** : Langage de requête pour [API](#api), permettant au [client](#client) de demander uniquement les données qu'il souhaite.

➢ **Interpréteur** : Programme qui lit et exécute le code source ligne par ligne sans nécessité de le compiler.

➢ **Latence** : Délai entre une action et une réponse.

➢ **Lazy Loading** : Tactique de chargement de ressources uniquement lorsqu'elles sont nécessaires.

➢ **Promesse** : Objet représentant la complétion ou l'échec éventuel d'une opération asynchrone.

➢ **Protocole** : Ensemble de règles et conventions pour la communication entre systèmes.

➢ **Paquet** : Unité de données envoyée sur un réseau.

➢ **Package** : Module ou ensemble de modules préemballés, souvent avec des [dépendances](#dependance), que l'on peut utiliser dans d'autres projets.

➢ <b id="pile">Pile</b> : Permet de gérer les appels et les retours de [fonctions](#fonction). Lorsqu'une fonction est appelée, un enregistrement est créé et ajouté au sommet de la pile d'appel.

➢ **Requête** : Demande d'information ou d'action à un système ou une base de données.

➢ **Runtime** : Temps pendant lequel un programme est en cours d'exécution.

➢ <b id="serialisation">Serialisation</b> : Processus de conversion d'un objet ou d'une structure de données en un format linéaire (binaire, XML, JSON, etc) = JSON.parse en JS, et ceux pour le stockage ou la transmission. 

➢ <b id="serveur">Serveur</b> :  Système ou application fournissant des ressources, des données ou des services à des [clients](#client).

➢ **Socket** : Point de terminaison pour envoyer ou recevoir des données à travers un réseau.

➢ **Synchronisation** : Coordination d'opérations pour qu'elles s'exécutent dans le bon ordre, souvent utilisée dans les environnements [multithread](#thread).

➢ <b id="thread">Thread</b> : Unité la plus petite de traitement que peut gérer un système d'exploitation.

➢ **Webhook** : Mécanisme permettant à une application de fournir des données à une autre application dès qu'un événement spécifique se produit.

<br>

---

### <u>L'environnement :</u>
➢ <b id="biblio">Bibliothèque</b> (library) : Ensemble de [fonctions](#fonction), [classes](#classe) ou [routines](#routine) utilisées pour développer des logiciels sans avoir à les écrire à partir de zéro.

➢ <b id="container">Container</b> : Technologie permettant de contenir une application et ses [dépendances](#dependance) dans un environnement isolé, garantissant qu'elle fonctionnera de la même manière, quelle que soit la plateforme sur laquelle elle est exécutée.

➢ **Docker** : Outil permettant de créer, déployer et exécuter des applications à l'aide de [conteneurs](#container).

➢ **Framework** : Ensemble d'outils et de [bibliothèques](#biblio) conçu pour faciliter la création d'applications en fournissant des structures et des fonctions réutilisables.

➢ **Git** : Logiciel de versionning permettant de suivre les modifications apportées à un code source pendant le développement de logiciels et fonctionnant a un niveau atomique.

➢ **IDE** (Integrated Development Environment) : Environnement de développement intégré afin d'écrire, de tester et de déboguer du code.

➢ **Middleware** : Logiciel qui agit comme un pont entre différents logiciels ou services.

➢ **ORM** (Object-Relational Mapping) : Technique permettant de mapper et de synchroniser les données entre des systèmes de bases de données relationnelles et des objets orientés objet.

➢ **SandBox** (bac à sable) :  Environnement de test isolé où les codes, les applications ou les fichiers peuvent être exécutés sans affecter l'application ou le système d'exploitation hôte.

➢ **VM** (Machine virtuelle) :  Logiciel simulant un environnement informatique et permettant d'exécuter des programmes comme s'ils fonctionnaient sur un ordinateur physique.

<br>

---

### <u>Vocabulaire :</u>
➢ **Deprecié** : Obsolescence d'une [fonction](#fonction) ou d'une [bibliothèque](#biblio) et qui pourrait être supprimée/remplacée dans les versions futures. 

➢ <b id="regex">Regex</b> (Expression régulière) : Séquence de caractères représentant un modèle de recherche dans un texte (ex: le modèle d'une adresse mail).

<br>

---

_Fin du glossaire._
