# Formation en Deep Learning appliquée aux mathématiques

## Introduction

Bienvenue dans ce projet issu de ma formation en Deep Learning appliquée aux mathématiques. Après avoir suivi la formation proposée par la chaîne YouTube **Machine Learnia**, j'ai reproduit les concepts abordés à travers des démonstrations mathématiques et des implémentations pratiques. 

Cette formation m'a permis de comprendre en profondeur les bases du Deep Learning, allant des modèles simples comme le perceptron à des réseaux de neurones complexes avec plusieurs couches.

### Programme de la formation

1. **Le perceptron simple** :
 - Écriture et compréhension des formules mathématiques.
 - Calcul de la performance avec la fonction coût (Log Loss).
 - Entraînement avec la descente de gradient.
 - Implémentation à l'aide de Numpy et manipulation de matrices.

2. **Extension au réseau de neurones** :
 - Construction d'un réseau de neurones avec plusieurs perceptrons.
 - Programmation de la Forward Propagation et Back Propagation.
 - Démonstrations mathématiques et calcul des gradients.

3. **Ajout de complexité au réseau** :
 - Ajout de neurones et de couches dans le réseau.
 - Introduction et implémentation de différentes fonctions d'activation :
 - Tangente Hyperbolique.
 - ReLU.
 - Softmax.
 - Optimisation et amélioration du code pour permettre la création de réseaux génériques.

Cette approche progressive suit naturellement l’histoire et la pédagogie expliquées dans la formation **Machine Learnia**.

---

## Contenu du Dépôt

Ce dépôt contient les fichiers suivants :

### Jupyter Notebooks

1. **[01 - Création d'un 1er neurone.ipynb](./01%20-%20Création%20d'un%201er%20neurone.ipynb)** 
 Implémentation d'un perceptron simple avec calcul de la fonction coût et entraînement via descente de gradient.

2. **[02 - 1er neurone appliqué chat VS chien.ipynb](./02%20-%201er%20neurone%20appliqué%20chat%20VS%20chien.ipynb)** 
 Exemple pratique : classification binaire entre "chat" et "chien" avec un perceptron.

3. **[03 - Réseau de neurones à 2 couches.ipynb](./03%20-%20Réseau%20de%20neurones%20à%202%20couches.ipynb)** 
 Introduction à un réseau de neurones à deux couches avec démonstrations de Forward et Back Propagation.

4. **[04 - Réseau de neurones profond.ipynb](./04%20-%20Réseau%20de%20neurones%20profond.ipynb)** 
 Construction d'un réseau de neurones profond avec plusieurs couches et fonctions d'activation avancées.

### Autres Fichiers

- **[README.md](./README.md)** : Ce fichier, pour une description complète de la formation et des fichiers inclus.
- **[testset.hdf5](./testset.hdf5)** : Jeu de données de test pour l'évaluation des modèles.
- **[trainset.hdf5](./trainset.hdf5)** : Jeu de données d'entraînement pour l'entraînement des modèles.
- **[utilities.py](./utilities.py)** : Fonctions utilitaires pour l'entraînement et l'évaluation des modèles.
