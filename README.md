# Projet 3: Concevez une application au service de la santé publique
## Présentation:
L'agence "Santé publique France" a lancé un appel à projets pour trouver des idées innovantes d’applications en lien 
avec l'alimentation. Vous souhaitez y participer et proposer une idée d’application.
Pour ce projet, j'ai eu l'idée d'une application interactive. Lorsque l’utilisateur scanne un produit, l’application 
lui propose une alternative sans allergènes la plus saine possible et vendue en France. Ces alternatives contiennent 
peu d’additifs, sans huile de palme avec un bon nutri score (‘a’ ou ‘b’), cela correspond à des produits faibles en 
énergie, en glucides, en graisse, en sel, riche en protéines et en fibre. 
## Mission: 
Après avoir lu l’appel à projets, voici les différentes étapes que vous avez identifiées :

1) Traiter le jeu de données, en :

   Réfléchissant à une idée d’application.
   Repérant des variables pertinentes pour les traitements à venir, et nécessaires pour votre idée d’application.
   Nettoyant les données en :
   mettant en évidence les éventuelles valeurs manquantes, avec au moins 3 méthodes de traitement adaptées aux variables concernées,
   identifiant et en quantifiant les éventuelles valeurs aberrantes de chaque variable.
   Automatisant ces traitements pour éviter de répéter ces opérations
2) Tout au long de l’analyse, produire des visualisations afin de mieux comprendre les données. Effectuer une analyse univariée pour chaque variable intéressante, afin de synthétiser son comportement.
3) Confirmer ou infirmer les hypothèses à l’aide d’une analyse multivariée. Effectuer les tests statistiques appropriés pour vérifier la significativité des résultats.

4) Justifier votre idée d’application. Identifier des arguments justifiant la faisabilité (ou non) de l’application à partir des données Open Food Facts.

5) Rédiger un rapport d’exploration et pitcher votre idée durant la soutenance du projet.
## Données:
- Les données sont disponible sur le site officiel Open Food Fact : https://world.openfoodfacts.org/ et ont été
  téléchargés à cette adresse : https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-scientist/P2/fr.openfoodfacts.org.products.csv.zip
- Les variables sont définies à cette adresse : https://world.openfoodfacts.org/data/data-fields.txt

Les champs sont séparés en quatre sections :

Les informations générales sur la fiche du produit : nom, date de modification, etc.
Un ensemble de tags : catégorie du produit, localisation, origine, etc.
Les ingrédients composant les produits et leurs additifs éventuels.
Des informations nutritionnelles : quantité en grammes d’un nutriment pour 100 grammes du produit.
## Construction:
Dans ce dépôt, vous trouverez plusieurs fichiers:

- "nettoyage.ipynb" : notebook du nettoyage, de la préparation des données.
- "exploration.ipynb" : notebook d’exploration comportant une analyse univariée, multivariée, une réduction 
dimensionnelle, ainsi que les différentes questions de recherches associées


## Packages:
Différents packages Python ont été utilisés:

- pandas 1.4.4
- matplotlib 3.5.2
- numpy 1.23.5
- scipy 1.9.1
- seaborn 0.11.2
- scikit-learn 1.0.2
## Compétences: 
- Effectuer une analyse statistique multivariée 
- Communiquer ses résultats à l’aide de représentations graphiques lisibles et pertinentes
- Effectuer une analyse statistique univariée
- Effectuer des opérations de nettoyage sur des données structurées

