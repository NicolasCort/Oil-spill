# Oil spill

## Introduction

This is a project that uses machine learning to detect oil spills . The model is trained on a dataset of satellite images with annotated oil spills to recognize oil spills in new data.


## Libraries

- Python 3.7 or later
- Numpy
- Seaborn
- Matplotlib
- Pandas
- Plotly
- Sklearn
- Xgboost

## Models
I used seven models:

- [RandomForest](https://en.wikipedia.org/wiki/Random_forest)
- [GradientBoosting](https://en.wikipedia.org/wiki/Gradient_boosting)
- [SVC]( https://en.wikipedia.org/wiki/Support_vector_machine)
- [DecisionTree](https://en.wikipedia.org/wiki/Decision_tree)
- [AdaBoost](https://en.wikipedia.org/wiki/AdaBoost)
- [XGBC](https://en.wikipedia.org/wiki/XGBoost)
- [MLP](https://en.wikipedia.org/wiki/Multilayer_perceptron)


## Results

The model is evaluated on a validation set after every epoch during training and its performance is plotted to monitor overfitting. The final results on the test set are reported in terms of accuracy:

<p align="center">
  <img src="results.png" width="800" height="300" align="center"> 
</p>


## Installation

Clone the repository to your local machine:

```bash
 git clone https://github.com/NicolasCort/Tumor_AI.git

```
Install the required packages using pip:

```bash
 pip install -r requirements.txt


```

## Contributions
Contributions to this project are welcome! If you want to contribute, please follow these steps:

- Fork this repository
- Clone the forked repository to your local machine
- Make the desired changes and commit them
- Push the changes to your forked repository
- Submit a pull request to this repository

