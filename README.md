# Fake-News-Detection  
  
**Project Overview**  
  
This project aims to build a machine learning model to classify news articles as fake or real. It utilizes several algorithms including Naive Bayes, Logistic Regression, Support Vector Machine, Random Forest, and Gradient Boosting.  

  
**Dataset**  
  
The dataset used for this project is fakenews.csv, which contains the following columns:   
  
  
`text`: The body of the news article  
`label`: The label indicating whether the news is fake (0) or real (1)  
`fakenews.csv`: The dataset file.  
`Fake_news_Pre.ipynb`: The Jupyter notebook containing the code for data analysis, visualization, and model training.  

**Key Steps**  

`Data Loading and Preprocessing`:

Load the dataset using pandas.  
Remove duplicates based on the text column.  

`Exploratory Data Analysis (EDA)`:  


Distribution of fake vs. real news using a count plot.  
Text length analysis.  
Word cloud visualizations for fake and real news headlines.

`Model Training and Evaluation`:  
  
Split the data into training and testing sets.  
Use TF-IDF vectorization for text data.  

`Train and evaluate the following models`:
  
Naive Bayes  
Logistic Regression  
Support Vector Machine  
Random Forest  
Gradient Boosting  
  
Compare models based on accuracy, precision, and recall.  

`Results`
  
Naive Bayes Model:  
  
- Accuracy: 76.11%
- Precision: 74.60%
- Recall: 53.71%
  
Logistic Regression Model:  
  
- Accuracy: 76.43%
- Precision: 74.71%
- Recall: 54.86%
    
Support Vector Machine Model:  
  
- Accuracy: 76.32%
- Precision: 70.32%
- Recall: 62.29%
  
Random Forest Model:  
  
- Accuracy: 77.91%
- Precision: 78.54%
- Recall: 55.43%
  
Gradient Boosting Model:  
  
- Accuracy: 75.69%
- Precision: 75.00%
- Recall: 51.43%
  
Conclusion  

The Random Forest model achieved the highest accuracy in detecting fake news, followed closely by Logistic Regression and Naive Bayes models.
