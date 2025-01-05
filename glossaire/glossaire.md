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

permet au navigateur de garder en mémoire les informations les informations de l'utilisateur, stocké coté serveur. 
session_start(). 
 

Qu’est-ce qu’un cookie ? Donner un exemple d’utilisation en PHP 

!! Donner un exemple !!

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

HyperText Markup Language. Langage de programmation permettant de créer la structure d'un site

Définir CSS

Cascading StyleSheet. Langage de programmation permettant la stylisation d'un site

Définir Javascript

Langage de programmation Front end, gérant aussi le back end, permettant de créer des animations visuelles sur un site web, comme les évènement lors d'un clic sur une icone par exemple.

Définir JSON. Dans quel contexte ce format est-il utilisé ? 

Format léger de données pris en charge par quasiment presques tous les langages, bien que dérivé de Javascript.
Utilisé dans la communication client-serveur ou le stockage léger de données

Peut-on interpréter du Javascript côté serveur ? Si oui, comment ?

oui, en utilisant un environnement de travail spécialisé, comme NODE.JS

Qu’est-ce qu’un sélecteur CSS ?

un sélecteur CSS cible une balise HTML précise pour lui donner un style voulu grâce aux propriétés

Quelle balise HTML permet de créer un lien hypertexte ?

<a href="exemple.php">nom_du_lien</a>

Qu’est-ce qu’une requête AJAX ?

(Asynchronous JavaScript and XML) Technique utilisée pour envoyer et recevoir des données entre le client et le serveur sans recharger la page

Quel sélecteur CSS permet de sélectionner tous les éléments d’une 
classe spécifique ? D’un identifiant spécifique ?

classe spécifique : . - exemple : .classe{}
identifiant spécifique : # - exemple : #identifiant{}

Définir le responsive design

Adapte le contenu desktop d'un site à tout type d'écran

Qu’est-ce que le templating ?

Permet la gestion du contenu commun à plusieurs pages sur un seul et même fichiers partagé entre ces mêmes pages

Qu’est-ce qu’une fonction anonyme en Javascript ?

Fonction qui n’a pas de nom et utilisée immédiatement

Quelle méthode JavaScript est utilisée pour ajouter un élément à la fin d'un tableau ?

push()

Qu’est-ce qu’un « media query » ?

Un media query (@media) permet de définir le style d'un contenu en fonction d'une taille d'écran spécifiée

Qu’est-ce qu’un pseudo élément en CSS ?

Cible et stylise un élément spécifique (ex : p::first-letter {}) sans toucher au code HTML de la page

Qu’est-ce que Bootstrap ? Donner d’autres exemples équivalent !!

Framework CSS simplifiant la mise en place du responsive par l'utilisation de classes prédéfinies reliées à des sélécteurs prédéfinis.
Equivalents : Tailwind CSS, Pure CSS

Quand un formulaire HTML est créé, quelles sont les 2 méthodes qui peuvent lui être associées ? Donner la différence entre ces 2 méthodes

POST : passe les informations du formulaire dans le corps des requêtes du code
GET : passe les informations du formulaire dans l'URL de la page

UX UI

Quelle est la différence entre UX Design et UI Design ?

UX design : Experience Utilisateur - s'intéresse à la manière dont l'utilisateur interagit avec le produit
UI Design : Interface Utilisateur - s'interesse à l'apparence directe de l'interface (bouton, police, couleur, ...
)
Qu’est-ce qu’un wireframe ?

Représentation visuelle simple de l'interface utilisateur

Qu’est-ce qu’un prototype ?

Première version intéractive d'un produit plus aboutie qu'un wireframe d'une application 

Qu’est-ce que la hiérarchie visuelle en UI Design ?

Organisation visuelle des éléments d'une application permettant de guider l'utilisateur

Qu’est-ce que l’accessibilité en UX Design ?

La mise en place d'interaction permettant une meilleure prise en main de l'application par les personnes handicapées

