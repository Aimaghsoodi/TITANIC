# TITANIC
Titanic Data R Markdown Codes 

### Overview

The Titanic sank on April 15, 1912. Out of the 2224 passengers and crew, 1502 died due to a lack of lifeboats. Luck played a part in who survived but it seems some groups had a higher rate of survival. Please review the Data Description and answer the questions on the following pages.

### Data Description

The provided data is in two csv's:

• training set (train.csv) • test set (test.csv)

The training set covers the fate of 891 of the 1502 passengers that died. Use the training set to build your model. The features you decide on will predict the fate of the remaining 418 passengers (in the test set).

The test set does not provide the passengers fate but does provide similar information as the training set. Use this set to check your model performance on unseen data. Then make a prediction on whether each passenger survived when the Titanic sunk.

### Variable Notes

**pclass**: A proxy for socio-economic status (SES)

-   1st = Upper
-   2nd = Middle
-   3rd = Lower

**age**: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**sibsp**: The dataset defines family relations in this way.

**Sibling**: brother, sister, stepbrother, stepsister

**Spouse**: husband, wife (mistresses and fiancés were ignored)

**parch**: The dataset defines family relations in this way.

**Parent**: mother, father

**Child**: daughter, son, stepdaughter, stepson

**parch=0**:Some children travelled only with a nanny
