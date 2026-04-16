#  Sentiment Analysis of Claude Tweets

## (1) Problem Statement
The problem is to analyze tweets related to Claude and classify them into positive, negative, or neutral sentiments. Understanding public opinion from text data is difficult manually, so we use machine learning to automate this task.

## (2) Objective
- To classify tweets into positive, negative, and neutral categories
- To compare performance of different machine learning models
- To evaluate models using precision and recall

## (3) Dataset
- Source: Tweets collected manually related to Claude
- Features: Tweet text, Sentiment label (positive/negative/neutral)
- Size: 100 tweets

## (4) Methodology
1. Data Preprocessing
   - Removed missing values  
   - Cleaned text data
      
2. EDA
    - Checked distribution of sentiments  
   - Observed sample tweets
     
3. Model Building
    - Converted text into numbers using TF-IDF  
    - Applied models:
     - Naive Bayes  
     - Logistic Regression  
     - SVM
       
6. Evaluation
   - Used precision, recall, and F1-score  
   - Compared performance of all models 

## (5) Results
- Naive Bayes gave moderate performance  
- Logistic Regression gave balanced results  
- SVM performed best with highest accuracy  
- Overall, machine learning models successfully classified tweet sentiments  

## (6) How to Run
1. Open the .ipynb notebook file in Google Colab
2. Upload the dataset file (CSV/Excel) using the left-side file panel
3. Run all the cells step by step (Runtime → Run all)
4. View the output results including model performance and evaluation metrics

## (7) Conclusion
This project shows that sentiment analysis can be effectively performed using machine learning. Among all models, SVM achieved the best performance. The system can help in understanding public opinion from social media data.

## (8) Student's details
- Name: Tahiya Raza
- Roll No: 46
- UIN:231A042
- YEAR: TE-AIDS
