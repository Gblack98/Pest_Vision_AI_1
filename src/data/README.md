# Dataset PestVisionAI

## Structure
- `raw/` : Données brutes (images et annotations).
- `processed/` : Données prétraitées et organisées pour l'entraînement.
  - `train/` : Données d'entraînement, organisées par classe.
  - `val/` : Données de validation, organisées par classe.
  - `test/` : Données de test, organisées par classe.
  - `class_names.txt` : Liste des classes.

## Classes disponibles
- Pepper_Bacterial_Spot
- Corn_Cercospora_Leaf_Spot
- Tomato_Early_Blight
- ...