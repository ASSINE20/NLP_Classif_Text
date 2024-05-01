# NLP_Classif_Text

## By Géraud ASSINE

Construire un modèle pour la classification de texte (critiques) de films selon une tonalité positive ou négative.

## Chargement des données
- Utilisation de la librairie pandas pour importer les données(fichiers parquet)

## Exploration des données
Avoir un apperçu sur les données.

## Prétraitement du texte
- ### Tokenization
  Diviser le texte en mots, phrases ou sous-phrases significatifs, appelées tokens.
- ### Suppression des caractères alphabétiques non numériques
  Retirer les symboles, les caractères spéciaux et les emojis.
- ### Suppression des stopwords
  Suppression des mots qui n'apportent pas de sens à la phrase.

## Définition des ensembles: trainingset, testset et validationset

D'une part, application du baseline Bag Of Word puis construire des modèles de Régression Logistique et Random Forest.

D'autre part, application du baseline TF-IDF et construction des des modèles de Régression Logistique et Random Forest.

## Reccurent Neural Network (LSTM)
- Utilisation d'un modèle préentrainé word2vec afin d'applliquer le modèle LSTM.
- Preparation Embedding Layer.
- Création de l'architecture du modèle LSTM avec l'optimizer Adam.


