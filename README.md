# EDLD654-Final-Project

The repository is created for the final project of EDLD 654 Applied Machine Learning.


## [Data Source](https://archive.ics.uci.edu/ml/datasets/wine+quality)

Paulo Cortez, University of Minho, Guimarães, Portugal, http://www3.dsi.uminho.pt/pcortez

A. Cerdeira, F. Almeida, T. Matos and J. Reis, Viticulture Commission of the Vinho Verde Region(CVRVV), Porto, Portugal

@2009

## Data Set Information

Two datasets related to red and white vinho verde wine samples, from the north of Portugal, are available from the link above. For this project, only the dataset related with the quality of read wine samples is used. 

Link to the data:
```
wine_red <- readr::read_csv("https://raw.githubusercontent.com/shijing-z/EDLD654-Final-Project/main/winequality-red.csv")
```

### Relevant Papers:

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## Attribute Information:

For more information, read [Cortez et al., 2009](https://doi.org/10.1016/j.dss.2009.05.016).

### Input variables (based on physicochemical tests):

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

### Output variable (based on sensory data):

12 - quality (score between 0 and 10)

## Citation

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.

Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
