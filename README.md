👪 Famly - Application MERN de gestion de sorties en famille (En développement)
Famly est une application web en cours de développement, construite avec la stack MERN (MongoDB, Express, React, Node.js) et Redux. Cette application a pour objectif de permettre aux familles de créer et gérer des sorties en groupe. Ce projet est en phase de développement, certaines fonctionnalités sont en cours de finalisation.

🚀 Fonctionnalités
Fonctionnalités déjà implémentées :
Création d'une famille : Créez une famille et obtenez un identifiant unique.
Ajout de membres : Les membres peuvent s'inscrire et rejoindre une famille avec l'identifiant.
Création et édition des sorties : Les membres peuvent proposer et modifier des sorties.
Participation aux sorties : Les membres peuvent indiquer leur participation aux événements.
Fonctionnalités en cours de développement :
Gestion des membres : Le créateur de la famille pourra ajouter ou supprimer des membres.
Filtrage avancé des sorties : Filtrer les sorties en fonction de la participation, de la date, ou d’autres critères.
Notifications en temps réel : Notification lors de la création de nouvelles sorties.
📚 Technologies Utilisées
React : Pour la gestion des composants et l'interface utilisateur.
Redux : Pour la gestion de l'état global de l'application.
Node.js & Express.js : Pour le backend et les requêtes HTTP.
MongoDB & Mongoose : Pour la base de données.
TypeScript : Pour un typage strict et une meilleure gestion des erreurs.
ChakraUI & CSS3 : Pour la conception et les styles.
🛠️ Installation et Utilisation
Prérequis
Node.js et npm doivent être installés sur votre machine.
Un compte MongoDB et une clé URI pour connecter la base de données.
Étapes d'installation
Clonez le dépôt GitHub :

git clone https://github.com/Irnam1/famly-outings-manager
Installez les dépendances du projet :

npm install
Configuration de MongoDB :

Créez un fichier .env à la racine du projet.
Ajoutez-y votre clé URI MongoDB :
MONGODB_URI="votre_uri_mongodb"
Démarrez l’application :

npm start
Utilisation (en développement)
L'application est encore en phase de développement, certaines fonctionnalités peuvent ne pas être entièrement fonctionnelles.

Créer une famille : Créez une famille avec un nom unique.
Ajouter des membres : Les membres peuvent se joindre à la famille avec un identifiant unique.
Créer des sorties : Proposez des sorties familiales via l'interface de gestion.
🔮 Améliorations futures
Voici quelques fonctionnalités potentielles pour les prochaines versions :

Gestion complète des membres : Ajout et suppression des membres par l'administrateur.
Calendrier interactif : Voir toutes les sorties sur un calendrier pour une meilleure organisation.
Notifications par email et push : Alertes pour les nouvelles sorties et les changements de participation.
🐛 Problèmes connus
Suppression de membres : Cette fonctionnalité est en cours de développement et peut ne pas fonctionner comme prévu.
Notifications en temps réel : Cette fonctionnalité n'est pas encore disponible.
📄 Licence
Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus de détails.
