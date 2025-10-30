ForestCover-PL — Classification des types de couvert forestier

**Objectif**

Construire un modèle qui prédit le type de couvert forestier (7 classes) à partir de 54 variables tabulaires (caractéristiques du site), en s’appuyant sur un réseau de neurones (MLP) et le framework PyTorch Lightning pour un entraînement structuré et reproductible. *TP_1_2_solution.ipynb*

***Description du projet*** 

**Données :** le jeu CoverType est chargé via <code>sklearn.datasets.fetch_covtype</code>, puis scindé en train / validation / test avec stratification pour préserver les proportions de classes. *TP_1_2_solution.ipynb*

**Préparation :** les tableaux sont convertis en tenseurs PyTorch et empaquetés en DataLoader pour l’entraînement/évaluation par mini-lots. *TP_1_2_solution.ipynb*

**Modèle :** un Perceptron Multicouche séquentiel 54 → 128 → 64 → 7 est entraîné pour la classification multiclasse. *TP_1_2_solution.ipynb*

**Entraînement & évaluation :** l’entraînement et l’évaluation finale sont fait sur un jeu de test séparé avec une accuracy équilibrée (macro).*TP_1_2_solution.ipynb*

Les notebooks d’énoncés rappellent les concepts Lightning/DataLoader sur des exemples pédagogiques, aidant à contextualiser la structure du projet. *TP_1_1_énoncé.ipynb, TP_1_2_énoncé.ipynb*

