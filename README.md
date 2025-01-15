# Formation en Deep Learning appliquée aux mathématiques

## Introduction

Bienvenue dans ce projet issu de ma formation en **Deep Learning appliqué aux mathématiques**. Cette formation, proposée par la chaîne YouTube **Machine Learnia**, m’a permis d’acquérir une compréhension approfondie des concepts fondamentaux du Deep Learning. À travers des démonstrations mathématiques et des implémentations pratiques, j'ai exploré les bases du Deep Learning, du perceptron aux réseaux de neurones complexes.

Si vous souhaitez consulter la formation complète, vous pouvez la retrouver [ici](https://www.youtube.com/watch?v=XUFLq6dKQok&list=PLO_fdPEVlfKoanjvTJbIbd9V5d9Pzp8Rw).

## Objectifs de la formation

L'objectif principal de cette formation est de comprendre et de maîtriser les concepts mathématiques derrière les modèles de Deep Learning. Voici les étapes clés abordées tout au long de la formation :

1. **Le perceptron simple**  
   - Définition des formules mathématiques du perceptron.
   - Calcul de la performance avec la fonction coût (Log Loss).
   - Entraînement à l'aide de la descente de gradient.
   - Implémentation avec Numpy et manipulation des matrices.

2. **Extension au réseau de neurones**  
   - Construction d’un réseau de neurones avec plusieurs perceptrons.
   - Programmation de la propagation avant (Forward Propagation) et de la rétropropagation (Back Propagation).
   - Calcul des gradients et démonstrations mathématiques associées.

3. **Ajout de complexité au réseau**  
   - Ajout de neurones et de couches supplémentaires.
   - Introduction et implémentation des fonctions d'activation :
     - Tangente hyperbolique (Tanh).
     - ReLU (Rectified Linear Unit).
     - Softmax.
   - Optimisation du code pour créer des réseaux de neurones plus flexibles.

Cette approche progressive suit les étapes pédagogiques proposées par **Machine Learnia**, permettant une assimilation complète des concepts.

## Contenu du dépôt

Ce dépôt contient les éléments suivants :

### Jupyter Notebooks

- **[01 - Création d'un premier neurone.ipynb](./01%20-%20Création%20d'un%201er%20neurone.ipynb)**  
  Implémentation d’un perceptron simple, calcul de la fonction coût et entraînement via la descente de gradient.

- **[02 - 1er neurone appliqué chat VS chien.ipynb](./02%20-%201er%20neurone%20appliqué%20chat%20VS%20chien.ipynb)**  
  Application pratique : classification binaire entre "chat" et "chien" avec un perceptron.

- **[03 - Réseau de neurones à 2 couches.ipynb](./03%20-%20Réseau%20de%20neurones%20à%202%20couches.ipynb)**  
  Introduction à un réseau de neurones à deux couches avec les algorithmes de Forward Propagation et Back Propagation.

- **[04 - Réseau de neurones profond.ipynb](./04%20-%20Réseau%20de%20neurones%20profond.ipynb)**  
  Construction d’un réseau de neurones profond avec plusieurs couches et utilisation de fonctions d'activation avancées.

### Autres fichiers

- **[README.md](./README.md)**  
  Ce fichier, contenant une description complète de la formation et des fichiers inclus dans ce dépôt.

- **[datasets/testset.hdf5](./datasets/testset.hdf5)**  
  Jeu de données pour l’évaluation des modèles de Deep Learning.

- **[datasets/trainset.hdf5](./datasets/trainset.hdf5)**  
  Jeu de données d’entraînement utilisé pour l'apprentissage des modèles.

- **[utilities.py](./utilities.py)**  
  Fonctions utilitaires pour l’entraînement et l’évaluation des modèles.

---

## Conclusion

Ce projet vous offre une approche claire et détaillée pour comprendre les fondamentaux du Deep Learning appliqués aux mathématiques. Vous découvrirez les algorithmes de base et leur implémentation dans des réseaux de neurones. Grâce à cette formation, vous serez à même de concevoir vos propres modèles de Deep Learning et d'optimiser leur performance pour des applications réelles.

Si vous avez des questions ou souhaitez approfondir certains concepts, n’hésitez pas à consulter la formation complète [ici](https://www.youtube.com/watch?v=XUFLq6dKQok&list=PLO_fdPEVlfKoanjvTJbIbd9V5d9Pzp8Rw) ou à me contacter directement.
