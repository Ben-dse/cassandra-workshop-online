# Exercice 1 - Créez votre instance Astra


Accédez au service `ASTRA` en cliquant sur [https://astra.datastax.com](https://astra.datastax.com/)

### Register et Login

Utilisez vos identifiants pour vous logger à Astra. Remplissez les champs, et cliquez sur le bouton Log In.
Vous pouvez également vous identifier via votre compte Google ou Github.
Enfin, si vous n'avez aucun de ces comptes disponible, cliquez sur le lien `register`.

Voici le formulaire de login:

<img src="https://github.com/Ben-dse/cassandra-workshop-online/blob/master/images/astra_login.JPG" height="300" />

Si besoin donc, créez un compte via le formulaire si dessous  en cliquant sur le bouton `register`:

<img src="https://github.com/Ben-dse/cassandra-workshop-online/blob/master/images/astra_register.JPG" height="300" />


### Vous êtes loggés! Remplissez le formulaire pour créer une nouvelle base de données

Vous n'avez (à priori) pas créé d'instance précédement, vous êtes donc dirigés directement vers le formulaire de création d'instance.
Remplissez les champs tel que ci dessous:

<img src="https://github.com/Ben-dse/cassandra-workshop-online/blob/master/images/astra_newdb.JPG" height="400" />


- **Compute Size**: Pour nos exercices, utilisez `Free tier`. Votre instance sera gratuite, et disponible sans limitation de durée.

- **Sélectionnez la région**: Il s'agit de la région ou votre base de donnée sera physiquement présente, il faut donc sélectioner celle la plus proche de l'utilisateur (vous pour cet atelier). Vous êtes à priori en France, choisissez donc `europe-west-1` dans le but de minimiser les latences.

- **Remplissez le nom de la base de données** - `plasmacluster.` Vous pouvez effectivement choisir le nom que vous voulez, mais pour des raisons pratiques, nous vous invitons à suivre nos recommendation pour ne pas être perdus dans la suite des exercices.

- **Remplissez le nom du keyspace** - `plasma`. Encore une fois, afin que les exercices fonctionnent correctement, merci de suivre cette demande. Nous savons que vous voulez être créatifs, mais pensez à vos collègues qui devront vous attendre si l'atelier et bloqué pour ce petit écart.

- **Remplissez le nom d'utilisateur de la BDD** - `PlasmaUser`. Attention aux majuscules!

- **Remplissez le mot de passe** - `PlasmaPass`. Remplissez les deux champs mot de passe et confirmation. A nouveau attention aux majuscules.

- **Lancez la base de données**. Une dernière revue, 3, 2, 1, décollage!


<img src="https://github.com/Ben-dse/cassandra-workshop-online/blob/master/images/04.png" height="300" />


### Visualiser votre base de données et vous y connecter

Quelques minutes sont probablement nécessaire pour que votre cluster de 3 noeuds soit disponible. Vous recevrez un email de confirmation quand votre base de donnée est prête. Continuons.


<img src="https://github.com/Ben-dse/cassandra-workshop-online/blob/master/images/astra_init.png" height="300" />


Lorsque votre cluster est prêt, vous devriez voir la page suivante :
<img src="https://github.com/Ben-dse/cassandra-workshop-online/blob/master/images/astra_list.png" height="100" />


Jetons un oeil à la base de données que vous avez configuré. Dans le block supérieur gauche, vous voyez la base de données et le nom du keyspace. La partie supérieure droite décrit la taille et l'emplacement de votre BDD. Le block inférieur gauche indique ce que cela vous coûte (rien). Enfin, une fois qu'Astra a fini l'initialisation, vous aurez les détails de connection dans la partie inférieure-droite.

<img src="https://github.com/Ben-dse/cassandra-workshop-online/blob/master/images/astra_ready.png" height="300" />


### Ouvrez DataStax Studio


Vous pouvez cliquer sur le bouton bleu `Launch Developer Studio` pour commencer à utiliser l'outil. Utilisez les mêmes identifiants que vous avez utilisé pour créer l'instance Astra.

<img src="https://github.com/Ben-dse/cassandra-workshop-online/blob/master/images/08.png" height="300" />


- **Remplissez le nom d'utilisateur de la BDD** - `PlasmaUser`. Attention aux majuscules!

- **Fill in the password** - `PlasmaPass`. Attention aux majuscules!

TADAA !


