# Introduction à Python + Jupyter

## Environnement de travail

Pour les TDs, il y aura deux possibilités:

1. Installez Python et Jupyter
2. Utilisez [Google Colab](https://colab.research.google.com/)

## Utilisation basique

Lancez un notebook et dessinez les fonction cosinus et sinus à l'aide de Numpy et Matplotlib

## Chargement de données

Chargez le fichier [diabetes.csv](diabetes.csv) dans un *notebook* Python
(conseil: utilisez la bibliothèque `pandas`), et essayez de répondre aux questions suivantes:

- Combien y'a t-il de lignes ? De colonnes ?
- Quelle est la moyenne de `pregnancies` ? Son écart type ?
    - Moyenne: vous devez trouver `3.8450520`
    - Écart type: vous devez trouver `3.3673836`
- Affichez un histogramme des ages des personnes de la liste
- Récupérez la liste des gens qui ont moins de 40 ans
- Affichez `age` vs `pregnancies` pour ces personnes
- Faites la même chose, en mettant de couleur différente les points qui ont un `Outcome` différent
- Essayez d'utiliser de trouver des indicateurs qui permettraient de bien séparer les données
(classifier), et de construire un modèle simple qui permettrait de prédire la valeur de `Outcome`