Qu’est-ce qu’une grille de mise en page ?

Ensemble de lignes et de colonnes utilisés pour structurer des éléments

Qu’est-ce que la notion d’affordance en UX Design ?

Lorsqu'un élément suggère son utilisation par son apparence

Qu’est-ce qu’un « mobile first design » ?

Le fait de penser le design d'une app d'abord pour une utilisation mobile plutot qu'une utilisation desktop 

Programmation orientée objet (POO)

Donner une définition de la programmation orientée objet

méthode de programmation basé sur la création et la définition des propriétés et des méthodes d'une classe permettant la création d'objets

Qu’est-ce qu’une classe ? Comment la déclare-t-on ?

modèle pour créer des objets définissant les méthodes et les propriétés de ceux-ci

Qu’est-ce qu’un objet ?

entité regroupant les propriétés et méthodes de la classe qui le défini

Définir la notion de propriété / attribut / méthode

propriété : contrôle l'accès et la modification d'un attribut (getters/setters)
attribut : variables définies représentant les données d'une classe
méthode : fonction définie dans la classe interprétant le comportement de l'objet

Qu’est-ce que la visibilité d’une propriété ou d’une méthode ? Citer les différents types de visibilité

la visibilité détermine la portée d'utilisation d'une propriété ou d'une méthode. 

Public : utilisable partout
Private : utilisable que la classe définie Public : utilisable n'importe où Protected : utilisable par sa classe et ses childs (son héritage)

Quelle est la méthode spécifique utilisée pour créer un nouvel objet à partir d’une classe ?

$objet = new Nom_Classe();

Qu’est-ce que l’encapsulation ?

consiste à protéger les données d'un objet en limitant leur accès direct. Les données sont rendues privées et leur accès et modification controlé par des getters et des setters

Que signifie « étendre une classe » ? Quelle est le concept clé mis en œuvre ? Donner un exemple

Le fait de créer une classe enfant depuis une classe parent. Le concept d'Héritage est mis en oeuvre.  

Class Parent {}
Class Enfant Extends Parent {}

Définir l’opérateur de résolution de portée

opérateur de résolution de portée = ::
Permet d'accéder à des méthodes des classes parents 

Définir une méthode / propriété statique

Methode / Propriété accessible sans avoir besoin de créer une instance de cette classe 

Définir le polymorphisme en POO

Permet à différentes classes d’avoir une méthode avec le même nom, mais avec des comportements différents selon le type d’objet qui l’appelle

Définir une méthode / classe abstraite ?

Une méthode abstraite est défini dans une classe abstraite parent, dont le fonctionnement sera propre aux enfants 

Définir le chaînage de méthodes

permet d'éxécuter plusieurs actions sur un objet dans une seule ligne avec $this

Qu’est-ce que la méthode __toString() ? Existe-t-il d’autres méthodes « magiques »

__tostring définis comment un objet se convertira en chaine de caractères
exemple de méthodes magiques :
__construct(), __get($property, $value), __invoke(), _isset() et unset()

Qu’est-ce qu’un « autoload » ?

permet de charger automatiquement les classes d'un script, plus besoin de les inclures manuellement

Comment appelle-t-on en français les « getters » et les « setters » ?

getters : accesseurs et setters: mutateurs

Qu’est-ce que la sérialisation en PHP ?

Converti un objet en chaine de caractère pour le stocker 
Exemple : 	$personne = new Personne("Alice", 25);
			$chaine = serialize($personne);

Architecture


Qu’est-ce que l’architecture client / serveur ? Grâce à quel type de requête peut-on interroger le serveur.

Modèle ou le client et le serveur collaborent :
Client : Navigateur Web - envois une requete
Serveur : renvoi l'information demandé par le client 
Requête : HTTP / HTTPS

Définir l’acronyme de ce type de requête. Si on ajoute un « S » à cet acronyme, expliquer la différence

