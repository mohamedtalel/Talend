
# Dimension Date 

Bonjour 

Je partage avec vous un job Talend qui permet de générer la Dimension Date dans une datawarehouse . 

Le composant TRowGenerator permet de génerer les dates souhaitées. Puis à partir de ces dates , on a fait les transformations necessaires dans Tmap pour ajouter des nouvelles colonnes dans la table (Quarter , Semester , WeekNumber etc ... )

Pour exécuter correctement ce job, veuillez suivre ces étapes :

-Changer les paramètres de connexion vers la base de données en remplaçant les valeurs par celles de votre base de données.

-Lors de l'exécution, choisissez l'intervalle de dates que vous souhaitez inclure dans votre dimension en insérant la date de début et la date de fin. Par défaut, le job génère les dates de l'année 2024. 







## Tech Stack

**outil:** Talend Open Source For Data integration

**Base de données:** PostgreSQL

