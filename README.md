# Application Gestion de Caserne de Pompiers

Ce projet est une **application desktop** développée en **C#** et utilisant le framework **.NET (Windows Forms)**. Son objectif est de **modéliser et d'optimiser la gestion opérationnelle et administrative d'une ou plusieurs casernes de pompiers (SQLite)**.


## Fonctionnalités Clés 

L'application offre un ensemble complet de fonctionnalités pour la gestion interne d'une caserne :

* **Gestion du Personnel**
    Création, modification, suppression et consultation des fiches pompiers. Ce volet prend en compte et gère les habilitations (ou compétences) de chaque pompier.

* **Gestion des Engins**
    Suivi du matériel et des véhicules. Le système permet de connaître leur type, leur état (par exemple, en panne ou en mission), leur disponibilité et de les visualiser par caserne.

* **Gestion des Missions/Interventions**
    Enregistrement détaillé des incidents. L'application fournit un tableau de bord des missions en cours, permettant la clôture rapide et l'édition des rapports associés.

* **Rapports et Statistiques**
    Génération de comptes rendus d'interventions en PDF. Le volet affiche des statistiques clés (telles que l'utilisation des engins, le nombre d'interventions par type de sinistre ou les habilitations les plus sollicitées) à destination des régulateurs.

* **Administration et Droits d'Accès**
    Gestion des droits d'accès, notamment pour l'aspect « mise à jour » des données qui est réservé aux utilisateurs disposant des droits d'administrateur.

## Voici quelques exemples de volets :

<img width="1176" height="775" alt="tableau_de_bord" src="https://github.com/user-attachments/assets/65b76902-8f16-4785-b0e1-bb0b4bf9f531" />
<img width="1182" height="781" alt="engins" src="https://github.com/user-attachments/assets/e8bbd559-3e2e-4b82-856e-3fdfea669208" />
<img width="1182" height="781" alt="gestion_personnel" src="https://github.com/user-attachments/assets/c1dea967-7b9b-484d-ae2a-e1f355d3eff5" />


## Technologies

* **Langage & Framework** : C# avec Windows Forms (.NET) pour l'interface utilisateur.
* **Gestion des Données** : L'application devait varier son utilisation de la base de donnée entre :
    * **Mode Connecté** : Base de données locale (fichiers `.db` ou SQLite).
    * **Mode Déconnecté** : Utilisation d'un DataSet et de fichiers XML pour la sauvegarde et la manipulation des données.


## Équipe

Ce projet a été réalisé avec :

* **Yann STOLL-GEYER** 
* **Valentin JAECKEL** 


## Installation et Lancement

Pour exécuter et contribuer au projet localement, suivez ces étapes :

1.  **Prérequis** : Windows et Visual Studio avec support WinForms et .NET Desktop Development.
2.  **Cloner le dépôt** :
    git clone https://github.com/valentin-petit/Application-Gestion-Caserne-de-pompier-C-.git.


## Licence
Ce projet est distribué sous la Licence MIT.