HyperText Transfer Protocol - HyperText Transfer Protocol Secure 
HTTPS chiffre les données tranférées entre le client et le serveur

Donner la définition d’un design pattern. Citer au moins 3 exemples de design pattern

Modèle de conception réutilisable et éprouvé permettant d'organiser son code.
Exemple : Singleton, Observer, Factory Method

Qu’est-ce que l’architecture MVC ?

Modèle Vue Contrôleur. Modèle de conception séparant la logique métier (Model), l'affichage (View) et les interactions (Controller). 

Quel est le rôle de chaque couche du design pattern MVC : Model, View, Controller ?

Model : Gère l'accès à la base de données
View : Gère et génère l'affichage des données
Controller : Reçoit les requêtes, appelle  le model et récupère les données pour choisir la view à adopter

Quels sont les avantages de l’architecture MVC ?

Sépare les responsabilités, Maintenance facilitée

Existe-t-il des variantes à l’architecture MVC ?

Oui, l'architecture MVP : Modèle Vue Présentateur

Qu’est-ce qu’une API ? Définir l’architecture REST

API : Application Programming Interface - Interface qui permet à deux applications de communiquer entre elles. Représente un enemble de règles pour accéder aux fonctionnalités d'une application
Representational State transfer, permet à des applications de communiquer entre elles via des requêtes HTTP

Modélisation - Base de données

Qu’est-ce que la modélisation de données ? Définir la méthode Merise

processus de structuration et d'organiser les données d'un système pour représenter ses entités, leurs attributs, et leurs relations.
méthode d'analyse de données sur 3 niveaux : conceptuel, organisationnel et physique pour modéliser les données (MLD)

Quelles sont les 3 étapes principales de la méthode Merise ? 

a. Analyse, conception et réalisation 

Qu’est-ce qu’un modèle conceptuel de données (MCD) en Merise ?

représentation abstraite des données d'un système, mettant en avant les entités, et les relations

Qu’est-ce qu’un modèle logique de données (MLD) en Merise ?

Modèle reprenant le MCD et intégrant les clés primaires et étrangères et les types de données

Donner la définition des mots suivants : 

a. Entité : Représente un objet 
b. Relation : Lien logique entre deux entités
c. Cardinalité :  Indique le nombre minimal et maximal de relations possibles entre les entités
d. Clé primaire / clé étrangère : 
	Primaire : Identifiant unique d'une entité ou table
	Etrangère : Attribut reliant une table à une autre via une clé primaire

Que devient une relation de type « Many To Many » dans le modèle logique de données ?

Devient une table associative

Qu’est-ce qu’une base de données ?

Une base de données est un ensemble de données stockées dans des tables représentant les entités d'un MCD

Définir les notions suivantes : 
a. SQL : (Structured Query Language) langage utilisé pour interroger, manipuler, et gérer les bases de données relationnelles
b. MySQL : système de gestion de base de données relationnelle open-source, utilisé pour stocker et gérer des données
c. SGBD (donner 2 exemples de SGBD) : (Système de Gestion de Base de Données) : Un SGBD est un logiciel permettant de stocker, gérer et interroger des bases de données
	ex : MySQL et PostgreSQL

Dans une base de données, les données sont stockées dans des tables. Celles-ci sont constituées de lignes appelées enregistrement et de colonnes appelées attribut

Quelle est la différence entre une base de données relationnelle et non relationnelle ?

Relationnelle : Utilise des tables avec des schémas fixes, des relations entre les entités, et des données stockées selon des modèles rigides

Non Relationnelle : Ne repose pas sur des tables et schémas fixes,  Stocke les données sous forme de documents, graphes ou clés-valeurs

Qu’est-ce qu’une jointure dans une base de données ? En existe-t-il plusieurs ? Si oui lesquelles ?

combine les données de deux ou plusieurs tables en fonction d'une clé commune

Jointure Interne (INNER JOIN) et Jointure externe (LEFT JOIN / RIGHT JOIN)

