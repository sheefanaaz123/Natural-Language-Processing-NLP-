# Text Categorization Project 
## Problem Statement 
The project aims to develop a Natural Language Processing (NLP) solution for categorizing customer grievances. Customer grievances can manifest in various forms, including issues related to the quality of service, access and availability, billing/financial disputes, benefit packages, and marketing. In this project, we have trained a classification model capable of classifying text descriptions into appropriate categories and subcategories. 
## Objectives
### Data Preprocessing 
- Load a dataset containing customer grievances, with a primary focus on the 'Description of the Grievance' column. - Preprocess the data by cleaning and transforming the text to facilitate meaningful analysis. 
### Label Encoding 
- Encode the target labels, specifically 'Grievance Category' and 'Grievance SubCategory,' into numerical values to prepare them for machine learning algorithms. 
### Feature Engineering
- Convert text data into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. This step helps represent text data in a format suitable for machine learning models. 
### Model Building and Evaluation
- Employ several machine learning classifiers, including K Nearest Neighbors, Decision Tree, Random Forest, Logistic Regression, SGD Classifier, Naive Bayes, and SVM Linear, to categorize customer grievances into predefined categories. 
- Predict both 'Grievance Category' and 'Grievance SubCategory' separately using these classifiers. 
### Ensemble Modeling 
- Construct a Voting Classifier to combine predictions from multiple base classifiers. This ensemble approach aims to enhance prediction accuracy and robustness.
### Performance Evaluation 
- Evaluate the accuracy of each individual classifier and the ensemble model. 
- Generate classification reports to provide detailed insights into model performance.
## Outcome 
The project seeks to provide a robust and accurate solution for automatically categorizing customer grievances based on textual descriptions. This automated categorization can help organizations streamline their grievance handling processes, allocate resources efficiently, and enhance customer satisfaction by ensuring that grievances are directed to the appropriate teams for resolution. The use of machine learning and ensemble techniques allows for a more efficient and objective handling of customer grievances. 
## Results
### Category Prediction Results: 
- Achieved the highest accuracy of 62.42% using the Voting Classifier model. 
### Sub-Category Prediction Results:
- Achieved the highest accuracy of 37.58% through the combined efforts of the Voting Classifier and SVM Linear models.
  
--- *Note: This README provides an overview of the Text Categorization project. For detailed implementation and code, refer to the project files and documentation.*
