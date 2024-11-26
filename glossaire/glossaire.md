Général
Quel est l’environnement à installer pour exécuter un script PHP ? Citer 2 exemples de logiciels permettant ce contexte
Logiciel gérant Apache et SQL
Laragon ou WAMP
Qu’est-ce qu’un algorithme ?
Définition d'une suite d'instruction permettant de retourner un resultat
Qu’est-ce qu’une variable ? Par quel symbole est préfixée une variable en PHP ?
élément qui associe un nom à une valeur qui sera implanté dans le processus d'un algorithme. Peut changer de valeur en cours de programme. Peut être de plusieurs type :
chaine de caractère, entier, réel, bool
Qu’est-ce que la portée d’une variable ?
zone de l'algorithme où elle est déclarée
Qu’est-ce qu’une constante ? Quelle est la différence avec une variable ?
C'est une valeur associée à un nom qui n'a pas pour but d'être modifiée, contrairement à la variable
Qu’est-ce qu’une superglobale, combien en existent-ils et donner un exemple d’utilisation
Variable qui est disponible dans le code, acceessibles depuis n'importe quelle fonction. Il en existe 9. 
ex. : $x  =  $_GET['x'];
Quels sont les différents types (primitifs) que l’on peut associer à une variable en PHP ? Les citer et en donner des exemples (ne pas oublier le type d’une variable sans valeur)
- Entiers (INT) : nombre sans décimales - 
	$x=1
- Flottant (FLOAT) : nombre décimal - 
	$x=1.5
- Bolléen (BOOL) : valeur binaire - TRUE ou FALSE - $x=TRUE
- Chaine de caractère (STRING) : séquence de caractère (groupe de mots) - 
	$x='Hello World'
- Tableaux (ARRAY) : collection d'éléments pouvant être de types différents - 
	$x=[1, 'Hello World', 'TRUE']
- Valeur Nulle (NULL) : Variable qui n'a pas de valeur -
	$x=NULL
Existe-t-il plusieurs types de tableaux en PHP, si oui lesquels ?
oui, les tableaux statiques, qui ne contiennent que des données, et les tableaux associatifs, qui contiennent des données clés associés chacunes associées à des valeurs 
Quelles sont les différentes structures de contrôles qu’il existe en algorithmie ? Donner un exemple pour chacune d’entre elles
-les structures séquentielles, le code sera éxécuté ligne après ligne
-les structures conditionnelles (IF-ELSE), le code sera éxécuté si une condition prévue est vraie, sinon un autre code se lancera si la condition est fausse
-les structures itératives (Boucles FOR - WHILE - Foreach), répète un nombre d'instruction. FOR : un nombre déterminé de fois. WHILE : se répète tant que la condition est vraie. Foreach : se répète pour chaque valeur d'un tableau
Quelle est la fonction PHP permettant de demander la longueur d’une chaîne de caractères ?
strlen
Qu’est-ce qu’une session ? Quelle fonction permet de démarrer une session en PHP ? Donner un exemple d’utilisation en PHP
permet au navigateur de garder en mémoire les informations les informations de l'utilisateur, stocké coté serveur. session_start(). 
 

