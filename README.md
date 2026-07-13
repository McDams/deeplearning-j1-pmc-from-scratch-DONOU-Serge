# Deep Learning J1 - PMC from scratch

Projet du jour 1 : Implémentation d’un perceptron multi-couches from scratch en numpy, puis comparaison avec Keras.

## Objectif
Comprendre concrètement :
- le forward pass
- les poids et biais
- les fonctions d’activation
- la binary cross-entropy
- la descente de gradient
- la backpropagation
- la différence entre numpy from scratch et Keras

## Organisation du repo

- `phase1_neurone_unique.ipynb` : neurone unique, sigmoid, BCE
- `phase2_descente_gradient.ipynb` : entraînement du neurone à la main
- `phase3_xor.ipynb` : XOR avec réseau 2-2-1
- `phase4_spirale_2d.ipynb` : spirale 2D avec réseau profond
- `phase5_keras_mnist.ipynb` : PMC Keras sur MNIST
- `phase6_activations.ipynb` : comparaison sigmoid / tanh / ReLU
- `phase7_optimizers.ipynb` : comparaison SGD / Adam
- `phase8_pipeline_personnel.ipynb` : pipeline complet numpy + Keras sur dataset sklearn
- `phase9_bonus_ablation.ipynb` : bonus, variantes et ablation
- `phase10_bonus_timing.ipynb` : bonus, comparaison de temps numpy vs Keras

## Stack
- Python
- NumPy
- Matplotlib
- scikit-learn
- TensorFlow / Keras
- Google Colab

## Auteur
Awadji Mahouna Serge DONOU

## Règles Git
- Commits fréquents
- Un commit = un changement logique
- Staging explicite avec `git add fichier`
- Pas de `git add .`