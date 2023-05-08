# Asteroids_Classification_Analysis
NASA Asteroids Classification

A potentially hazardous asteroid is with an orbit that can make close approaches to the Earth and is large enough to cause significant regional damage in the event of impact. By Identifying the potential hazardous asteroids, we can assess potential prevent the collision between the Earth and the asteroid. To achieve our goal to classify whether the asteroid is potentially hazardous or non-hazardous, we trained NASA Asteroids data with the Naive Bayes Classifier, Support Vector Machine, and Decision Tree. As a result, Decision tree modeling predicted hazardous asteroids with the best performance by achieving 99% accuracy.

https://github.com/Wook22/Asteroids_Classification_Analysis/blob/main/NASA.pdf

## Introduction

This project analyzed the Asteroids - NeoWs dataset to identify factors that could help classify an asteroid as potentially hazardous or not. Near Earth Objects (NEOs) are comets and asteroids that can come close to Earth's orbit, and understanding the factors that could make them hazardous is important for ensuring the safety of our planet.

## Data Analysis

The project began with exploring the dataset and identifying trends and relations between variables. We discovered that some variables shared similar distributions and that the data was imbalanced. To address this, we used a correlation heatmap to remove some variables that were overlapping or minority features.

We then used a dendrogram to visualize the relation between variables and discovered that 'hazardous' was related to several variables, including 'Est Dia in M(min)', 'Est Dia in M(max)', 'Est Dia in Miles(min)', 'Est Dia in Miles(max)', 'Orbital Period', and 'Aphelion Dist'. We used this information to guide our selection of features for modeling.

To address the imbalanced distribution of the target variable, we used Synthetic Minority Over-sampling Technique (SMOTE) to generate synthetic data for the minority class.

## Modeling

We trained three models - Naive Bayes Classifier, SVM, and Decision tree - to predict the hazard of an asteroid. The Decision tree model performed the best with 99% accuracy.

## Conclusion

Our analysis identified important factors that could help classify an asteroid as potentially hazardous. We also demonstrated the effectiveness of SMOTE in addressing imbalanced data and the superiority of Decision tree modeling for this classification problem. The findings of this project could help inform future efforts to identify and track potentially hazardous asteroids and protect our planet from potential impact.
