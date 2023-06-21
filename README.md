# Sampling Assignment

This assignment involves the following steps and tasks:

## Step 1: Download the dataset
Download the dataset from the provided link.

## Step 2: Convert the dataset into a balanced class dataset
Transform the dataset into a balanced class dataset, ensuring an equal representation of different classes.

## Step 3: Applying 5 Models using Pycaret
Use the Pycaret library to apply the following five models to the dataset:

1. Random Forest Classifier
2. Extra Trees Classifier
3. Gradient Boosting Classifier
4. Decision Tree Classifier
5. Ada Boost Classifier

## Sampling Techniques and Model Performance

The table below shows the performance of the five models using different sampling techniques:

| Sampling Technique | Random Forest | Extra Trees | Gradient Boosting | Decision Tree | Ada Boost |
|--------------------|---------------|-------------|------------------|---------------|-----------|
| Simple Random      |     1.000     |   1.000     |      1.000       |     1.000     |   1.000   |
| Systematic         |     1.000     |   1.000     |      0.997       |     0.981     |   1.000   |
| Stratified         |     1.000     |   1.000     |      1.000       |     0.994     |   1.000   |
| Cluster            |     0.780     |   0.841     |      0.871       |     0.738     |   0.864   |
