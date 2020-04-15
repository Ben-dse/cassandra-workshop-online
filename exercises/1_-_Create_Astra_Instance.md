# Exercice 1 - Créez votre instace Astra


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


- **Set the Compute Size**: For the work we are doing please use `Free tier`. You instance will be there forever, free of charge

- **Select the region**: This is the region where your database will reside physically (choose one close to you or your users). For people in EMEA please use `europe-west-1` idea here is to reduce latency.

- **Fill in the database name** - `killrvideocluster.` While Astra allows you to fill in these fields with values of your own choosing, please follow our reccomendations to make the rest of the exercises easier to follow. If you don't, you are on your own! :)

- **Fill in the keyspace name** - `killrvideo`. It's really important that you use the name killrvideo (with no 'e' in "killr") here in order for all the exercises to work well. We realize you want to be creative, but please just roll with this one today.

- **Fill in the Database User name** - `KVUser`. Note the user name is case-sensitive. Please use the case we suggest here.

- **Fill in the password** - `KVPassword`. Fill in both the password and the confirmation fields. Note that the password is also case-sensitive. Please use the case we suggest here.

- **Launch the database**. Review all the fields to make sure they are as shown, and click the Launch Database button.


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


