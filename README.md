# DS_6372_Project1 WHO

Contributors: Suchismita Moharana and Jamie Vo

### Abstract:
Many factors affecting life expactancy have been studied in detail by stataticians through out history, with the exeption
of immunization. The data set is narrowed to the year 2014...

#### Introduction
Many factors affecting life expactancy have been studied in detail by stataticians through out history. One variable that
 has recently recieved mass attention is immunization. Reviewing past studies, it was determined that immunization was not 
 taken into account. These could range from Hepatitis B, Polio to Diphtheria, and many more. The data set studied includes data from 2000-2015 and varying countries. In order to simplify the analysis, 2014 is selected to be the sole year. 

#### Analysis
The analysis consisted of the following models:

1. Linear Regression
2. Linear Regresson with interaction terms
3. KNN
4. Decision Tree
5. RandomForest

Random forest has the hgihest predictability accuracy, but is the most complex of all the models, with the highest MSE. Simple linear regressoin proved to be the most interpretable, but as expected, has the lowest accuracy. Linear regression with the interaction terms balances bias and precision by having a limited number of variables and enough to increase the accuracy in a test/train set.

#### Conclusion
Income, Adult mortality, and HIV/AIDs are the most significant variables when predicting life expectancy. Immunizations fail to have a significant impact on the variable in question.
