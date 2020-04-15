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


### Vous êtes loggés! Remplissez le formulaire pour créer un nouvelle base de données

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


<img src="https://raw.githubusercontent.com/DataStax-Academy/cassandra-workshop-online/master/images/04.png" height="300" />


### View your Database and connect

View your database. It may take 2-3 minutes for your database to spin up. You will receive an email at that point. But, go ahead and continue with the rest of the exercise now.

<img src="https://raw.githubusercontent.com/DataStax-Academy/cassandra-workshop-online/master/images/05.png" height="300" />


Once Database is ready you should see the following home page :
<img src="https://raw.githubusercontent.com/DataStax-Academy/cassandra-workshop-online/master/images/06.png" height="100" />


Let’s review the database you have configured. In the box on the top-left side of the window, you can see the database and keyspace name metadata. The box on the top-right describes the size and location of your database. The lower-left box shows your estimated cost. Once Apollo initializes the database completely, the lower-right box will have connection details.

<img src="https://raw.githubusercontent.com/DataStax-Academy/cassandra-workshop-online/master/images/07.png" height="100" />


### Open DataStax Studio


You can click on `Launch Developer Studio` blue button to start the tool. Please enter the credentials you used for Astra instance creation.

<img src="https://raw.githubusercontent.com/DataStax-Academy/cassandra-workshop-online/master/images/08.png" height="300" />


- **Fill in the Database User name** - `KVUser`. Note the user name is case-sensitive. Please use the case we suggest here.

- **Fill in the password** - `KVPassword`. Fill in both the password and the confirmation fields. Note that the password is also case-sensitive. Please use the case we suggest here.

TADA !


