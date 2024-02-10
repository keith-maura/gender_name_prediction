# Gender Name Prediction
Maura Keith and Gauri Dandi
DS 4420
Prof Wallace
29 April 2022

## Abstract
The purpose of this project was to determine if gender can viably be predicted from a name itself. We found a number of gender datasets and implemented models using names with binary labels (male or female), categorical labels (male, female, or neutral), and continuous scales (ratio of male to female name occurances). Logistic Regression, Linear Regression, SVC, Random Forest, and LTSM models were all created to predict different data representations based on our cleaning methodologies. Such models that we built are more effective in predicting male or female names, but less effective against names that are "neutral", that is, names that can be assigned to either gender. Our models were also the most effective in categorizing Latin-based names, as the majority of our datasets consist of such naming structures. Our models were also the most accurate in detecting female names, since they typically end in a vowel and generally contain more vowels than male or neutral names. Simple models drawing upon manual feature engineering rely the most on the last letter of a name, whereas our neural network model drew upon the order of letters for more accurate results.
