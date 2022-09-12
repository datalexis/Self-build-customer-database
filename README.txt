## ENG

My first dive into the world of databases! When I arrived, the company's contracts and customers were managed with unreadable Excel sheets. Within the framework of the quality approach, it was necessary to consolidate all that. The point was to create a system that would limit double data entry for users, data inconsistency and data redundancy, and following a workflow in compliance with quality standards and existing procedures.

This small database has a multitude of features :
- customer base management
- project sheet with id generator
- estimation of bid price
- editing bids, bills
- employee timesheets
- project costs management

Obviously, on the technical level, this database is my prototype so some choices would have been different today (like using Access as a Front-end to a SGBD like MySQL)

It was then completed by modules (which don't work here because a full rewrite of the scripts is required) :
- sending email alerts when some thresholds are exceeded (negative profitability, no time entered for several weeks by an employee...)
- auto-generated folder for the project according to a template

Following the success of this database within my team, I then created other databases based on this model to manage other aspects of the company:
- quality management system
- laboratory information management system

As the years go by, this little Access database had become a real small ERP ! 


## FR


Mon premier plongeon dans l'univers des bases de données ! Quand je suis arrivé, les contrats et les clients de l'entreprise était gérée avec des feuilles excel illisibles. Dans le cadre de la démarche qualité, il fallait consolider tout cela. L'objectif était donc de créer un système permettant de limiter la double saisie pour les utilisateurs, les incohérences au niveau des chiffres, et le respect des procédures en place.

Cette petite base de données possède une multitude de fonction :
- gestion de la base client
- création des fiches affaires avec générateur des identifiants
- chiffrage des devis
- édition des factures
- saisie des temps des collaborateurs
- gestion à l'affaire et suivi de la rentabilité

Evidemment, sur le plan technique, cette base de données a essuyé les platres et certains choix auraient été différents aujourd'hui (comme coupler Access en front-end avec un SGBD type MySQL)

Elle a ensuite été complété par des modules (qui ne marchent plus ici car le code devrait être repris entièrement) :
- envoi d'alerte par email lorsque des seuils sont dépassés (rentabilité négative, aucun temps saisi pendant plusieurs semaines par un collaborateur...)
- génération d'un dossier affaire automatiquement sur le serveur lors de la création d'une affaire selon un modèle prédéfini

Suite au succès rencontré par cette base de donnée au sein de l'équipe, j'ai ensuite crée d'autres bases de données basé sur ce modèle afin de gérer d'autres aspects de l'entreprise :
- gestion du système de management de la qualité
- gestion du parc d'équipements de mesure du laboratoire

Cette base Access était devenu au fil du temps un véritable petit ERP ! 