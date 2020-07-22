# FDA-Adverse-Event-Reporting-Sytem

### Description of the Dataset ####
FAERS is a computerised database for the spontaneous reporting System of adverse events and medication errors involving human drugs and therapeutic biological products.

#### Dataset files ######
There are different datasets for each category and a final dataset which I have prepared by merging all the csv files using one common feature in all the files that is primaryid.
Categories:
1. Therapy
2. Indication
3. Drug
4. Demographic
5. Reaction
6. Outcome
7. Report_Sources

##### Model Building ##########
The classification model has been built and has been converted into 2 categories from 5 categories for convience.
For the classification RandomForest Classifier has been used.
It mainly involves few basic steps:
a.Data cleaning
b.Exploratory Data Analysis (EDA)
c.EDA (Feature Engineering)
d.Normalisation
e.Model Building
