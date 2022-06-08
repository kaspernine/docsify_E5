## initialisation des modules

Pour pouvoir lancer le serveur Angular, il est necessaire d'installer les dépendances de NodeJS. Npm est le gestionnaire de dépendances/paquets par défaut de NodeJS, NodeJS correspondant quand à lui à l'environnement d'execution.
Les dépendances du projet sont habituellement stockés dans un dossier nommé "node_modules", cependant si les dépendances ne sont pas installer dans le dossier "ClientApp" le CLI retournera une erreur à l'execution de la commande comme ci-dessous.
![npm install error](//ressources/pictures/npm_install_error.JPG "erreur d'installation des modules")

Pour pouvoir télécharger les dépendances nécessaires au fonctionnement de l'application, il est également nécessaire d'avoir un fichier package.json qui référence tous les modules à installer (ou qui sont déjà installés) ainsi que leur versions.
![fichier package.json](//ressources/pictures/npm_intsall_package.JPG "fichier package.jon")

Pour installer toutes les dépendances (les packages/modules) il suffit de lancer la commande "npm install" ou "npm i". Si les 2 points précédents sont bien respectés, tous les modules devraient s'installer sans erreur comme ci-dessous.
![npm install](//ressources/pictures/npm_install.JPG "npm install")