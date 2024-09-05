# K-Nearest Neighbors (KNN) Pokémon Classifier

A K-Nearest Neighbors (KNN) classifier implemented from scratch in Python, trained on Pokémon statistics to predict if a Pokémon is legendary.

## Features

- 🧠 KNN algorithm
- 📊 Trained on Pokémon stats (HP, Attack, Defense, etc.)
- 🔄 Dataset normalization
- ⚖️ Accuracy evaluation on test data

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/twotimesgi/KNN.git
2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
3. Run the classifier
    ```bash
    python knn_pokemon_classifier.py

## Input Parameters

The KNN classifier was trained using the following Pokémon statistics:

- **Type 1:** Primary type of the Pokémon (e.g., Fire, Water)
- **Type 2:** Secondary type of the Pokémon (if applicable)
- **Total:** Total stats (sum of HP, Attack, Defense, Sp. Atk, Sp. Def, Speed)
- **HP:** Hit Points (health)
- **Attack:** Physical attack strength
- **Defense:** Physical defense strength
- **Sp. Atk:** Special attack strength
- **Sp. Def:** Special defense strength
- **Speed:** Speed in battle
- **Generation:** The generation in which the Pokémon was introduced

## Results

- **Dataset Records:** 800
- **Training Dataset Records:** 560
- **Testing Dataset Records:** 240
- **k (Number of Neighbors):** 7
- **Accuracy:** Achieved around 90% accuracy on the test dataset.

## Technologies

- Python 3
- Scikit-learn (for train-test split)
- CSV for dataset handling


