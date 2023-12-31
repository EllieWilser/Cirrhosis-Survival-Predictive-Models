# Cirrhosis-Survival-Predictive-Models
Cirrhosis of the liver is late stage scarring of the liver which is caused by other liver diseases and conditions like hepatitis and chronic alcoholism. This data used in my predictive analysis was collected by the Mayo Clinic in their primary biliary cirrhosis of the liver trial which was conducted between 1974 and 1984.
## Summary
### Data Preprocessing
In the data preprocessing section, I first started by removing the ID column because it had no use in my analysis. Next I handled the the empty entries in the data set by removing them because I only wanted to use properly collected data. Next, I had to change the data types from strings to numeric data types.
### Exploritory Data Analysis
In the EDA section, the outliers were examined in the dataset by graphing histograms of the different features. It was shown that there were significant amounts of outliers in the dataset, and they were replaced with the median of the given feature. Next, the nominal and ordinal were encoded and a correlation analysis was done to see if any feature could be removed. None of the correlations was above .7, so they were all deemed important at that time.
### Decision Tree, Random Forest, and Gradient Boosting Classifiers
These different models were implemented with all the features and the feature importance histograms were graphed. Next, the accuracy scores were examined and the Random Forest Classifier performed the best compared to the other models. Looking at the feature importance for the models, the drug feature was not deemed important by the model. Looking at the correlation of the drug and the other features, which was close to zero, this could mean that the drug was not effective. Further examination would need to be done to see if the drug was effective.

## Running the Program
1. Download the dataset which is a csv file.
2. Download the Python Notebook file.
3. Change add the location of the file in the read csv function to the location of where you saved the csv
4. Run the script.