A quoi sert une vue dans une base de données ?

permet de créer une "table virtuelle" qui affiche des données provenant de plusieurs tables ou d'une requête spécifique, sans modifier les données originales.

Qu’est-ce que l’intégrité référentielle dans une base de données ?

veille à ce que les relations entre les tables respectent les contraintes définies, en empêchant l'insertion, la mise à jour ou la suppression de données qui violeraient ces relations

Quelles sont les fonctions d’agrégation en SQL ?

SUM - AVG - COUNT - MIN - MAX - GROUP BY

Qu’est-ce qu’un CRUD dans le contexte d’une base de données ?

Create Read Update Delete

Quelles sont les clauses qui permettent de : 
a. Insérer un nouvel enregistrement dans une table : INSERT INTO
b. Modifier un enregistrement dans une table : UPDATE
c. Supprimer un enregistrement dans une table : DELETE FROM
d. Supprimer la base de données : DROP
e. Filtrer les résultats d’une requête SQL : WHERE
f. Trier les résultats d’une requête SELECT : ORDER BY
g. Regrouper les résultats d'une requête SELECT en fonction d'une colonne spécifique : GROUP BY
h. Concaténer 2 chaînes de caractères : CONCAT()


Comment se connecter à une base de données en PHP ? Quelle est la classe native utilisée ?

Utilisation de la classe PDO

voir exemple ici : 

$dsn = 'mysql:host=localhost;dbname=nom_base_de_donnees';
$username = 'utilisateur';
$password = 'mot_de_passe';

try {
    $pdo = new PDO($dsn, $username, $password);
    $pdo->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
    echo "Connexion réussie !";
} catch (PDOException $e) {
    echo "Erreur de connexion : " . $e->getMessage();
}

PDO permet de connecter et d’interagir avec différents types de bases de données de manière uniforme.

Symfony

Qu’est-ce que Symfony ?

Framework PHP, permet une strucutre cohérente et offre des outils facilitant la création d'application web

Sur quel langage de programmation et design pattern repose Symfony ?

Language : PHP 
Design pattern : MVC

Quelle est la dernière version en date de Symfony ?

8.1

Qu’est-ce qu’un bundle ?

extension Symfony regroupant des fonctionnalités spécifiques

Quel est le moteur de template utilisé par défaut dans Symfony ?

TWIG

Qu’est-ce qu’un ORM ? Quel est son utilité et comment s’appelle-t-il au sein de Symfony ?

ORM : Objet Relational Mapping - relie des objets à des tables d'une base de données
Sur Symfony : Doctrine

Qu’est-ce que l’injection de dépendances ? Quel est l’outil utilisé dans ce contexte et quel fichier contient l’intégralité des dépendances du projet ?

design pattern qui permet de déléguer la création et la gestion des dépendances à un conteneu. 
Fichier : Config/service.yaml

Que permet le bundle Maker au sein de Symfony ?

Permet de créer automatiquement des entités, des formulaires, des controleurs

Quel est le langage de requêtage exploité au sein d’un projet Symfony ?

DQL (Doctrine Query Langage)

Quel est le composant qui garantit l’authentification et l’autorisation des utilisateurs ?

 Symfony Security

Sécurité

Qu’est-ce que l’injection SQL ? Comment s’en prémunir ?

Attaque consistant à injecter du code SQL dans un formulaire
utiliser des requetes préparées (prepare) - Limiter les accès et les permissions - Sinon, utiliser un ORM

Qu’est-ce que la faille XSS ? Comment s’en prémunir ?

(Cross Site Scipting) Permet à un attaquant d’insérer du code malveillant (souvent JavaScript) dans une page web. 
Filtrer les données filter_var() OU htmlspecialchar() - Utiliser des framework incluant des protections XSS

Qu’est-ce que la faille CSRF ? Comment s’en prémunir ?

