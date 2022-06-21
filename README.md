# Création d'une application FullStack avec React CRUD et API/ASP.NET

Ceci est le depôt d'une application FullStack représentant un menu de pizzeria simple et basique.
Cette application a été réalisé par Thomas Le Blan, étudiant en BTS SIO au lycée Saint Gabriel et en stage au RIF (Rassemblement des ingénieur francophones)

Les outils utiliser pour créer cette application sont les suivant:

## Outils
#### Node.js v16.15.1
#### .net v6.0
#### Cmder v1.3.19
#### Reactjs 18.1.0


## Etape de création de l'application
### 1) Création de l'interface React avec Create React App (React/JS)
Nous avons créer notre front-end avec React CRUD et tester notre interface avec un fichier de donnée static
### 2) Back-End temporaire et test de l'app (MockServer)
Pendant que l'équipe chargé du back-end finis sont travail nous avons utiliser un Mock-Server local pour tester notre liaison front-end/back-end.
### 3) Implémentation du Back-End final et configuration du CORS (.net/C#)
L'équipe Back-End a livré sont travail, nous avons donc plus qu'a configurer CORS et a lancer les 2 partie.

# Lancement de l'application:
### 1) Lancer le serveur:
```sh
dotnet run
```
### 2) Lancer l'interface:
```sh
npm start
```

## Scripts disponibles

Dans le répertoire du projet, vous pouvez exécuter :
```sh
npm start
```

Exécute l'application en mode développement.
Ouvrez [http://localhost:3000](http://localhost:3000) pour la visualiser dans votre navigateur.

La page se recharge lorsque vous apportez des modifications.
Vous pouvez également voir les éventuelles erreurs de lint dans la console.
```sh
npm test
```

Lance le programme d'exécution des tests en mode de surveillance interactive.
Voir la section sur [l'exécution des tests] (https://facebook.github.io/create-react-app/docs/running-tests) pour plus d'informations.
```sh
npm run build
```

Construit l'application pour la production dans le dossier `build`.
Il regroupe correctement React en mode production et optimise la compilation pour obtenir les meilleures performances.

La compilation est réduite et les noms de fichiers incluent les hachages.
Votre application est prête à être déployée !

Consultez la section sur le [déploiement] (https://facebook.github.io/create-react-app/docs/deployment) pour plus d'informations.

```sh
npm run eject
```

**Note : c'est une opération à sens unique. Une fois que vous vous êtes éjecté, vous ne pouvez plus revenir en arrière !**.

Si vous n'êtes pas satisfait de l'outil de compilation et des choix de configuration, vous pouvez vous `ejecter` à tout moment. Cette commande enlèvera la dépendance de construction unique de votre projet.

Au lieu de cela, elle copiera tous les fichiers de configuration et les dépendances transitives (webpack, Babel, ESLint, etc) directement dans votre projet afin que vous ayez un contrôle total sur eux. Toutes les commandes sauf `eject` fonctionneront toujours, mais elles pointeront vers les scripts copiés afin que vous puissiez les modifier. A ce stade, vous vous débrouillez tout seul.

Vous n'aurez jamais à utiliser `eject`. L'ensemble des fonctionnalités conservées est adapté aux petits et moyens déploiements, et vous ne devriez pas vous sentir obligé d'utiliser cette fonctionnalité. Cependant, nous comprenons que cet outil ne serait pas utile si vous ne pouviez pas le personnaliser lorsque vous êtes prêt à le faire.

## En savoir plus

Vous pouvez en savoir plus dans la [documentation sur la création d'une application React] (https://facebook.github.io/create-react-app/docs/getting-started).

Pour apprendre React, consultez la [documentation React](https://reactjs.org/).

### Fractionnement du code

Cette section a été déplacée ici : [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyse de la taille des paquets

Cette section a été déplacée ici : [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Créer une application Web progressive

Cette section a été déplacée ici : [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Configuration avancée

Cette section a été déplacée ici : [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Déploiement

Cette section a été déplacée ici : [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` ne parvient pas à minifier les fichiers

Cette section a été déplacée ici : [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
