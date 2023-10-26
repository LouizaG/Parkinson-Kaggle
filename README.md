# Parkinson-Kaggle
# Projet_kaggle “Parkinson's Disease Progression Prediction”

# Contexte : 
Dans notre étude, nous nous intéressons aux patients diagnostiqués avec la maladie de Parkinson et qui reçoivent soit une CSF-MS semi-annuelle, soit une CSF-MS annuelle en même temps que le MDS-UPDRS.  La CSF-MS mesure l'abondance des protéines et des peptides chez le patient - dans le cas présent, 227 protéines et 971 peptides - tandis que le MDS-UPDRS  est un score de pronostic composé de quatre valeurs.
L'ensemble de données utilisé dans cette étude provient d'un concours Kaggle  sur la prédiction de la progression de la maladie de Parkinson. Ce concours a impliqué 248 patients qui ont visité un hôpital environ tous les six mois, ce qui a conduit à l'attribution de scores MDS-UPDRS et à la création semestrielle ou annuelle de résultats de tests CSF-MS

# Objectif : 
Utilisation de données protéiques et peptidiques de patients atteints de la maladie de Parkinson pour prédire la progression de la maladie. Pour ce faire, nous construisons un algorithme de deep learning capable de prédire les scores UPDRS de patients à partir de données cliniques et biologiques, pour pouvoir, à terme, mieux adapter la prise en charge des patients.

## Setup your environment

Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).

Clone the repository

```
git clone https://github.com/{name}.git
```

Move to the new directory

```
cd Project_kaggle
```

Create the Project_Kaggle conda environment:

```
conda create --name Project_kaggle_env
```

Load the `Project_Kaggle` conda environment:

```
conda activate Project_Kaggle_env
```

To deactivate an conda active environment, use

```
conda deactivate
```

Add python in yout environment:

```
conda install python
```

Add jupyter in your environment:

```
conda install jupyter
```

Run jupyter notebook

```
jupyter notebook
```

1) Run the file Kaggle_Exploratory_Analysis.ipynb to see the first analyzes

2) Run the file Model_LSTM_CNN.ipynb to have all the results

3) Run other files 