(Cross-Site Request Forgery) permet à un attaquant de forcer un utilisateur à effectuer involontairement une action non désirée sur une application web, comme soumettre un formulaire ou exécuter une commande, souvent sans que l'utilisateur ne s'en rende compte
Utiliser un token unique généré pour chaque requete et vérifier ce token sur les actions sensibles - Sur Symfony, activer la protection CSRF

Définir l’attaque par force brute et l’attaque par dictionnaire

Force Brute : essaie toutes les combinaisons possibles pour deviner un mot de passe
Dictionnaire : utilise une liste de mots connus (comme des noms, des mots courants, ou des expressions) pour deviner un mot de passe 

Existe-t-il d’autres failles de sécurité ? Citer celles-ci et expliquer simplement leur comportement

Man-in-the-Middle (MitM) : Hacker intercepte les communications entre un utilisateur et un serveur pour voler des données, les manipuler ou les modifier

A quoi servent l’authentification et l’autorisation dans un contexte d’application web ?

Authentification :
But : Elle permet de vérifier l’identité des utilisateurs en demandant des informations comme un nom d'utilisateur et un mot de passe
Objectif : S’assurer que l’utilisateur est bien qui il prétend être avant d’accéder à des ressources sécurisées

Autorisation :
But : l’autorisation contrôle les actions que l’utilisateur est autorisé à effectuer
Objectif : Assigner les droits d’accès (lecture, écriture, suppression, etc.) en fonction du rôle ou du statut de l’utilisateur

Définir la notion de hachage d’un mot de passe et citer des algorithmes de hachage

processus qui transforme un mot de passe en une chaîne de caractères difficile à inverser. Existe des algo de hashage faibles et forts

faibles : SHA256 et MD5 
Forts : Argon2i et Bcrypt

Qu’est-ce qu’une politique de mots de passe forts ?

critères que doivent respecter les utilisateurs pour créer des mots de passe sécurisés imposés par une REGEX

12 caractères minimum 
Une Maj + Un symbole + Un chiffre minimum

Qu’est-ce que l’hameçonnage ?

Phishing - hacker envoie des emails ou messages qui semblent légitimes, mais sont en réalité destinés à voler des informations personnelles telles que des mots de passe, des numéros de carte bancaire, ou des données sensibles

Définir la « validation des entrées »

consiste à contrôler et vérifier les données entrées par les utilisateurs pour s’assurer qu’elles respectent certaines règles avant de les traiter ou de les stocker dans une application

Objectifs de la validation des données : 
éviter les injections XSS et SQL
Assurer que les données saisies sont valides et attendue

RGPD

Qu’est-ce que le RGPD ?

règlement européen visant à protéger la vie privée et les données personnelles

Quel est son objectif principal ?

renforcer la protection des données personnelles et d’accorder aux individus plus de contrôle sur leurs informations

Quelle est la date d’entrée en vigueur du RGPD ?

25 mail 2018

Quelles sont les sanctions possibles en cas de non-respect du RGPD ?

20 millions d'€ ou 4% du CA annuel mondial

En France, quel est l’autorité administrative qui s’occupe de faire appliquer le RGPD ?

CNIL - Commission Nationale Informatique et Liberté

Quel est le consentement valide selon le RPGD ?

Être libre, spécifique, éclairé et univoque
Reposer sur une action affirmative claire de la part de l’utilisateur
Être donné sans contrainte et être révocable à tout moment

Qu’est-ce qu’une politique de confidentialité ?

explique comment une organisation collecte, utilise, protège et partage les données personnelles des utilisateurs
doit informer clairement les individus sur leurs droits et sur la manière dont leurs données sont traitées

Quelle est la durée de conservation maximale des données personnelles selon le RGPD ?

Il n’y a pas de limite fixe, mais les données doivent être supprimées une fois la finalité atteinte

Quels sont les droits des utilisateurs selon le RGPD ?

