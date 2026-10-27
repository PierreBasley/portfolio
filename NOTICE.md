# Maquette du portfolio de Pierre Basley — version 10

## Direction et hiérarchie

La palette conserve bleu nuit `#141827`, surfaces `#202539`, violet désaturé `#C4B9DB` et pêche `#F0C3A5`. Open Sans est locale ; le décor reste discret.

L’accueil garde **01 Projets, 02 Parcours, 03 Contact**. Son introduction indique : « Je m’appelle Pierre Basley. En formation à Zone01 Rouen, je construis mon parcours en développement full stack, tout en me renforçant dans le domaine DevOps et IA. » Le bloc d’orientations distinct est retiré.

Sur l’accueil, le monogramme « PB » figure en haut à gauche. Forum utilise `assets/projets/forum/accueil.png`. Les cartes étudiantes restent entièrement cliquables, avec un lien HTML unique.

## Parcours et contact

Les cartes de stacks présentent seulement nom et monogramme, sans lien vers les projets ni mention « Dans mon CV ». La distinction entre usages déclarés dans les projets et compétences du CV reste documentée dans les données et les sources. Les outils incluent Postman et Discord.

Le bloc Langues indique **anglais B2 — intermédiaire avancé** et **portugais A2 — initié**. La mention de provenance n’est plus affichée. Le récit et la chronologie restent retirés.

Alternance : **mai 2027, temps plein, deux ans**. Localisation et mobilité ne sont pas affichées sur l’accueil. Le bouton e-mail reste actif sans adresse répétée ; GitHub conserve son logo. Le CV original reste téléchargeable. Les pieds de page restent simplifiés.

## Projets

**Forum** présente publication avec stacks, réponses, votes sur posts et réponses, recherche et filtres. Pierre déclare avoir organisé versions et tâches comme chef de projet, participé au backend, aux pages et au design web, ainsi qu’aux sessions. Technologies : Go, HTML, CSS, SQLite, Git, Docker. Coauteurs : Abdou CHERIF HONO DIGO, Yohann FEDAOUI et Hicham HEE.

Les trois difficultés documentées concernent SQLite, les sessions serveur avec fichiers JSON et le hachage bcrypt. Le résultat déclaré est la communication entre membres. Modération, OAuth2 et profil restent des améliorations futures. **« Finalisé à 90 % » est une estimation de Pierre**, sans audit ni mesure indépendante ; la date reste inconnue.

Groupie Tracker et ASCII-ART conservent leurs fiches détaillées et « Projet finalisé ». Coach Go reste un prototype personnel : un palier, l’exercice « Ajuster » et des tests unitaires déclarés. Ses prochaines étapes restent séparées de l’existant. Aucun code de ces projets n’a été consulté ou audité.

## Fichiers et réalisation

Les originaux restent dans `assets/projets/` : trois images Forum, trois Groupie Tracker, quatre ASCII-ART et trois Coach Go. Forum utilise `forum/accueil.png`, `post-reponses.png` et `publier-question.png`. Les captures gardent légendes, textes alternatifs et liens grand format annonçant un nouvel onglet.

Le PDF `maquette-pierre-basley.pdf` comprend douze pages. Forum ajoute `forum-ordinateur.png`, `forum-mobile.png` et `forum-galerie.png` ; les autres exports restent accessibles depuis le README. Télécharger et extraire le dossier complet, puis ouvrir `index.html` ou `projet-*.html` ; GitHub affiche leur code.

Le CV reste dans `assets/cv/pierre-basley-cv.pdf` ; son téléchargement et `mailto:pierrebasley14@gmail.com` sont actifs. `profil.json` organise le profil ; `projets.json` décrit contexte, fonctionnalités, technologies, contributions, auteurs, difficultés/solutions, résultats, médias, améliorations et liens. Ces données ne sont pas chargées automatiquement : choisir une source unique au développement. Garder les champs `[À COMPLÉTER : information attendue]` nécessaires.

Le **HTML** structure contenu et navigation ; le **CSS** règle présentation et adaptation aux écrans. Le **JavaScript** pourrait enrichir des interactions facultatives, mais cette livraison n’en utilise pas.

Préserver contrastes, focus visible, lien d’évitement, titres, cibles tactiles et textes alternatifs. L’exemple ASCII-ART conserve ses espaces et son défilement au clavier. Respecter `prefers-reduced-motion` ; aucune musique automatique. Le dépôt reste privé.

Contrôles historiques v9 : cinq pages sur quatre largeurs, sans débordement horizontal ; liens et navigation clavier contrôlés.

Contrôles v10 : accueil vérifié à quatre largeurs ; capture Forum et lien de carte validés.
