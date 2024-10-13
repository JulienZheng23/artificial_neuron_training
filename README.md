# Artificial Neuron Training

Ce projet met en œuvre un simple neurone artificiel pour la classification binaire. Le modèle est entraîné sur un jeu de données d'images, et il est évalué en traçant les courbes d'apprentissage, et en ajustant les hyperparamètres pour trouver les meilleurs résultats.

## Fonctionnalités

1. **Normalisation des données** : Les images sont normalisées de la plage [0-255] à [0-1].
2. **Aplatissement des images** : Les images de taille 64x64 sont aplaties en vecteurs de 4096 dimensions.
3. **Entraînement du modèle** : Le neurone est entraîné sur le jeu de données, avec traçage des courbes d'apprentissage (loss et précision).
