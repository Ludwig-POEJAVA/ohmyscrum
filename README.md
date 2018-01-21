# ohmyscrum
Manage your scrum things with awesomeness

## Intro
Déjà bravo pour votre initiative, le sujet est bien trouvé et peut répondre à un véritable besoin.
Il existe des solutions, notemment du coté de chez atlassian, mais elles sont intégrées à une suite logicielle certe complète, mais un peu lourde.
Votre projet peut être à l'outillage Scrum ce que Trello est à la gestion de projet : on se concentre sur un petit lot de fonctionnalités qu'on rend hyper accessibles. IMHO.

## V.Solo vs V.Team
### Javascript / Java
La version solo à elle seule peut prendre pas mal de temps.
Et elle se concentre sur des features front. Donc attention. Vous allez faire beaucoup de Java à partir de maintenant. Je pense que le coté drag'n'drop trop cool peut être fait dans un coin par un enervé et partagé avec le reste de l'équipe ensuite histoire de ne pas passer trop de temps sur cette feature. 

### Dévelopement des tâches en horizontal
Ce que je veux dire par là est qu'il serait dommage de faire des rush Javascipt, puis des rushs Java, puis des rush BDD.
Essayer de penser les US en terme de fonctionnalités complète. Une US complète doit faire intervenir toutes les couches techniques de votre application, c'est ce que j'appel le dev horizontal, on traverse l'ensemble de l'architecture à chaque feature.
N'oubliez pas qu'en Scrum on doit créer de la valeur ajoutée pour le client. Une feature JS jolie-qui-clignote vaut zéro point technique si elle ne permet pas à l'utilisateur de réaliser une tâche complète.

### Le business coté server
Si vous prêter attention à garder votre business (code métier) coté serveur, et non pas dans angular, vous aurez pas mal d'appel REST à réaliser, ce qui est bien.
Vous aurez ainsi du code front et back pour chaque feature.

Exemple : En tant qu'utilisateur, je déplace une tâche de en-cours vers terminée.
 * drag'n'drop JS
 * appel REST au service /task/move?state=DONE   (--> ceci est un exemple)
 * récupération de la réponse HTTP coté client

Bref, attention à ne pas répartir les tâches en fonction des techno, mais bien en fonction des besoins métiers.

### Organisation du travail
Vous pensez vous organiser comment ? Chacun fait son projet ou vous vous répartissez les tâches ?
La répartition peut être très intéressante, mais plus compliquée à mettre en place. Tout le monde doit apprendre toutes les techno, pas de héro, donc la répartition équitable des tâches par une équipe auto gérée de 10 personnes va être compliquée. à vous de voir.
Si vous choisissez cette voie, je pense que faire 2 équipes peut être un peu plus simple. Voir 3. Et il faut un regard exterieur afin d'éviter que ce soit toujours les même qui prennent leurs tâches préférés :)
Vous pouvez nommer un scrum master dans l'équipe d'à coté qui check le taf de l'autre équipe par exemple...

Si vous bosser en solo, moins de problème, mais vous en ferez moins. A vous de motiver les formateurs afin qu'ils adaptent légèrement leurs TP. 

### US et Formateur
Si vous arrivez à prévoir quelles genres d'US pourraient convenir pour chacun des modules à venir, vous faciliterez le travail des formateurs. L'idéal, et je pense d'ailleurs que c'est essentiel, serait d'envoyer votre backlog à tous les formateurs à venir, en leur disant que c'est ce projet qui est mis en place et sur lequel ils devront vous faire travailler. Parce que c'est votre projeeeeeeeeeeeet! bref.

### Ceci est une formation
Ne perdez pas de vue que vous suivez une formation, et surtout que vous suivez tous la même formation. Vous devez apprendre ensemble. Vous aurez tout le temps de coder comme des petits fou dans les années à venir, alors prenez le temps de bien tout assimiler ;)












