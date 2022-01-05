# Etude de marché

## Contexte

"La poule qui chante" est une entreprise française d'agroalimentaire" qui souhaite se développer à l'international. Elle souhaite avoir la liste des pays favorables à son exportation de poulet.

Dans ce projet, nous sommes missionné pour cibler les pays potentiels en réalisant une étude de marché à partir de données.

## Méthodologie

Les données utilisées proviennent de la base de données de la FAO (Food and Agriculture Organization). J'ai choisi comme données :

Régime alimentaire :
- Disponibilité alimentaire par habitant
- Disponibilité en poulet par habitant
- Quantité de poulet consommée
- Quantité de poulet produit et importée par pays

Population et pouvoir d'achat :
- Evolution de la population
- PIB par habitant
- Stabilité politique des pays

Deux notebook jupiter ont été crées, l'un pour la préparation des données et l'autre pour l'analyse de ces dernières.

Dans la partie analyse, j'ai réalisé en premier lieu un classification ascendante hiérarchique (CAH) illustré par un dendogramme. Puis, les pays ont été classifiés par la méthode des K-means. Un comparatif de ces deux méthodes de classification a été réalisé.

Une ACP a été réalisée afin de visualiser les résultats, les groupes et comprendre les liens entre les variables.

## Compétences mises en oeuvre

- Effectuer un clustering simple
- Explorer des données pour synthétiser des variables

*Ce projet a été réalisé dans le cadre de la formation [Data Analyst](https://openclassrooms.com/fr), d'OpenClassrooms.*