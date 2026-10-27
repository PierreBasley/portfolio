# Sources et limites éditoriales — version 10

## Sources réellement consultées

- **Messages de Pierre Basley** : profil, formation Zone01 depuis mai 2026, recherche d’alternance, projets et préférences de présentation. Les échanges précisent mai 2027, temps plein, deux ans d’alternance, les territoires de mobilité, les fonctionnalités et technologies des trois projets étudiants ainsi que les objectifs et l’état actuel du prototype Coach Go. Les précisions sur Groupie Tracker et ASCII-ART documentent leurs dates et statuts, contributions personnelles, difficultés et solutions, coauteurs, fonctionnalités et outils. Pierre a également fourni l’exemple textuel ASCII-ART « Un exemple ». Les dernières précisions décrivent Coach Go, ses outils, son fonctionnement, son exercice existant, ses tests unitaires et ses prochaines étapes, ainsi que les modifications des cartes et du statut des projets finalisés. Les dernières demandes détaillent Forum, ses fonctionnalités, contributions, coauteurs, difficultés, résultat, état déclaré et améliorations envisagées. Elles précisent aussi les cartes de stacks réduites au nom et au monogramme, les outils Postman et Discord, les libellés des langues et la nouvelle introduction sans bloc d’orientations séparé. La version 10 reprend deux demandes sur l’accueil : le monogramme « PB » et la première capture de Forum sur sa carte.
- **Archive jointe `forum.zip`** : trois captures originales extraites et consultées visuellement, intégrées dans `assets/projets/forum/`. Elles montrent l’accueil, un post avec sa zone de réponses et le formulaire de publication.
- **Nouveau CV joint `CV_Pierre_BASLEY_2026.pdf`** : texte de son unique page extrait et consulté. Ce fichier remplace le CV précédent, sans modification, dans `assets/cv/pierre-basley-cv.pdf`.
- **Archive jointe `image groupie tracker.zip`** : trois captures PNG originales extraites et consultées visuellement. Elles sont intégrées à la galerie de Groupie Tracker sans retouche ni recadrage.
- **Archive jointe `AsciiArt.zip`** : quatre captures PNG originales de 1 335 × 926 pixels extraites et consultées visuellement. Elles sont intégrées à la galerie ASCII-ART sans retouche ni recadrage.
- **Archive jointe `coach-golang.zip`** : trois captures PNG originales de 3 076 × 1 695 pixels fournies pour Coach Go, conservées sans retouche dans `assets/projets/coach-go/`.
- **Ancien CV `CV_2026-09-23_Pierre_BASLEY.pdf`** : utilisé pour la version précédente ; il n’est plus le document proposé au téléchargement dans cette version.
- **[Profil GitHub public](https://github.com/PierreBasley)** : consulté lors de la première version, le 25 octobre 2026 ; aucun dépôt public n’était alors affiché.
- **[Dépôt privé du portfolio](https://github.com/PierreBasley/portfolio)** : accès connecté disponible. Il contient désormais la livraison précédente de la maquette sur `main`. La version 10 est préparée pour ce même dépôt privé. Ce dépôt de conception ne constitue pas une consultation du code des projets étudiants.

## Informations renseignées

Les précisions de Pierre font foi pour les conditions d’alternance : disponibilité en **mai 2027**, rythme **temps plein**, durée **deux ans**. Pierre est localisé à Rouen, possède le permis B et un véhicule ; sa recherche s’étend à la Métropole de Rouen, aux agglomérations du Havre et de Caen ainsi qu’à la ville de Paris. Ces informations de localisation et de mobilité sont conservées ici comme données fournies ; elles ne sont plus affichées sur l’accueil, conformément à sa dernière demande. Les modalités télétravail/présentiel avaient également été retirées.

Le nouveau CV confirme l’e-mail, les postes, leurs dates, la formation Zone01, le master 2 et les niveaux déclarés en langues : anglais B2 et portugais A2. Il mentionne HTML, CSS, JavaScript, Go, Rust, C, C++, **C#**, PHP, SQL avec SQLite, MySQL et PostgreSQL, Git, Docker, Linux Ubuntu, le terminal et Visual Studio Code.

## Informations propres aux projets

Les éléments suivants sont **déclarés par Pierre dans son message** ; aucun dépôt de ces projets n’a été audité :

- **Forum** : projet étudiant collectif d’entraide entre développeurs de tous niveaux. Fonctionnalités déclarées : publier un post avec les stacks concernées, répondre, voter sur un post ou une réponse, rechercher et filtrer. Pierre déclare un rôle de chef de projet avec organisation des versions et des tâches, une participation au backend, aux pages web et au design, ainsi qu’aux sessions. Technologies déclarées : Go, HTML, CSS, SQLite, Git et Docker. Coauteurs : Abdou CHERIF HONO DIGO, Yohann FEDAOUI et Hicham HEE. Les trois difficultés et solutions décrites concernent le choix de SQLite, un gestionnaire de sessions serveur utilisant des fichiers JSON et le hachage bcrypt. Le résultat déclaré est la possibilité de communiquer entre membres. Modération, OAuth2 et profil restent des améliorations envisagées. L’état « Finalisé à 90 % » est l’estimation fournie par Pierre, sans mesure indépendante, audit ou taux de couverture calculé. La date reste inconnue.
- **Groupie Tracker** : projet étudiant collectif déclaré finalisé en août 2026. Il affiche les informations d’artistes et de groupes obtenues via une API REST, les concerts, dates et lieux avec Google Maps, une barre de recherche, des filtres et le rafraîchissement des données de l’API. Technologies et outils déclarés : Go, HTML, CSS, Git et Postman. Pierre a fourni quatre points de contribution personnelle ainsi que deux difficultés et leurs solutions ; ils sont repris dans la fiche. La précision « dans des variables internes au serveur » complète l’explication du stockage des données. Les autres auteurs nommés sont Léo Giffard et Alexis Fourny. Ces informations décrivent le travail déclaré par Pierre ; elles ne constituent ni un audit du code ni une mesure de performance.
- **ASCII-ART** : site étudiant collectif déclaré finalisé en juillet 2026. Il transforme un texte en ASCII-ART avec trois modèles, standard, shadow et thinkertoy, et propose des exports TXT, Markdown et HTML. Technologies déclarées : Go, HTML, CSS et Git. Pierre décrit trois contributions : serveur et routes, conversion du texte, sécurisation du traitement des requêtes HTTP. Les mécanismes de sécurisation ne sont pas précisés ; aucune authentification ni configuration HTTPS n’est déduite de cette déclaration. La difficulté de conversion des caractères est associée à une solution utilisant des fichiers texte lus par le serveur. Les coauteurs nommés sont Maxime Fedaoui et Amélie Lematelot. L’exemple textuel « Un exemple » fourni par Pierre est repris avec ses espacements dans un bloc monospace accessible au clavier.
- **Coach Go** : prototype personnel développé seul, présenté à part. Son objectif est l’apprentissage de l’algorithmique et de la programmation modulaire, avec une méthode permettant d’avancer à son rythme. L’existant déclaré fonctionne localement, hors ligne, sous Linux Debian. Wails fournit l’interface graphique ; CodeMirror sert d’éditeur et ses dépendances sont installées. Le prototype propose le premier palier seulement, avec un exercice nommé « Ajuster » et des tests unitaires. Technologies déclarées : Go, HTML, CSS, Node.js, Wails et JavaScript. La date du prototype reste inconnue. Les trois prochaines étapes sont de définir les notions et la difficulté du palier 1, d’y ajouter des exercices et de réviser la charte graphique vers l’univers Go. Elles restent séparées des fonctionnalités actuelles.

Git est renseigné pour Forum, Groupie Tracker et ASCII-ART à partir des déclarations de Pierre. Docker est désormais déclaré pour Forum, sans être attribué aux autres projets. Les contributions, difficultés et captures de ces trois réalisations sont renseignées. Coach Go conserve les précisions sur son fonctionnement et ses trois captures. Les liens encore inconnus et la date de Forum restent à compléter. La date de Coach Go reste inconnue, mais son champ à compléter est retiré de la fiche affichée ; aucune date n’est inventée. Aucun support d’autres systèmes ni usage de l’IA n’est attribué à Coach Go.

## Galerie de Forum

Les trois captures originales de `forum.zip` sont conservées dans `assets/projets/forum/` :

- `accueil.png` : accueil sans publications affichées.
- `post-reponses.png` : post de démonstration, vote et zone de réponses vide.
- `publier-question.png` : formulaire de publication, description et sélection des technologies.

Les captures sont accompagnées de légendes, textes alternatifs et liens grand format annonçant un nouvel onglet. Les exports sont `forum-ordinateur.png`, `forum-mobile.png` et `forum-galerie.png` ; deux vues Forum sont ajoutées au PDF, qui comprend douze pages. Les contenus de démonstration visibles n’établissent aucune activité réelle de communauté. Les captures ne constituent pas un audit du fonctionnement du projet.

La carte Forum sur l’accueil utilise désormais `assets/projets/forum/accueil.png`, première capture fournie dans `forum.zip`, à la place de l’illustration de conception. La fiche Forum et les autres pages conservent leur contenu ; l’origine des captures reste identique.

## Galerie de Groupie Tracker

Les trois originaux reçus dans `image groupie tracker.zip` sont conservés dans `assets/projets/groupie-tracker/` :

- `catalogue-accueil.png` : vue principale du catalogue.
- `fiche-genesis.png` : vue complémentaire de la fiche Genesis.
- `catalogue-suite.png` : vue complémentaire de la suite du catalogue.

Ils sont affichés sans retouche ni recadrage, avec des légendes, des textes alternatifs et des liens vers leur taille originale. L’ouverture de ces liens dans un nouvel onglet est annoncée. Les exports `projet-ordinateur.png`, `projet-mobile.png` et le PDF montrent la fiche de portfolio avec cette galerie.

La consultation de ces captures permet de documenter l’interface montrée. Elle ne constitue pas un audit du code des projets étudiants et n’ajoute aucune mesure de performance aux résultats déclarés par Pierre.

## Galerie et exemple d’ASCII-ART

Les quatre originaux reçus dans `AsciiArt.zip` sont conservés dans `assets/projets/ascii-art/` :

- `rendu-salut.png` : première vue de la galerie actuelle, montrant le rendu « salut ».
- `accueil.png` : vue complémentaire de l’accueil.
- `rendu-hello-world.png` : vue complémentaire du rendu « hello world ».
- `rendu-caracteres.png` : vue complémentaire du rendu de caractères.

Ces PNG de 1 335 × 926 pixels sont affichés sans retouche ni recadrage, avec légendes, textes alternatifs et liens vers les originaux annonçant un nouvel onglet. Les captures affichent le modèle standard sélectionné ; les noms et la disponibilité des trois modèles viennent de la déclaration de Pierre, sans déduire les modèles des rendus montrés. Les exports dédiés sont `ascii-ordinateur.png`, `ascii-mobile.png` et `ascii-galerie.png` ; le PDF comprend également la fiche ASCII-ART.

L’exemple textuel « Un exemple » vient du message de Pierre. Ses espacements sont préservés dans un bloc de code monospace ; sur mobile, ce bloc peut défiler horizontalement au clavier. Les captures et cet exemple documentent les éléments fournis, sans audit du code ni mesure de performance.

## Captures de Coach Go et cartes de l’accueil

Les trois originaux de `coach-golang.zip` sont conservés dans `assets/projets/coach-go/` :

- `accueil.png` : première image de la galerie.
- `palier-1.png` : deuxième image de la galerie.
- `exercice-ajuster.png` : illustration de la section Résultat.

Ces PNG de 3 076 × 1 695 pixels sont accompagnés de légendes, textes alternatifs et liens grand format annonçant un nouvel onglet. Les exports dédiés sont `coach-ordinateur.png`, `coach-mobile.png` et `coach-galerie.png` ; le PDF comprend aussi cette fiche. Les textes et nombres visibles dans les captures sont conservés tels que fournis. Leur présence ne valide pas les « 18 variantes » ou « 201 tests » affichés : aucun code ni résultat de test du programme Coach Go n’a été audité ou exécuté dans le cadre de cette maquette.

Sur l’accueil du portfolio, les premières captures actuelles de Groupie Tracker (`catalogue-accueil.png`) et d’ASCII-ART (`rendu-salut.png`) remplacent les illustrations précédentes. L’encart Coach Go affiche désormais sa première capture, `assets/projets/coach-go/accueil.png`. Les trois cartes étudiantes utilisent chacune un seul lien HTML couvrant la carte entière. Cette navigation ne nécessite pas JavaScript.

Le portfolio livré reste une maquette statique HTML/CSS. Wails, Node.js, CodeMirror et JavaScript concernent le programme Coach Go décrit ; ils ne sont pas des dépendances nécessaires pour lire la maquette.

## Présentation de Parcours et Contact

La section Parcours est conservée. Les cartes de stacks affichent seulement le nom et le monogramme, sans liens vers les projets ni mention « Dans mon CV ». Les provenances restent dans les données éditoriales et ce document : usages déclarés dans les projets, compétences déclarées dans le CV. Le regroupement visuel ne transforme pas une déclaration du CV en preuve issue d’un projet ni en compétence auditée. Les outils restent affichés, avec Postman et Discord ajoutés à la demande de Pierre. Postman était déjà déclaré pour Groupie Tracker ; Discord est une nouvelle déclaration générale, sans attribution automatique à un projet.

Le bloc Langues reprend **anglais B2 — intermédiaire avancé** et **portugais A2 — initié**. Les niveaux B2/A2 proviennent du CV ; les libellés explicatifs viennent de la demande de Pierre. La mention de provenance est retirée de l’interface, sans validation indépendante des niveaux.

Le bloc d’orientations est supprimé. L’introduction reprend exactement : « Je m’appelle Pierre Basley. En formation à Zone01 Rouen, je construis mon parcours en développement full stack, tout en me renforçant dans le domaine DevOps et IA. » Cette formulation décrit une progression en formation, sans expertise confirmée. Les éléments détaillés du parcours restent dans le CV et les sources, sans chronologie narrative sur l’accueil.

La localisation et la mobilité ont été retirées de l’accueil. L’adresse e-mail n’est plus répétée à côté du bouton Contact, mais son lien `mailto:` reste actif. La suppression de la mention « maquette » dans les pieds de page ne change pas la nature de cette livraison : un prototype statique HTML/CSS documenté dans le README et la notice.

## Choix de rédaction

Le nouveau CV mentionne encore « 7 ans » dans la fonction publique, alors que les expériences listées couvrent 2017 à mai 2026. Le récit « Une nouvelle voie… » et la chronologie ont été retirés de l’accueil. Les postes et leurs dates restent dans le CV original, sans correction du PDF ni durée totale recalculée.

La formulation « accessibilité ARIAL » n’est pas reprise comme preuve de compétence. Les spécialités proposées par Zone01 ne sont pas assimilées à des compétences acquises. DevOps et ingénierie IA restent les orientations exprimées par Pierre, sans affirmation d’expertise.
