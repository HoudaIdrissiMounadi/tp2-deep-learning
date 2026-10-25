# TP2 – Apprentissage Profond avec TensorFlow / Keras

**Module :** Technologies IA – ENSA Fès (ILIA2)
**Professeur :** Youness IDRISSI KHAMLICHI

Ce dépôt contient la réalisation du TP2 :

| Exercice | Dataset | Contenu |
|---|---|---|
| 1 | MNIST | Réseau Dense (ANN) pour reconnaître des chiffres manuscrits |
| 2 | Fashion-MNIST | ANN, comparaison des fonctions d'activation, CNN, matrice de confusion, data augmentation |

Chaque notebook contient le code complet, ainsi que les réponses aux questions du TP.

## Structure

```
tp2-deep-learning/
├── exercice1_mnist.ipynb
├── exercice2_fashion_mnist.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation

```bash
python -m venv venv
source venv/bin/activate        # Windows : venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Les datasets MNIST et Fashion-MNIST sont téléchargés automatiquement par Keras (`keras.datasets`).

## Exécution sans installation

Ouvrir les notebooks dans [Google Colab](https://colab.research.google.com) (File > Upload notebook ou File > Open notebook > GitHub).

## Résultats

À compléter après exécution :

| Modèle | Précision test |
|---|---|
| ANN – MNIST | … |
| ANN – Fashion-MNIST | … |
| CNN – Fashion-MNIST | … |
| CNN + Data Augmentation | … |

## Auteur

Étudiant(e) ENSA Fès – ILIA2
