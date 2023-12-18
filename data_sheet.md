# Datasheet Template

As far as you can, complete the model datasheet. If you have got the data from the internet, you may not have all the information you need, but make sure you include all the information you do have. 

## Motivation

- For what purpose was the dataset created? 
The database aims to predict whether a loan application will be approved or rejected based on various features provided in the dataset. The dataset includes information about applicants' demographics, financial status, credit history, and other factors.

- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?
The sample dataset was extracted from Kaggle for learning purposes. 
 
## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 
Dataset consists of numerical (integers) and categorical (object)
- How many instances of each type are there? 
Number of: rows - 553 and columns - 13
- Is there any missing data?
There was no missing data
- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by    doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?
The dataset is sample data which can be used for investigative purposes. 

## Collection process

- How was the data acquired? 
The data was extracted from Kaggle 
- If the data is a sample of a larger subset, what was the sampling strategy? Not a larger sample 
- Over what time frame was the data collected? 

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 
- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 
 
 Exploratory data analysis: Loan_id field was removed from the dataset. Pair plots were created to compare the integer values, with the separation loan_status. Correlation matrix displayed the correlation among the integer variables. Count plots created for object variables. 
 Feature engineering convert categorical features to binary, logistic regression model instantiated again. The most important features were displayed on a bar plot. 

## Uses

- What other tasks could the dataset be used for? 
- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 
- Are there tasks for which the dataset should not be used? If so, please provide a description.

The data will only be used for learning purposes. 

## Distribution

- How has the dataset already been distributed? 
I downloaded a copy of the datsetset as a csv file and used the python read function.
- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?  NO 

## Maintenance

- Who maintains the dataset?
The dataset has been uploaded to Kaggle, as a one-off sample, therefore will not be maintained. 
