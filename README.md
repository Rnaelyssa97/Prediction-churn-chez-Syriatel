**Prédiction du désabonnement Client**

**Contexte du projet**

L’objectif de ce projet est de prédire les clients susceptibles de cesser d’utiliser le service (churners) à partir d’un jeu de données de 3333 clients.
L’identification précoce de ces clients permet à l’entreprise de mettre en place des stratégies de fidélisation adaptées.

**Jeu de données**

Taille : 3333 clients

Colonnes : 21 (informations sur l’usage des services, plan international, appels au service client, etc.)

**Répartition des classes :**

Non-Churn : 2850 (~86%)

Churn : 483 (~14%)

Problème identifié : Déséquilibre des classes

**Méthodologie**

1.	Exploration des données

⦁	Vérification des valeurs manquantes : aucune

⦁	Analyse des types (numériques & catégorielles)

⦁	Visualisations (matplotlib, seaborn, pandas profiling)

2. Préparation des données

⦁	Encodage des variables catégorielles

⦁	Normalisation des variables numériques

⦁	Division en train/test

3. Modélisation

⦁	Algorithme choisi : Decision Tree Classifier et Regression logistique

⦁	Optimisation : GridSearchCV (max_depth, min_samples_split, min_samples_leaf)

⦁	Comparaison avant et après optimisation

4. Évaluation

Métriques utilisées : Accuracy, Precision, Recall, F1-score

**Résultats :**

L’arbre optimisé offre un meilleur équilibre entre précision et rappel

Sur le test set, 70 clients churners ont été correctement identifiés

Résultats principaux

Le modèle a atteint une bonne performance de classification malgré le déséquilibre des classes.

La capacité à identifier les clients churners permet de cibler les actions de rétention.

Nombre de churners prédits : 70 (dans l’échantillon de test).

**Conclusion**

Le travail réalisé a atteint l’objectif initial :
⦁	Identifier les clients à risque de churn
⦁	Fournir une base d’aide à la décision pour des actions de fidélisation
⦁	Démontrer l’efficacité d’un modèle simple (arbre de décision) après optimization






##  Données
Source : Kaggle


##  Outils utilisés
- Python (Jupyter Notebook)
- Pandas / Matplotlib/scikit learn
- Git / GitHub


##  Auteur
Nael Yssa Robert - Aout 2025
www.linkedin.com/in/naël-yssa-robert-83297a20b

