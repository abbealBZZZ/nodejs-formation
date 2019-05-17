# Node.JS Module 1

## Prérequis
______________________________________
- Connaissances basiques d'ES5+
______________________________________

## Jour 1 - matin

______________________________________
### Introduction, contenu du cours
_Durée, 30 minutes_

______________________________________
### Pourquoi Node JS, différences avec d'autres backends
_Durée, 15 minutes_

- Modèles bloquants vs non bloquants
- NodeJS vs PHP, Java
- NodeJS vs Apache, nginx
- NodeJS vs Serverless

______________________________________
### La boucle d'évènemenents
_Durée, 2h00_

Présentation de la boucle d'évènements
#### Cycle de vie de la boucle d'évènement
- timers
- pending callbacks
- idle, prepare
- poll
- check
- close callbacks
#### process.nextTick();
#### Timers
- `setTimeout()` / `clearTimeout()`
- `setImmediate()` / `clearImmediate()`
- `setInterval()` / `clearInterval()`
- `ref()` et `unRef()`

#### Le modèle de Node.JS, threads ou pas threads ? le worker pool.
Bloquer l'event loop
- expressions régulières
- encryption
- filesystem
- compression
- child processes
______________________________________

## Jour 1 - après-midi
______________________________________
### Rappel sur les callbacks, les promesses, et async/await
_Durée, 1h30_
#### Pourquoi la programmation asynchrone
#### Les callbacks
#### Le pattern Promise
- Le callback hell
- Inversion de contrôle
- Promise: resolve, reject
- .then(), .catch()
#### Async / await

______________________________________
### Modules
_Durée, 30 minutes_
- CommonJS standard : `require()`
- ES modules : `import` / `export`
  - activation des ES modules
  - différences avec CommonJS
  - Différentes syntaxes
  - imports JSON
- `import()` dynamique
______________________________________
### Les évènements
_Durée, 30 minutes_
______________________________________
### HTTP
_Durée, 1h30_
- Créer un serveur HTTP basique
- l'objet request
- l'objet response
- METHODS
- STATUS_CODES
- Créer un client HTTP
______________________________________
## Jour 2 - Matin
______________________________________
### Introduction à Express
_Durée, 3h_
- Avantages d'Express par rapport à HTTP
- Les routes
- Middlewares
  - BodyParser
  - Cors
- Créer ses propres middlewares
- Alternatives à Express : Koa, HAPI, Micro, Sails, ...
______________________________________
## Jour 2 - Après-midi
______________________________________
### npm et package.json
_Durée, 1h_
Présentation du système de packages
______________________________________
### La gestion des erreurs
_Durée, 30 minutes_
- `try` / `catch` / `throw`
- L'objet `Error`
- Construction d'un objet d'erreur
______________________________________
### Le système de fichiers
_Durée, 2h_
- Introduction aux systèmes de fichiers
- Le module fs
  - lire et écrire des fichiers
  - fs Promises API
______________________________________
### Process
_Durée, 1h_
Contrôle du processus en cours
- Evènements
- Signaux
- I/O
- Exit codes
- Brève introduction aux child processes

### OS
_Durée, 1h_
- Informations sur l'OS :
  - Plateforme
  - Hostname et réseau
  - Consommation CPU et mémoire
  - Répertoires: utilisateur, temporaire, ...
- Constantes Signaux
- Constantes POSIX
- Priorités

______________________________________
## Jour 3 - matin
______________________________________
### Ligne de commande de nodeJS
_Durée, 1h_

- -e : eval
- -r : require
- --experimental-*

### Debugger NodeJS
_Durée, 1h_
- Débugguer via la ligne de commande
- Debugger - intégration IDE

### Profiler NodeJS
_Durée, 1h_
- Présentation du profiler V8
- Profiler - ligne de commande
- Profiler des requetes HTTP avec Apache ab
______________________________________
## Jour 3 - après-midi
____________
### Tests
_Durée, 2h_
- Tests unitaires avec assert
- Présentation de mocha / jest / karma
______________________________________
### Un pas vers le TDD
_Durée, 1h_
______________________________________

### Conclusion, ouverture vers le module 2
_Durée, 30 minutes_