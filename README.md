# Predicting Wine Quality 🍷

- [Predicting Wine Quality](#predicting-wine-quality)
  - [Introduction](#introduction)
  - [Usage](#usage)
  - [Learning](#learning)
  - [Analysis](#analysis)
    - [Why Supervised Learning?](#why-supervised-learning)
    - [Why wine prediction?](#why-wine-prediction)
    - [Benefits of wine prediction](#benefits-of-wine-prediction)
    - [Research](#research)
    - [Findings](#findings)
      - [Count vs Qualoty](#count-vs-quality)
      - [Pie Chart](#pie-chart)
      - [Citric Acid Feature](#citric-acid-feature)
      - [Correlation with Heatmap](#correlation-with-heatmap)
  - [Conclusion](#conclusion)

## Introduction

Using supervised learning, in this project, predicting wine quality from the dataset that has been made available by Cortez. et Al from 2009. The dataset can be found from the citations
folder. Throughout this project, we use different python libraries such as `pandas` for parsing and working with the datset, `seaborn` and `matplotlib` for using it for plotting, and
`numpy` for working with the data. 

For the machine learning aspect, the models were taken from `sklearn` and they have been trained on the dataset as mentioned above.

We will build a supervised machine learning model to predict the color of wines whether the wine is white or red in color

## Usage

The code is stored as a `jupyter` notebook. To run the code, please open the file in jupyter and use run all command to run the code.

## Learning

## Analysis

### Why Supervised Learning?

### Why wine prediction?

### Benefits of wine prediction

### Research

### Findings

#### Count vs Quality
The below represents that in the dataset we have more average quality wines rather than the low/bad or high/good quality wine. A general observation, of a Gaussian distribution trend can be seen in the data.
![Count Vs Quality](https://github.com/nipun1992/Predicting-Wine-Quality/blob/main/pics/count%20vs%20quality.png)

#### Pie Chart
![Pie Chart](https://github.com/nipun1992/Predicting-Wine-Quality/blob/main/pics/Pie%20Chart.png)


#### Citric Acid Feature
![Citric Acid Feature](https://github.com/nipun1992/Predicting-Wine-Quality/blob/main/pics/citric_acid.png)

In the heatmap, if there are any 2 independent features that are highly correlated i.e. 80% or more, then we can drop 1 of those 2 features because both those features are serving the same purpose. We can see that density and 'residual sugar' features have a `pearson correlation coefficient of 0.83` i.e. *83% and thus we can drop 1 of these 2 features*. But in the dataset of red wines, these 2 features are not strongly correlated and thus we cannot drop 1 amongst these 2 features from the red wine dataset.

### Correlation with Heatmap
![Heatmap](https://github.com/nipun1992/Predicting-Wine-Quality/blob/main/pics/heatmap.png)


Hence, We retained the features.

## Conclusion

