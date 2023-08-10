# ≡ CheatSheet du développeur
*(pour une recherche rapide, tapper CTRL + F et entrez le mot désiré)*

<br>

## ✎ UTILITÉ DES BOUCLES :
➢ **FOR** : Si on connait le nombre d'itération à l'avance.

➢ **WHILE** : Si on ne connait pas le nombre d'itération à l'avance.

➢ **DO WHILE** : Pour executer du code au moins une fois avant de boucler.

➢ **FOR IN** _(js)_ : Pour parcourir les propriétés "énumérables" d'un [objet](#objet).

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

➢ **Null** _(js)_ : Un [objet](#objet) qui ne contient rien.

<br>

---

### <u>Les Référencés _(ou type complèxe)_ :</u>
➢ **String** : Une chaine de charactère.

➢ **Array** : Un tableau (itérable).

➢ **Object** : Structure de données représentant une [entité](#entite) avec des propriétés et des méthodes.

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

➢ **Abstraction** :  Pratique de cacher les détails complexes et de présenter uniquement les caractéristiques essentielles.

➢ <b id="accesseur">Accesseur</b> (Getter) : [Méthode](#methode) utilisée pour obtenir la valeur d'un [Attribut](#attribut) "protégé".

➢ **Agrégation** : Forme spéciale d'association où une [classe](#classe) contient une référence à un [objet](#objet) d'une autre classe, mais sans en prendre la propriété complète.

➢ **Association** : Relation entre deux [classes](#classe) ou l'une utilise les fonctionnalités de l'autre mais sans dépendance très forte.

➢ <b id="attribut">Attribut</b> (variable [membre](#membre)) : [Variable](#variable) associée à une [classe](#classe) ou à une instance de classe et qui représente les [propriétées](#propriete) ou caractéristiques d'un [objet](#objet).

➢ **Composition** : Une forme de relation où une [classe](#classe) contient une [instances](#instance) d'une autre classe comme [attributs](#attribut).

➢ <b id="constructeur">Constructeur</b> : [Méthode](#methode) spéciale d'une [classe](#classe) appelée lors de création d'une instance de classe.

➢ <b id="classAbstraite">Classe Abstraite</b> : [classe](#classe) qui ne peut pas être [instanciée](#instance) directement et sert généralement de base pour d'autres classes.

➢ **Decorateur** :  Patron de conception structurel qui permet de "décorer" un [objet](#objet) en y ajoutant des méthodes ou en modifiant le comportement de méthodes existantes.

➢ <b id="dependance">Dépendance</b> : Lien entre 2 classes où l'une dépend de l'autre pour son fonctionnement.

➢ **Destructeur** : [Méthode](#methode) spéciale d'une [classe](#classe) appelée lors de la destruction d'une instance.

➢ <b id="encapsulation">Encapsulation</b> : Regroupement des données ([attributs](#attribut)) et des [méthodes](#methode) ([fonctions](#fonction)) qui manipulent ces données en une seule unité ou [classe](#classe). L'encapsulation vise également à [restreindre l'accès](#public) direct à certaines composantes de cet [objet](#objet), afin de prévenir des modifications non autorisées ou inattendues de ces données.

➢ <b id="entite">Entité</b> : Une [entité](#entite) peut se référer à un [objet](#objet) ou à une [instance](#instance) d'une [classe](#classe) particulière, en particulier lorsqu'il s'agit d'un objet représentant un concept du monde réel dans le système, comme un utilisateur ou un produit. Une entité peut avoir des [méthodes](#methode) et des [propriétés](#propriete) associées pour manipuler et représenter ses données. 

➢ **Factory** (Fabrique) : Patron de conception pour créer des [objets](#objet) sans spécifier la [classe](#classe) exacte à instancier.

➢ <b id="heritage">Heritage</b> : Mécanisme par lequel une [classe](#classe) peut hériter des [attributs](#attribut) et des [methodes](#methode) d'une autre classe.

➢ <b id="instance">Instance</b> : [Objet](#objet) individuel créé à partir d'une [classe](#classe).

➢ <b id="instancier">Instancier</b> : Créer une [instance](#instance) ou un [objet](#objet) d'une [classe](#classe) spécifique.

➢ **Instantiation** : Processus de création d'un [objet](#objet) à partir d'une [classe](#classe).

➢ **Interface** : Déclaration de [méthodes](#methode) sans [implémentations](#implementer) que les [classes](#classe) doivent quand à elle implémenter. Elle permet à différents [objets](#objet) d'être traités comme des [instances](#instance) d'une interface commune, indépendamment de leur classe d'origine.

➢ <b id="membre">Membre</b> : Attribut ou méthode associé à une [classe](#classe) ou une structure.

➢ <b id="methode">Methode</b> : [Fonction](#fonction) définie à l'intérieur d'une [classe](#classe) et qui représente les actions qu'un [objet](#objet) peut réaliser.

➢ **Méthode abstraite** : [Méthode](#methode) déclarée mais non [implémentée](#implementer) dans une [classe abstraite](#classAbstraite) (elle doit toutefois être implémentée par toutes les [sous-classes](#sousClass) non abstraites).

➢ **Mutateur** (Setter) : [Méthode](#methode) utilisée pour définir ou modifier la valeur d'un [attribut](#attribut).

➢ <b id="objet">Objet</b> : Instance concrète d'une [classe](#classe). Il s'agit d'une [entité](#entite) qui [encapsule](#encapsulation) à la fois les données (par ses [attributs](#attribut)) et les [méthodes](#methode) qui opèrent sur ces donnée. Cela permet l'encapsulation, l'héritage, le polymorphisme et d'autres concepts fondamentaux de la POO.

➢ <b id="polymorphisme">Polymorhpisme</b> : Capacité de prendre plusieurs formes pour des [objets](#objet) de classes différentes afin d'être traités comme des objets d'une classe commune.

➢ <b id="propriete">Propriete</b> (interface) : Synonyme d'[attribut](#attribut), c'est une caractéristique ou une donnée [membre](#membre) d'une classe.

➢ **Singleton** : Patron de conception qui restreint l'instanciation d'une [classe](#classe) à un seul [objet](#objet).

➢ <b id="superClass">SuperClasse</b> : Une classe dont d'autres [classes](#classe) héritent des caractéristiques. Aussi appelée classe mère ou classe parente.

➢ **Surcharger** (Overloading) : Définir plusieurs [methodes](#methode) ou [fonctions](#fonction) avec le même nom mais avec des [paramètres](#parametre) différents.

➢ <b id="sousClass">Sous-classe</b> : Une classe qui hérite des caractéristiques d'une autre [classe](#classe). Aussi appelée classe fille ou classe dérivée.   

➢ **Visibilité** : Définit si (ou comment) un [attribut](#attribut) ou une [methode](#methode) est accessible en dehors de la [classe](#classe) ([public](#public), [private](#private), [protected](#protected)).


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

➢ **Routine** : Séquences répétitives de code conçues pour effectuer une tâche spécifique.

➢ <b id="variable">Variable</b> : Emplacement de stockage pour une valeur.

<br>

---

### <u>L'Architecture :</u>
➢ <b id="api">API</b> (Application Programming Interface) : Ensemble de [Fonctions](#fonction) et [Procédures](#procedure) qui permettent la création d'applications.

➢ **API Endpoint** : URL spécifique où une [API](#api) peut être accessible et où les opérations peuvent être effectuées.

➢ **Arbre** : Structure de données hiérarchique composée de [nœuds](#noeud), où chaque nœud a un parent (sauf le nœud racine) et 0 ou n enfants.

➢ **Controller** : Dans un contexte [MVC](#mvc), il s'agit de la partie qui reçoit les requêtes, traite la logique métier et renvoie une réponse.

➢ **DTO** (Data Transfer Object) : [Objet](#objet) dont le principal rôle est de transporter des données entre des processus, des applications ou des couches d'une application. Un DTO est généralement un objet simple, souvent sans logique métier, conçu uniquement pour contenir des données. Il contient principalement des [propriétés](#propriete) (ou [attributs](#attribut)), des [accesseurs](#accesseur) (getters et setters) et parfois un [constructeur](#constructeur). Les DTO sont couramment utilisés dans les architectures orientées services. Lorsqu'un [client](#client) envoie une requête à un [service](#service), les données sont souvent envoyées sous forme de DTO, et de même lorsque les données sont renvoyées du service au client.

➢ **Design Pattern** (Pattern) : Façon répétitive ou habituelle de faire quelque chose (bonne pratique).

➢ **Factorisation** (refactoring): Processus de restructuration du code existant sans changer son comportement externe afin  de regrouper des parties de code similaires ou répétitives en une seule structure, fonction ou module, afin de réduire la redondance, d'améliorer la lisibilité et de faciliter la maintenance future. Le terme peut aussi être utilisé pour décrire la simplification de l'expression ou de la structure du code.

➢ **Implémentation** : Réalisation concrète d'une fonctionnalité, d'une méthode ou d'une interface.

➢ **Injection** (de [dépendance](#dépendance)) : Technique consistant à insérer des [objets](#objet) dans une classe.

➢ **Injection** (de code) : Technique par laquelle un attaquant peut insérer ou "injecter" du code malveillant dans un système (ex: injection SQL ou de JS). 

➢ **Modèle** ([MVC](#mvc)) : Composante logiciel qui gère les données, la logique métier et les règles. Le modèle est responsable de l'accès aux données. Il sert de pont entre la base de données (ou toute autre source de données) et le contrôleur.

➢ **Modèle** (Entité/POO) : Désigne un schéma ou une structure de données qui illustre comment les différentes tables et relations sont organisées dans une base de données. Il s'agit de [classes](#classe) ou ensemble de classes représentant des [objets](#objet) ou des [entités](#entite) (et leurs relations) dans un système.

➢ <b id="mvc">MVC</b> (Model-View-Controller) : Modèle architectural pour développer des logiciels en séparant la logique métier, l'interface utilisateur et le contrôle de l'application.

➢ <b id="noeud">Nœud</b> : Élément individuel d'une structure de données, comme un [arbre](#arbre) ou une [Liste liée](#listeLiee).

➢ **REST** (Representational State Transfer) : Style architectural pour la conception de [services](#service) de réseau, souvent utilisé pour construire des ([API](#api)) web. 

➢ **Router** : Component qui détermine la manière dont une application répond à une demande [client](#client) pour une route, un URI (Uniform Resource Identifier) ou une [méthode](#methode) spécifique.

➢ <b id="service">Service</b> :  Composant ou module qui fournit une fonctionnalité spécifique à d'autres composants ou applications.


<br>

---

### <u>Les données/transferts :</u>
➢ **Bande passante** : Capacité maximale de transfert de données d'un point à un autre.

➢ **Cache** : Stockage temporaire de données pour des récupérations rapides.

➢ <b id="client">Client</b> : Programme ou système (ex : navigateur) qui demande un [service](#service) ou des ressources à un autre système distant, généralement appelé [serveur](#serveur).

➢ **Compilation** : Processus de transformation du code source de haut niveau (C#, Java, etc.) en un code machine ou en un code intermédiaire exécutable par un ordinateur.

➢ **Concurrence** : Exécution simultanée de plusieurs séquences d'opérations.

➢ **Data** : Données ou informations, souvent stockées ou traitées par des applications ou des bases de données.

➢ **Debordement de pile** (Stack Overflow) : Erreur qui se produit lorsque la [pile](#pile) atteint sa capacité maximale.

➢ **Deploiement** : Processus de mise en ligne (production) ou de distribution d'une application/système pour qu'elle soit opérationnelle.

➢ **Deserialisation** : Processus de conversion d'une représentation sérialisée en une structure de données/[objet](#objet) (inverse de la [sérialisation](#serialisation)).

➢ **File (Queue)** : Structure de données basée sur le principe Premier Entré, Premier Sorti (PEPS).

➢ **Garbage Collection** : Processus automatisé de récupération de la mémoire qui n'est plus référencée ou utilisée dans un programme.

➢ **GraphQL** : Langage de requête pour [API](#api), permettant au [client](#client) de demander uniquement les données qu'il souhaite.

➢ **Interpréteur** : Programme qui lit et exécute le code source ligne par ligne sans nécessité de le compiler.

➢ **Latence** : Délai entre une action et une réponse.

➢ **Lazy Loading** : Tactique de chargement de ressources uniquement lorsqu'elles sont nécessaires.

➢ **Metadonnée** : Données qui décrivent d'autres données. Par exemple, les informations sur la date de création d'un fichier.

➢ **Promesse** : [Objet](#objet) représentant la complétion ou l'échec éventuel d'une opération asynchrone.

➢ **Protocole** : Ensemble de règles et conventions pour la communication entre systèmes.

➢ **Paquet** : Unité de données envoyée sur un réseau.

➢ **Package** : Module ou ensemble de modules préemballés, souvent avec des [dépendances](#dependance), que l'on peut utiliser dans d'autres projets.

➢ <b id="pile">Pile</b> : Permet de gérer les appels et les retours de [fonctions](#fonction). Lorsqu'une fonction est appelée, un enregistrement est créé et ajouté au sommet de la pile d'appel.

➢ **Requête** : Demande d'information ou d'action à un système ou une base de données.

➢ **Runtime** : Temps pendant lequel un programme est en cours d'exécution.

➢ <b id="serialisation">Serialisation</b> : Processus de conversion d'un [objet](#objet) ou d'une structure de données en un format linéaire (binaire, XML, JSON, etc) = JSON.parse en JS, et ceux pour le stockage ou la transmission. 

➢ <b id="serveur">Serveur</b> :  Système ou application fournissant des ressources, des données ou des [services](#service) à des [clients](#client).

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

➢ **Middleware** : Logiciel qui agit comme un pont entre différents logiciels ou [services](#service). Dans les frameworks de développement web, comme Express pour Node, un middleware est une [fonction](#fonction) qui a accès aux [objets](#objet) de requête/réponse, et au prochain middleware dans le cycle de requête-réponse. Il peut exécuter n'importe quel code, effectuer des modifications aux objets de requête et de réponse, terminer le cycle de requête-réponse ou appeler le prochain middleware.

➢ **ORM** (Object-Relational Mapping) : Technique permettant de mapper et de synchroniser les données entre des systèmes de bases de données relationnelles et des objets orientés [objet](#objet).

➢ **SandBox** (bac à sable) :  Environnement de test isolé où les codes, les applications ou les fichiers peuvent être exécutés sans affecter l'application ou le système d'exploitation hôte.

➢ **VM** (Machine virtuelle) :  Logiciel simulant un environnement informatique et permettant d'exécuter des programmes comme s'ils fonctionnaient sur un ordinateur physique.

<br>

---

### <u>Vocabulaire Général:</u>
➢ **Asynchrone** : Opération qui s'exécute sans bloquer le déroulement principal et permettant à d'autres tâches de continuer simultanément.

➢ **Deboger** (débogage) : Processus d'identification et de correction d'erreurs ou de bugs dans un programme.

➢ **Deprecié** : Obsolescence d'une [fonction](#fonction) ou d'une [bibliothèque](#biblio) et qui pourrait être supprimée/remplacée dans les versions futures. 

➢ <b id="regex">Regex</b> (Expression régulière) : Séquence de caractères représentant un modèle de recherche dans un texte (ex: le modèle d'une adresse mail).

➢ <b id="versionning">Versionning</b> (sémantique) : Système de numérotation de versions basé sur trois numéros séparés de points (MAJEUR.MINOR.PATCH) pour signaler les types de modifications apportées.

➢ <b id="implementer">Implémenter</b> : Lorsqu'une classe fournit du code concret pour toutes les méthodes déclarées par une interface, on dit alors de cette classe qu'elle "implémente" une interface.

➢ <b id="semantique">Sémantique</b> : La sémantique traite du comportement attendu d'un programme lorsqu'il est exécuté. Elle fait ainsi référence au sens ou à la signification des programmes, indépendamment de leur syntaxe. Alors que la [syntaxe](#syntaxe) traite de la manière dont les programmes sont écrits, la sémantique concerne ce que fait le programme.

➢ <b id="syntaxe">Syntaxe</b> : Ensemble des règles qui définissent comment les programmes doivent être structurés (propre à chaque langage). Un programme qui viole ces règles entraînera généralement une erreur de syntaxe, indiquant que le code ne peut pas être compilé ou interprété correctement. Par exemple, oublier un point-virgule à la fin d'une instruction dans certains langages peut entraîner une erreur de syntaxe.

<br>

---

_Fin du glossaire._