Droit d’accès : Accéder à leurs données personnelles.
Droit de rectification : Corriger les données incorrectes
Droit à l’effacement (droit à l’oubli) : Demander la suppression de leurs données
Droit à la portabilité : Transférer leurs données vers un autre service
Droit d’opposition : S’opposer au traitement de leurs données
Droit à la limitation : Demander que le traitement de leurs données soit limité

Qu’est-ce que le principe de minimisation des données selon le RGPD ?

stipule que seules les données personnelles strictement nécessaires pour la finalité poursuivie doivent être collectées et traitées

SEO

Qu’est-ce que le SEO ?

(Search Engine Optimization) désigne l’ensemble des techniques utilisées pour améliorer la visibilité d’un site web sur les moteurs de recherche,

Quel est l’objectif principal du SEO ?

favoriser un meilleur classement dans les résultats de recherche

Existe-t-il plusieurs types de référencement ? Lesquels ?

SEO (Search Engine Optimization) : Optimisation pour les moteurs de recherche
SEA (Search Engine Advertising) : Publicité payante sur les moteurs de recherche, comme Google Ads

Qu’est-ce que la densité de mots-clés en SEO ?

pourcentage d’un mot-clé ou d’une expression par rapport au nombre total de mots sur une page. Evalue si une page est optimisée pour un mot-clé spécifique

Qu’est-ce qu’une balise « alt » ?

fourni une description textuelle d’une image. Permet une meilleure accessibilité et un meilleur référencement

Qu’est-ce que la balise « meta description » ?

court texte destiné à décrire le contenu d’une page web

Qu’est-ce que le « nofollow » en SEO ?

attribut utilisé pour indiquer aux moteurs de recherche de ne pas suivre un lien

Quelle est l'importance du contenu de qualité pour le référencement d'un site web ?

Répond aux besoins des utilisateurs : Fournit des informations utiles et pertinentes
Augmente la durée de visite : Diminue le taux de rebond et améliore l’expérience utilisateur
Optimise le SEO : Favorise un meilleur classement en répondant aux critères de pertinence des moteurs de recherche

Pourquoi est-il important d'utiliser des balises de titre (h1, h2, h3, etc.) de manière structurée ?

Améliore la lisibilité du contenu : Organise et hiérarchise les informations
Renforce le SEO : Aide les moteurs de recherche à comprendre la structure de la page et le sujet principal

Quelle est la recommandation pour les URL d'un site web bien référencé ?

Clarté et simplicité : Utiliser des URL courtes et lisibles qui décrivent le contenu
Utiliser des mots-clés : Inclure des termes pertinents pour le SEO

Qu'est-ce que le maillage interne et pourquoi est-il important pour le référencement ?

Lie des pages de votre site entre elles pour guider les visiteurs et les moteurs de recherche
Améliore l’indexation : Aide les moteurs de recherche à découvrir et à indexer les pages
Réduit le taux de rebond : Amène les utilisateurs à naviguer plus profondément sur le site

Qu'est-ce que l'optimisation des images pour le référencement ?

Consiste à améliorer la visibilité et la performance des images sur un site web
Utilisation de balises "alt"
Réduire la taille des images pour améliorer la vitesse de chargement
Utiliser des formats appropriés comme JPEG, PNG, ou WebP pour le web

Qu'est-ce qu'un plan de site (sitemap) et pourquoi est-il important pour le référencement ?

Liste toutes les pages d’un site web
Améliore l’indexation 
Guide les robots
Assure la couverture complète

Gestion de projets - DevOps

Qu’est-ce que la gestion de projet ?

Consiste à planifier, organiser, et suivre les activités d’un projet pour atteindre ses objectifs, tout en respectant les contraintes de temps, coût, et ressources

Qu’est-ce qu’une méthode Agile de gestion de projet ?

Gestion de projet est une approche flexible et itérative
Divise le projet en sprints ou itérations pour améliorer l’efficacité et la qualité

