# Features

- Open source, [AGPL License](/LICENSE).
- Auto-hébergeable, facil à déployer.
  - Fourni avec [Docker](#docker) et [Ansible](#ansible).
- Interface propre et conviviale pour les téléphones portables.
  - Il suffit d'un nom d'utilisateur et d'un mot de passe pour s'inscrire !
  - Prise en charge des avatars des utilisateurs.
  - Mise à jour en temps réel des fils de commentaires.
  - Scores de vote `(+/-)` comme l'ancien reddit.
  - Thèmes, y compris clair, sombre, et solarisé.
  - Emojis avec support de l'autocomplétion. Commencez en tapant `:`
  - Metion des utilisateurs avec `@`, mention de la communauté avec `!`.
  - Téléchargement d'images intégré dans les messages et les commentaires.
  - Un message peut être composé d'un titre et de toute combinaison de texte, d'une URL ou de rien d'autre.
  - Notifications, sur les réponses aux commentaires et lorsque vous êtes metionné.
    - Les notifications peuvent être envoyé par courriel
  - i18n / Prise en charge d l'internationalisation.
  - RSS / Flux Atom pour "Tous", "Abonnés", "Boîte de réception", "Utilisateur" et "Communauté".
- Prise en charge du publipostage croisé.
  - Une *recherche de messages similaires* lors de la création de nouveaux messages. Idéal pour les communautés de questions/réponses.
- Capacités de modération.
  - Logs de modération publics.
  - Peut épingler des messages en haut des communautés.
  - Administrateurs du site et les modérateurs de communauté, qui peuvent nommer d'autres modérateurs.
  - Peut verrouiller, supprimer et restaurer les messages et les commentaires.
  - Peut bannir et débannir des utilisateurs des communautés et du site.
  - Peut transférer le site et les communautés à d'autres.
- Peut effacer complètement vos données, en remplaçant tous les messages et commentaires.
- Prise en charge pour les messages NSFW et les communautés.
- Haute performance.
  - Le serveur est écrit en rust.
  - L'interface est `~80kB` gzippée.
  - Front-end fonctionne sans javascript (lecture seule).
  - Prise en charge d' arm64 / Raspberry Pi.