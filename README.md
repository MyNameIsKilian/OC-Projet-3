# OC - Projet 3 - Parcours Data Scientist

### 🚀 Objectif

L'agence "Santé publique France" a lancé un appel à projets pour trouver des idées innovantes d’applications en lien avec l'alimentation. Vous souhaitez y participer et proposer une idée d’application.

Après avoir lu l’appel à projets, voici les différentes étapes que vous avez identifiées :

1- Traiter le jeu de données, en :

- réfléchissant à une idée d’application
- repérant des variables pertinentes pour les traitements à venir, et nécessaires pour votre idée d’application

2- Nettoyant les données en :
- mettant en évidence les éventuelles valeurs manquantes, avec au moins 3 méthodes de traitement adaptées aux variables concernées
- identifiant et en quantifiant les éventuelles valeurs aberrantes de chaque variable
- automatisant ces traitements pour éviter de répéter ces opérations

3- Tout au long de l’analyse, produire des visualisations afin de mieux comprendre les données. 
Effectuer une analyse univariée pour chaque variable intéressante, afin de synthétiser son comportement.

3- Confirmer ou infirmer les hypothèses à l’aide d’une analyse multivariée. Effectuer les tests statistiques appropriés pour vérifier la significativité des résultats.

4- Justifier votre idée d’application. Identifier des arguments justifiant la faisabilité (ou non) de l’application à partir des données Open Food Facts.

5- Rédiger un rapport d’exploration et pitcher votre idée durant la soutenance du projet.

### 💾 Dataset

Le jeu de données est stocké sur un bucket S3 d'OC [ici](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-scientist/P2/fr.openfoodfacts.org.products.csv.zip).
Les variables sont définies [à cette adresse](https://world.openfoodfacts.org/data/data-fields.txt).
    
### 🧰 Outils

- Python 3.9
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scipy