Qu’est-ce qu’un cookie ? Donner un exemple d’utilisation en PHP !! Donner un exemple !!
Fichier stocké sur l'appareil de l'utilisateur permettant de stocker ses informations  (authentification, statistiques, ...) et récupérable automatiquement lors de chaque visite sur un site web
Quelle est la différence entre les instructions « require » et « include » en PHP
Require inclura le fichier et arrêtera sa lecture puis affichera une erreur en cas d'indisponibilité. 
Include inclura le fichier et continuera d'essayer de le lire, même si celui ci est indisponible
Comment effectuer une redirection en PHP ?
avec la fonction: header(location:exemple.php)
Définir la partie « front-end » et « back-end » d’une application
Le front end va se charger la partie client, visuelle, du site web, que ce soit sa structure ou ses animations.
Le back end va se charger de la partie serveur d'un site, que ce soit sa connexion à la base de données, l'envoi des formulaires, la connexion entre les différentes pages
Définir le contrôle de version ? Qu’est-ce que Git ?
permet de garder d'enregistrer les modifications d'un code source et de gérer la collaboration sur la création d'une application. Permet aussi de garder un historique de l'avancement du projet.
Git est un système de contrôleur de version (voir définition précédente)
Qu’est-ce qu’un CMS ? Citer au moins 2 exemples
Content Management Systems. 
Application permettant la création et la gestion du contenu d'un site web sans besoin de code.
Ex : Wordpress et Joomla!
Front-end
Définir HTML
Langage de programmation permettant de créer la structure d'un site
Définir CSS
Langage de programmation permettant la stylisation d'un site
Définir Javascript
Langage de programmation Front end, gérant aussi le back end, permettant de créer des animations visuelles sur un site web, comme les évènement lors d'un clic sur une icone par exemple.
Définir JSON. Dans quel contexte ce format est-il utilisé ? !! réponse à venir !!
Peut-on interpréter du Javascript côté serveur ? Si oui, comment ?
oui, en utilisant un environnement de travail spécialisé, comme NODE.JS
Qu’est-ce qu’un sélecteur CSS ?
un sélecteur CSS cible une balise HTML précise pour lui donner un style voulu grâce aux propriétés
Quelle balise HTML permet de créer un lien hypertexte ?
<a href="exemple.php">nom_du_lien</a>
Qu’est-ce qu’une requête AJAX ? !! réponse à venir !!
Quel sélecteur CSS permet de sélectionner tous les éléments d’une classe spécifique ? D’un identifiant spécifique ?
classe spécifique : . - exemple : .classe{}
identifiant spécifique : # - exemple : #identifiant{}
Définir le responsive design
Adapte le contenu desktop d'un site à tout type d'écran
Qu’est-ce que le templating ?
Permet la gestion du contenu commun à plusieurs pages sur un seul et même fichiers partagé entre ces mêmes pages
Qu’est-ce qu’une fonction anonyme en Javascript ? !! réponse à venir !!
Quelle méthode JavaScript est utilisée pour ajouter un élément à la fin d'un tableau ?
push()
Qu’est-ce qu’un « media query » ?
Un media query (@media) permet de définir le style d'un contenu en fonction d'une taille d'écran spécifiée
Qu’est-ce qu’un pseudo élément en CSS ?
Cible et stylise un élément spécifique (ex : p::first-letter {}) sans toucher au code HTML de la page
Qu’est-ce que Bootstrap ? Donner d’autres exemples équivalent !! réponse à venir !!
Quand un formulaire HTML est créé, quelles sont les 2 méthodes qui peuvent lui être associées ? Donner la différence entre ces 2 méthodes
POST : passe les informations du formulaire dans le corps des requêtes du code
GET : passe les informations du formulaire dans l'URL de la page
UX UI
Quelle est la différence entre UX Design et UI Design ?
Qu’est-ce qu’un wireframe ?
Qu’est-ce qu’un prototype ?
Qu’est-ce que la hiérarchie visuelle en UI Design ?
Qu’est-ce que l’accessibilité en UX Design ?
Qu’est-ce qu’une grille de mise en page ?
Qu’est-ce que la notion d’affordance en UX Design ?
Qu’est-ce qu’un « mobile first design » ?
Programmation orientée objet (POO)
Donner une définition de la programmation orientée objet
méthode de programmation basé sur la création et la définition des propriétés et des méthodes d'une classe permettant la création d'objets
Qu’est-ce qu’une classe ? Comment la déclare-t-on ?
modèle pour créer des objets définissant les méthodes et les propriétés de ceux-ci
Qu’est-ce qu’un objet ?
entité regroupant les propriétés et méthodes de la classe qui le défini
Définir la notion de propriété / attribut / méthode
propriété : représente la variable associé à un objet et définie dans sa classe
attribut : !! réponse à venir !!
méthode : fonction définie dans la classe interprétant le comportement de l'objet

