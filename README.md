# P4-OC-DataScientist

## Projet : Anticipez les besoins en consommation de bâtiments
Projet 4 de la formation OpenClassrooms du parcours data scientist

## Objectifs du projet
La ville de Seattle a pour objectif de devenir neutre en émissions de carbone en 2025.
Etant employée par la ville de Seattle, mon équipe s’intéresse de près à la consommation et aux émissions des bâtiments non destinés à l’habitation.

Des relevés minutieux ont été effectués par les agents de la ville en 2016. Cependant, ces relevés sont coûteux à obtenir, et à partir de ceux déjà réalisés, on veut tenter de prédire les émissions de CO2 et la consommation totale d’énergie de bâtiments non destinés à l’habitation pour lesquels elles n’ont pas encore été mesurées.

On cherche également à évaluer l’intérêt de l’"ENERGY STAR Score" pour la prédiction d’émissions, qui est fastidieux à calculer avec l’approche utilisée actuellement par votre équipe. On l'intégrera dans la modélisation et on jugera de son intérêt.

On se posera donc les questions suivantes :
- Les relevés de consommation d’énergie et d’émission de gaz à effet de serre sont coûteux à obtenir : peut-on les prédire à partir des données structurelles des bâtiments et des relevés déjà effectués ? 
- L’Energie Star Score est fastidieux à calculer :  Est-il vraiment intéressant de l’intégrer dans le modèle de prédiction ?

### Données à disposition : 
Données issus des relevés effectués par les agents de la ville de Seattle en 2016.

Les principales variables sont : 
- Situation géographique de la propriété : la ville, l’Etat, le quartier, la latitude, la longitude 
- Données structurelles : Nombre d’étages, nombre de bâtiment, année de construction, surface brute totale du batiment et des parkings
- Utilisation de la propriété : type de propriété, utilisation principale de la propriété et la surface brute ainsi que première, deuxième et troisième utilisation de la propriété et leurs surfaces brutes associées
- Données énergétiques : 
  - La quantité annuelle de vapeur (kBtu), d’électricité (kWh) et de gaz naturel (kBtu) consommés par la propriété
  - La quantité annuelle d'énergie consommée par la propriété à partir de toutes les sources d'énergie
  - La quantité totale d'émissions de gaz à effet de serre libérés dans l'atmosphère à la suite de la consommation d'énergie de la propriété 
- Energy Star Score : note qui évalue la performance énergétique globale d’une propriété


### Missions : 
1) Réaliser une courte analyse exploratoire.
2) Tester différents modèles de prédiction afin de répondre au mieux à la problématique.


## Compétences évaluées :
- Adapter les hyperparamètres d'un algorithme d'apprentissage supervisé afin de l'améliorer
- Évaluer les performances d’un modèle d'apprentissage supervisé
- Mettre en place le modèle d'apprentissage supervisé adapté au problème métier
- Transformer les variables pertinentes d'un modèle d'apprentissage supervisé

## Découpage des dossiers

- Saubot_Julie_1_notebook_exploratoire_022023.ipynb : notebook comportant l'analyse exploratoire des données
- Saubot_Julie_2_notebook_prediction_022023.ipynb : notebook comportant la prediction des émissions de CO2
- Saubot_Julie_3_notebook_prediction_022023.ipynb : notebook comportant la prediction de la consommation d'énergie
- Saubot_Julie_4_presentation_022023.pptx : support de présentation pour la soutenance
  
## Lien utiles

- Données utilisées : https://data.seattle.gov/Permitting/2016-Building-Energy-Benchmarking/2bpz-gwpy/about_data
