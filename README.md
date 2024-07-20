### Game Recommendation

---

## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Dependencies](#dependencies)
6. [Configuration](#configuration)
7. [Documentation](#documentation)
8. [Examples](#examples)
9. [Troubleshooting](#troubleshooting)
10. [Contributors](#contributors)
11. [License](#license)

---

## Introduction
Game Recommendation is a system that suggests the five most similar Nintendo Switch games to a chosen game using data scrapping, data cleaning, unsupervised learning (K-means), and natural language processing (NLP).

## Installation
To install and run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/thaoquynh0603/game-recommendation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd game-recommendation
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter notebook `game_recommendation.ipynb`.
2. Run the notebook cells to generate game recommendations.

## Features
- Data scrapping using BeautifulSoup4.
- Data cleaning and preprocessing.
- Unsupervised learning using K-means clustering.
- Natural language processing for game similarity recommendations.

## Dependencies
- BeautifulSoup4
- pandas
- scikit-learn
- Jupyter Notebook

## Configuration
No specific configuration is required for this project. Simply ensure that all dependencies are installed.

## Documentation
Detailed documentation for each part of the project can be found within the Jupyter notebook `game_recommendation.ipynb`.

## Examples
An example of generating game recommendations:
```python
# Assuming you have already run the necessary cells for data preprocessing
chosen_game = 'The Legend of Zelda: Breath of the Wild'
recommended_games = get_recommendations(chosen_game)
print(recommended_games)
```

## Troubleshooting
- Ensure all dependencies are installed.
- Verify that the dataset `dataset.csv` is present in the project directory.
- Check that Jupyter Notebook is properly installed and configured.

## Contributors
- Thao Quynh

## License
This project does not currently have a license.
