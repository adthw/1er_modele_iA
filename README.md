# 1er_modele_iA
Premiermodèle iA formation (sans les bibliothèques puis avec Sklearn)

[**Lien vers le notebook**](https://github.com/adthw/1er_modele_iA/blob/main/Premier-modele-iA.ipynb)

## Contexte du projet

### Régression linéaire simple :
L’un des modèles les plus simples d’apprentissage automatique est la régression linéaire. Lorsqu’il existe une relation linéaire entre les entités et la variable cible, il suffit de trouver l’équation de la droite dans l’espace multidimensionnel.

- Utilisez les bibliothèques de Python pour récupérer le contenu du jeu de données.
- Programmez les étapes du processus de machine learning en utilisant comme algorithme de machine learning la régression simple sur le jeu données nommé **reg_simple.csv **(Pour ce brief vous allez coder l’algorithme de régression simple sans utiliser la bibliothèque Scikit-learn)

Étapes à suivre :

- Récupération des données
- Visualisation des données
- Création du modèle (model(X,theta) )
- Fonction du coût (fonction_cout(X,Y,theta))
- Gradient (gradient(X,Y,theta))
- Descente du gradient (descente_gradient(X,Y,theta,alpha,n_iterations))
- Evaluer votre modèle en utilisant le coefficient de détermination
- Tracer la courbe de la fonction du coût selon les itérations

### Régression linéaire multiple :
L’exemple développé à partir de deux variables (régression simple) permet de comprendre la logique de la théorie de la régression mais il ne peut être généralisé de la sorte aux régressions multiples. Le système à deux équations à deux inconnus présenté se résolvait facilement comme on l’a vu. Les équations se compliquent avec plusieurs régresseurs, deux méthodes distinctes permettent de résoudre les équations. La première repose sur la connaissance des coefficients de corrélation linéaire simple de toutes les paires de variables entre elles, de la moyenne arithmétique et des écarts-types de toutes les variables. La seconde repose sur des calculs matriciels. En utilisant la méthode matricielle :
- Implémentez un modèle de régression multiple sur la base de données issue du fichier nommé boston_house_prices.csv (sans utiliser la bibliothèque Scikit-learn).
- Évaluez les résultats obtenus en utilisant la fonction mean_squared_error de sklearn

### Régression Polynomiale :

En utilisant les bibliothèques adéquates de Python, implémentez un modèle de régression polynomiale sur le jeu de données issu du fichier **Position_Salaire.csv** (sans utiliser la bibliothèque Scikit-learn).

- Appliquez le même modèle sur le jeu de données issu du fichier data/qualite_vin_rouge.csv
- Évaluez votre modèle.


## Scikit-Learn :

Refaire les 3 régressions avec le module Scikit-Learn
Comparez les résultats de prédiction avec la méthode normale

#### Pour aller plus loin :

- Réaliser une interface graphique qui permet de parcourir un jeu de données, le visualiser.
- Dans l’interface on peut avoir le choix d’utiliser un modèle spécifique (régression linéaire, polynomiale, multiple) pour l’appliquer à un jeu de données, de régler les paramètres (learning rate, iterations).
- Cette interface va ensuite nous permettre de visualiser notre modèle sur le jeu de données, de visualiser la fonction de coût et afficher les performances de notre modèle.

