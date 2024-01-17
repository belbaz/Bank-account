 Documentation du projet    /\*couleur qui change\*/ setInterval(function () { document.getElementById('colorChange').style.color = '#' + Math.random().toString(16).substr(-6); }, 750); [![Icône](../icones/accueil.png)](../ "Accueil")

Projet de Simulation de prêt PHP
================================

Ceci est la documentation de notre projet PHP
---------------------------------------------

Le sujet est disponible [ici](Projet%20PHP%202021.pdf)
------------------------------------------------------

### Nous vous recommandons de visiter ce site en utilisant Google Chrome

Manuel Utilisateur
------------------

#### Simulation

Pour faire la simulation d'un prêt, il faut cliquer sur le bouton **simulation** de la [page d'accueil](../) puis de rentrer le **Capital**, le nombre de **Mois** ainsi que le **Taux** puis cliquer sur **Calculer**.

#### Historique

Les 10 dernières entrées de l'historique sont disponibles via un bouton en dessous de l'encadré (il n'apparait que si l'historique contient des données).

Il est possible de charger les valeurs d'une entrée de l'historique dans le formulaire en cliquant sur la valeur encadrée de la colonne **Montant**.

Manuel Administrateur
---------------------

#### Connexion

Pour se connecter en tant qu'administrateur, il faut cliquer sur le bouton **connexion** de la [page d'accueil](../index.html).

#### Historique

Le fichier d'historique principal est `logs.csv`. Mais la liste déroulante de droite permet de choisir le fichier à afficher parmi les archives.  
L'historique entier est affiché avec l'adresse IP ainsi que la date et l'heure de l'envoi du formulaire.

#### Vidage/Archivage/Téléchargement

Le fichier par défaut `logs.csv` ne peut pas être supprimé, mais il peut être vidé ou archivé.  
Le vider efface tout son contenu tandis que l'archiver le renomme afin d'en garder une sauvegarde.  
Les fichiers d'archive peuvent être supprimés ou téléchargés.

![Schéma de l'architecture de l'application](architecture.png)

© 2021 Bilel Medimegh, Eliott Rogeaux, Benjamin Elbaz, Stéphane Lay, Raphaël Gruet
----------------------------------------------------------------------------------