Qu’est-ce que la visibilité d’une propriété ou d’une méthode ? Citer les différents types de visibilité
la visibilité détermine la portée d'utilisation d'une propriété ou d'une méthode. Private : utilisable que la classe définie Public : utilisable n'importe où Protected : utilisable par sa classe et ses childs (son héritage)
Quelle est la méthode spécifique utilisée pour créer un nouvel objet à partir d’une classe ?
$objet = new Nom_Classe();
Qu’est-ce que l’encapsulation ?
Que signifie « étendre une classe » ? Quelle est le concept clé mis en œuvre ? Donner un exemple
Définir l’opérateur de résolution de portée
Définir une méthode / propriété statique
Définir le polymorphisme en POO
Définir une méthode / classe abstraite ?
Définir le chaînage de méthodes
Qu’est-ce que la méthode __toString() ? Existe-t-il d’autres méthodes « magiques »
Qu’est-ce qu’un « autoload » ?
Comment appelle-t-on en français les « getters » et les « setters » ?
Qu’est-ce que la sérialisation en PHP ?
Architecture
Qu’est-ce que l’architecture client / serveur ? Grâce à quel type de requête peut-on interroger le serveur. Définir l’acronyme de ce type de requête. Si on ajoute un « S » à cet acronyme, expliquer la différence
Donner la définition d’un design pattern. Citer au moins 3 exemples de design pattern
Qu’est-ce que l’architecture MVC ?
Quel est le rôle de chaque couche du design pattern MVC : Model, View, Controller ?
Quels sont les avantages de l’architecture MVC ?
Existe-t-il des variantes à l’architecture MVC ?
Qu’est-ce qu’une API ? Définir l’architecture REST
Modélisation - Base de données
Qu’est-ce que la modélisation de données ? Définir la méthode Merise
Quelles sont les 3 étapes principales de la méthode Merise ? a. Analyse, conception et réalisation b. Planification, exécution et contrôle c. Création, modification et suppression
Qu’est-ce qu’un modèle conceptuel de données (MCD) en Merise ?
Qu’est-ce qu’un modèle logique de données (MLD) en Merise ?
Donner la définition des mots suivants : a. Entité b. Relation c. Cardinalité d. Clé primaire / clé étrangère
Que devient une relation de type « Many To Many » dans le modèle logique de données ?
Qu’est-ce qu’une base de données ?
Définir les notions suivantes : a. SQL b. MySQL c. SGBD (donner 2 exemples de SGBD)
Dans une base de données, les données sont stockées dans des ___. Celles-ci sont constituées de lignes appelées ___ et de colonnes appelées ___
Quelle est la différence entre une base de données relationnelle et non relationnelle ?
Qu’est-ce qu’une jointure dans une base de données ? En existe-t-il plusieurs ? Si oui lesquelles ?
A quoi sert une vue dans une base de données ?
Qu’est-ce que l’intégrité référentielle dans une base de données ?
Quelles sont les fonctions d’agrégation en SQL ?
Qu’est-ce qu’un CRUD dans le contexte d’une base de données ?
Quelles sont les clauses qui permettent de : a. Insérer un nouvel enregistrement dans une table b. Modifier un enregistrement dans une table c. Supprimer un enregistrement dans une table d. Supprimer la base de données e. Filtrer les résultats d’une requête SQL f. Trier les résultats d’une requête SELECT g. Regrouper les résultats d'une requête SELECT en fonction d'une colonne spécifique h. Concaténer 2 chaînes de caractères
Comment se connecter à une base de données en PHP ? Quelle est la classe native utilisée ?
Symfony
Qu’est-ce que Symfony ?
Sur quel langage de programmation et design pattern repose Symfony ?
Quelle est la dernière version en date de Symfony ?
Qu’est-ce qu’un bundle ?
Quel est le moteur de template utilisé par défaut dans Symfony ?
Qu’est-ce qu’un ORM ? Quel est son utilité et comment s’appelle-t-il au sein de Symfony ?
Qu’est-ce que l’injection de dépendances ? Quel est l’outil utilisé dans ce contexte et quel fichier contient l’intégralité des dépendances du projet ?
Que permet le bundle Maker au sein de Symfony ?
Quel est le langage de requêtage exploité au sein d’un projet Symfony ?
Quel est le composant qui garantit l’authentification et l’autorisation des utilisateurs ?
Sécurité
Qu’est-ce que l’injection SQL ? Comment s’en prémunir ?
Qu’est-ce que la faille XSS ? Comment s’en prémunir ?
Qu’est-ce que la faille CSRF ? Comment s’en prémunir ?
Définir l’attaque par force brute et l’attaque par dictionnaire
Existe-t-il d’autres failles de sécurité ? Citer celles-ci et expliquer simplement leur comportement
A quoi servent l’authentification et l’autorisation dans un contexte d’application web ?
Définir la notion de hachage d’un mot de passe et citer des algorithmes de hachage
Qu’est-ce qu’une politique de mots de passe forts ?
Qu’est-ce que l’hameçonnage ?
Définir la « validation des entrées »
RGPD
Qu’est-ce que le RGPD ?
Quel est son objectif principal ?
Quelle est la date d’entrée en vigueur du RGPD ?
Quelles sont les sanctions possibles en cas de non-respect du RGPD ?
En France, quel est l’autorité administrative qui s’occupe de faire appliquer le RGPD ?
Quel est le consentement valide selon le RPGD ?
Qu’est-ce qu’une politique de confidentialité ?
Quelle est la durée de conservation maximale des données personnelles selon le RGPD ?
Quels sont les droits des utilisateurs selon le RGPD ?
Qu’est-ce que le principe de minimisation des données selon le RGPD ?
SEO
Qu’est-ce que le SEO ?
Quel est l’objectif principal du SEO ?
Existe-t-il plusieurs types de référencement ? Lesquels ?
Qu’est-ce que la densité de mots-clés en SEO ?
Qu’est-ce qu’une balise « alt » ?
Qu’est-ce que la balise « meta description » ?
Qu’est-ce que le « nofollow » en SEO ?
Quelle est l'importance du contenu de qualité pour le référencement d'un site web ?
Pourquoi est-il important d'utiliser des balises de titre (h1, h2, h3, etc.) de manière structurée ?
Quelle est la recommandation pour les URL d'un site web bien référencé ?
Qu'est-ce que le maillage interne et pourquoi est-il important pour le référencement ?
Qu'est-ce que l'optimisation des images pour le référencement ?
Qu'est-ce qu'un plan de site (sitemap) et pourquoi est-il important pour le référencement ?
Gestion de projets - DevOps
Qu’est-ce que la gestion de projet ?
Qu’est-ce qu’une méthode Agile de gestion de projet ?
Expliquer la méthode MoSCoW en quelques lignes et citer ses avantages
A quoi sert la méthodologie MVP ? Citer les caractéristiques clés
Qu’est-ce que la planification itérative ?
Citer 3 méthodes Agiles dans le cadre d’un projet informatique
Qu’est-ce qu’une réunion de revue de projet ?
Qu’est-ce qu’un livrable dans un projet ?
Quels sont les 3 piliers SCRUM ? Définir chacun d’entre eux
Qu’est-ce que le DevOps et quel est son objectif principal ?
Qu’est-ce que l’intégration continue ?
Qu’est-ce que Docker ? Et en quoi est-il utile dans le cadre du DevOps ?
Qu’est-ce qu’un test unitaire ?
Quelle est l'unité de code testée lors d'un test unitaire ?
Quelles sont les caractéristiques d'un bon test unitaire ?
Qu'est-ce qu'une assertion dans un test unitaire ?  
English
1) What does JavaScript enable you to do on a website ? a. Add interactive behavior and dynamic content b. Define the layout and design of web pages c. Handle server-side operations 2) Which programming language is primarily used for server-side web development ? a. PHP b. JavaScript c. HTML 3) What is the purpose of a web browser ? a. To render and display web pages b. To execute serve-side code c. To manage databases 4) What is the difference between GET and POST methods in HTTP ? a. GET retrieves data from a server, while POST submits data to a server b. GET submits data to a server, while POST retrieves data from a server c. GET and POST methods are interchangeable 5) What is the purpose of version control systems (e.g., Git) in web development ? a. To track changes and manage collaborative development b. To optimize website loading speed c. To handle server-side scripting 6) What is the purpose of a framework in web development ? a. To provide a structured environment for building web applications b. To handle network protocols and data transfer c. To create visual designs and layouts for websites 7) What does NoSQL stand for ? a. Not Only SQL b. Non-Structured Query Language c. New Object-Oriented Language 8) Which of the following is a characteristic of NoSQL databases ? a. Strict schema enforcement b. Support for complex transactions c. Scalability and flexible data models