Expliquer la méthode MoSCoW en quelques lignes et citer ses 

Outil de priorisation utilisé pour classer les tâches en fonction de leur importance

Must-Have (Obligatoire) : Ce qui est essentiel pour le succès du projet
Should-Have (Souhaitable) : Ce qui est important, mais pas critique
Could-Have (Peut-être) : Ce qui est utile, mais non indispensable
Won’t-Have (Non prévu) : Ce qui ne sera pas traité pour l’instant

A quoi sert la méthodologie MVP ? Citer les caractéristiques clés

(Minimum Viable Product) - sert à créer une version initiale d’un produit avec les fonctionnalités essentielles

Qu’est-ce que la planification itérative ?

Consiste à diviser le projet en phases ou itérations courtes, où chaque cycle permet de planifier, développer, tester, et livrer un sous-ensemble fonctionnel

Citer 3 méthodes Agiles dans le cadre d’un projet informatique

KANBAN, TRELLO, SCRUM

Qu’est-ce qu’une réunion de revue de projet ?

Rencontre où l’équipe évalue et examine les progrès réalisés sur le projet, les résultats atteints, et les objectifs restants

Qu’est-ce qu’un livrable dans un projet ?

Ce qui est produit ou créé à la fin d’un projet

Quels sont les 3 piliers SCRUM ? Définir chacun d’entre eux

Engagement (Commitment) :
Toutes les parties prenantes s’engagent à suivre et à respecter les objectifs du sprint, à collaborer et à livrer des résultats de qualité

Transparence :
Les informations clés sur le projet, le progrès, et les résultats sont facilement accessibles et compréhensibles pour toutes les parties concernées

Inspection :
Les progrès sont vérifiés fréquemment pour garantir que le travail suit le chemin prévu, et les ajustements sont faits en fonction des retours ou des évolutions

Qu’est-ce que le DevOps et quel est son objectif principal ?

Ensemble de pratiques visant à améliorer la collaboration et l'intégration entre les équipes de développement (Dev) et d'exploitation

Qu’est-ce que l’intégration continue ?

Patique DevOps qui consiste à intégrer et tester automatiquement le code des développeurs fréquemment

Qu’est-ce que Docker ? Et en quoi est-il utile dans le cadre du DevOps ?

Outil qui permet de regrouper une application et toutes ses dépendances dans un « conteneur » pour qu'elle fonctionne partout de la même manière

Qu’est-ce qu’un test unitaire ?

Méthode de test qui vérifie le bon fonctionnement d'un petit morceau de code, comme une fonction ou une classe, en isolation

Quelle est l'unité de code testée lors d'un test unitaire ?

?? Répondre ici ??

Quelles sont les caractéristiques d'un bon test unitaire ?

Isolation : le test ne doit pas dépendre d'autres parties du code
Fiabilité : il doit toujours donner le même résultat, peu importe l’environnement
Exactitude : le test doit vérifier un comportement spécifique
Facilité : il doit être rapide et ne pas interférer avec d’autres tests
Répétabilité : peut être exécuté plusieurs fois avec le même résultat

Qu'est-ce qu'une assertion dans un test unitaire ?  

Compare le résultat du test avec ce que l'on attend, et signale si le test échoue

English

1) What does JavaScript enable you to do on a website ? a. Add interactive behavior and dynamic content

2) Which programming language is primarily used for server-side web development ? a. PHP

3) What is the purpose of a web browser ? a. To render and display web pages

4) What is the difference between GET and POST methods in HTTP ? a. GET retrieves data from a server, while POST submits data to a server

5) What is the purpose of version control systems (e.g., Git) in web development ? a. To track changes and manage collaborative development 

6) What is the purpose of a framework in web development ? a. To provide a structured environment for building web applications

7) What does NoSQL stand for ? b. Non-Structured Query Language 

8) Which of the following is a characteristic of NoSQL databases ? c. Scalability and flexible data models
