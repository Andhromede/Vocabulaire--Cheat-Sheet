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
➢ **Decorateur** :  Patron de conception où la responsabilité d'une [classe](#classe) est étendue dynamiquement à l'exécution.

➢ <b id="encapsulation">Encapsulation</b> : Restriction de l'accès direct aux composants ([attributs](#attribut)/[methodes](#methode)) d'un objet.

➢ <b id="attribut">Attribut</b> (variable membre) : [Variable](#variable) définie dans une [classe](#classe), représentant les [propriétées](#propriete) ou caractéristiques d'un objet.

➢ <b id="methode">Methode</b> : [Fonction](#fonction) définie dans une [classe](#classe) et qui représente les actions qu'un objet peut réaliser.

➢ **Constructeur** : [Méthode](#methode) spéciale d'une [classe](#classe) appelée lors de la création d'un objet.

➢ **Destructeur** : [Méthode](#methode) spéciale d'une [classe](#classe) appelée lors de la destruction d'un objet.

➢ **Accesseur** (Getter) : [Méthode](#methode) utilisée pour obtenir la valeur d'un [Attribut](#attribut).

➢ <b id="classAbstraite">Classe Abstraite</b> : [classe](#classe) qui ne peut pas être [instanciée](#instance) directement et est souvent utilisée comme base pour d'autres classes.

➢ **Méthode abstraite** : [Méthode](#methode) déclarée dans une [classe abstraite](#classAbstraite) qui n'a pas d'[implémentation](#implementation) dans cette même [classe](#classe), mais doit être implémentée par toutes les [sous-classes](#sousClass) non abstraites.

➢ **Visibilité** : Définit si un [attribut](#attribut) ou une [methode](#methode) est accessible en dehors de la [classe](#classe) ([public](#public), [private](#private), [protected](#protected)).

➢ **Mutateur** (Setter) : [Méthode](#methode) utilisée pour définir ou modifier la valeur d'un [attribut](#attribut).

➢ **Surcharge** (Overloading) : Définition de plusieurs [methodes](#methode) avec le même nom mais avec des [paramètres](#parametre) différents dans la même [classe](#classe).

➢ <b id="instance">Instance</b> : Objet créé à partir d'une [classe](#classe).

➢ **Instantiation** : Processus de création d'un objet à partir d'une [classe](#classe).

➢ **Abstraction** : Concept central de la POO où un modèle est créé en isolant des données et des fonctionnalités pertinentes.

➢ <b id="propriete">Propriete</b> (interface) : [encapsulation](#encapsulation) d'un [attribut](#attribut) qui permet d'acceder a celui-ci.

➢ <b id="superClass">SuperClasse</b> : [classe](#classe) mère/parent.   

➢ <b id="sousClass">Sous-classe</b> : [classe](#classe) enfant.   

➢ <b id="heritage">Heritage</b> : (multiple) mécanisme où une [classe](#classe) peut hériter des propriétés et méthodes d'une ou plusieurs autres classes. 

➢ **Composition** : Technique où une [classe](#classe) inclut une [instances](#instance) d'une autre classe comme l'un de ses [attributs](#attribut).

➢ **Association** : Relation générale entre les objets, indiquant qu'une [classe](#classe) utilise les fonctionnalités d'une autre classe.

➢ <b id="dependance">Dépendance</b> : Lien entre 2 morceaux de code où l'un nécessite la présence de l'autre.

➢ **Factory** (Fabrique) : Patron de conception pour créer des objets sans spécifier la [classe](#classe) exacte à instancier.

➢ **Singleton** : Patron de conception qui restreint l'instanciation d'une [classe](#classe) à un seul objet.

➢ **Agrégation** : Forme spéciale de composition où une [classe](#classe) contient une référence à un objet d'une autre classe, mais sans en prendre la propriété complète.

➢ **Interface** : ensemble de [méthodes](#methode) sans [implémentations](#implementation) que les [classes](#classe) doivent fournir. Elle permet à différents objets d'être traités comme des [instances](#instance) d'une interface commune, indépendamment de leur classe d'origine.

➢ <b id="polymorphisme">Polymorhpisme</b> : Capacité de prendre plusieurs formes. Souvent vu en POO lorsque des [classes](#classe) dérivées peuvent être traitées comme des [instances](#instance) de la [classe parente](#superClass).  

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
➢ **Argument** : [Variable](#variable) passée lors de l'appel d'une fonction.

➢ **Callback** : Fonction passée à une autre [fonction](#fonction) comme argument, qui sera exécutée après la fin de cette fonction.

➢ **Conditionnelle** : Structure permettant d'exécuter du code en fonction d'une condition.

➢ <b id="fonction">Fonction</b> : Bloc de code réutilisable qui effectue une tâche spécifique.

➢ <b id="listeLiee">Liste liée</b> : Collection d'éléments ordonnés où chaque élément [pointe](#pointeur) vers le suivant.

➢ **Paramètre** : [Variable](#variable) déclaré dans la définition d'une [Fonction](#fonction).

➢ <b id="procedure">Procedure</b> :  Série d'étapes ou d'instructions organisées de manière séquentielle, destinées à accomplir une tâche ou à réaliser un objectif spécifique.

➢ **Recurssion** : (récursivité) Mécanisme où une [Fonction](#fonction) s'appelle elle-même.

➢ <b id="variable">Variable</b> : Emplacement de stockage pour une valeur.

<br>

---

### <u>L'Architecture :</u>
➢ <b id="api">API</b> : Ensemble de [Fonctions](#fonction) et [Procédures](#procedure) qui permettent la création d'applications.

➢ **API Endpoint** : URL spécifique où une [API](#api) peut être accessible et où les opérations peuvent être effectuées.

➢ **Arbre** : Structure de données hiérarchique composée de [nœuds](#noeud).

➢ **Implémentation** : processus de traduction d'une idée, d'une conception ou d'une spécification en quelque chose de concret (du code).

➢ **Injection** : Technique où le code est introduit ou "injecté" dans un programme/app.

➢ **MVC** (Model-View-Controller) : Modèle d'architecture logicielle séparant la logique métier, l'interface utilisateur et le contrôle.

➢ <b id="noeud">Nœud</b> : Élément fondamental de nombreuses structures de données, comme les [Listes liées](#listeLiee).

➢ **Pattern** : Solution réutilisable à un problème couramment rencontré.

➢ **Refactoring** : Processus de restructuration du code existant sans changer son comportement extérieur.

➢ **REST** ([API](#api)) : Style d'architecture pour la conception de réseaux d'applications .

➢ **Sémantique** : Signification des structures et [expressions](#regex) dans un langage de programmation.

<br>

---

### <u>Les données/transferts :</u>
➢ **Bande passante** : Capacité maximale de transfert de données d'un point à un autre.

➢ **Cache** : Stockage temporaire de données pour des récupérations rapides.

➢ **CI/CD** : (Intégration Continue / Livraison Continue) Pratiques d'ingénierie logicielle pour intégrer fréquemment et déployer automatiquement.

➢ <b id="client">Client</b> : Machine ou application qui demande des ressources à un [serveur](#serveur) (ex : navigateur).

➢ **Compilation** : Processus de transformation du code source de haut niveau (C#, Java, etc.) en un code machine ou en un code intermédiaire exécutable par un ordinateur.

➢ **Concurrence** : Plusieurs tâches exécutées en parallèle mais pas nécessairement en même temps.

➢ **Debordement de pile** (Stack Overflow) : Erreur qui se produit lorsque la [pile](#pile) atteint sa capacité maximale.

➢ **Deploiement** : Processus de mise en ligne ou d'installation d'une application pour qu'elle soit opérationnelle.

➢ **Deserialisation** : Processus inverse de la [sérialisation](#serialisation), convertissant une [chaîne de données](#string) stockée ou transmise en un objet.

➢ **File (Queue)** : Structure de données basée sur le principe Premier Entré, Premier Sorti (PEPS).

➢ **Garbage Collection** : Processus automatique de récupération de la mémoire non utilisée.

➢ **GraphQL** : Langage de requête pour [API](#api), permettant au [client](#client) de demander uniquement les données qu'il souhaite.

➢ **Interpréteur** : Programme qui exécute du code source ligne par ligne.

➢ **Latence** : Délai entre une action et une réponse.

➢ **Lazy Loading** : Technique de chargement de ressources uniquement lorsque cela est nécessaire.

➢ **Promesse** : Objet représentant la fin éventuelle (ou le non-achèvement) d'une opération asynchrone.

➢ **Protocole** : Ensemble de règles pour la communication entre machines.

➢ **Paquet** : (Package) Module ou ensemble de modules préemballés, souvent avec des [dépendances](#dependance), que l'on peut utiliser dans d'autres projets.

➢ <b id="pile">Pile</b> : permet de gérer les appels et les retours de [fonctions](#fonction). Lorsqu'une fonction est appelée, un enregistrement est créé et ajouté au sommet de la pile d'appel.

➢ **Requête** : Demande d'information ou d'action à un système ou une base de données.

➢ **Runtime** : Temps pendant lequel un programme est en cours d'exécution.

➢ <b id="serialisation">Serialisation</b> : convertion d'objets en un format de données afin d'etre stocker ou transmis (binaire, XML, JSON, etc) = JSON.parse en JS.

➢ <b id="serveur">Serveur</b> : Machine ou application qui fournit des ressources aux [clients](#client).

➢ **Socket** : Point de terminaison pour envoyer ou recevoir des données à travers un réseau.

➢ **Synchronisation** : Coordonner l'exécution de plusieurs [threads](#thread).

➢ <b id="thread">Thread</b> : Unité la plus petite de traitement exécutée par un système d'exploitation.

➢ **Webhook** : [Méthode](#methode) permettant à une application d'envoyer des données en temps réel à d'autres applications dès qu'un événement se produit.

<br>

---

### <u>L'environnement :</u>
➢ <b id="biblio">Bibliothèque</b> : (library) Collection de [fonctions](#fonction) et de [routines](#routine) réutilisables.

➢ <b id="container">Container</b> : Technologie qui [encapsule](#encapsulation) une application et ses [dépendances](#dependance) dans un objet unique.

➢ **Docker** : Plateforme pour développer, expédier et exécuter des applications à l'intérieur de [conteneurs](#container).

➢ **Framework** : Ensemble d'outils et de [bibliothèques](#biblio) pour faciliter le développement.

➢ **Git** : Logiciel de versionning pour le suivi des modifications du code source et fonctionnant a un niveau atomique.

➢ **IDE** : Outil logiciel pour écrire, tester et déboguer du code.

➢ **Middleware** : Logiciel qui agit comme un pont entre différents logiciels ou services.

➢ **ORM** (Object-Relational Mapping) : Technique de liaison entre des objets et des données stockées dans des bases de données relationnelles.

➢ **SandBox** (bac à sable) : Environnement isolé pour exécuter des programmes, souvent utilisé pour tester ou exécuter du code non sûr.

➢ **VM** (Machine virtuelle) : Émulation d'un système informatique qui exécute des programmes comme s'ils tournaient sur une machine physique.

<br>

---

### <u>Vocabulaire :</u>
➢ **Depreciation** : Obsolescence d'une [fonction](#fonction) ou d'une [bibliothèque](#biblio) et qui pourrait être supprimée/remplacée dans les versions futures. 

➢ <b id="regex">Regex</b> (Expression régulière) : Séquence de caractères représentant un modèle de recherche dans un texte.

<br>

---

_Fin du glossaire._
