 Sentiment Analysis on Twitter Data

 Overview

This project focuses on performing sentiment analysis on Twitter data using classical machine learning techniques. The goal is to classify tweets based on their sentiment (positive, negative, or neutral) using a labeled dataset. The analysis includes data preprocessing, feature extraction, model training, and evaluation.

Project Structure

```
CSC-637--SentimentAnalysis-Twitter/
├── data/
│   └── twitter_training.csv              # Dataset used for training and evaluation
├── notebook/
│   └── sentiment_analysis.ipynb          # Jupyter Notebook containing the entire workflow
```

 Features

- Text preprocessing (cleaning, tokenization)
- Feature extraction using TF-IDF
- Sentiment classification using machine learning models
- Evaluation using metrics such as accuracy and F1-score
- Visualizations for data distribution and model performance

 Technologies Used

- Python 3.x
- Jupyter Notebook
- pandas
- scikit-learn
- matplotlib / seaborn (for optional visualizations)

 How to Run the Project

1. Clone the repository:

  
   git clone https://github.com/rahulnani04/CSC-637--SentimentAnalysis-Twitter.git
   

2. Navigate to the project directory:

 
   cd CSC-637--SentimentAnalysis-Twitter
   ```

3.Launch Jupyter Notebook:


4.Open the notebook:

   Navigate to `notebook/sentiment_analysis.ipynb` and run the cells step by step.

 Dataset

The dataset (`twitter_training.csv`) contains tweets with corresponding sentiment labels. It has been pre-labeled and used for training supervised machine learning models. The dataset resides in the `data/` directory.

 Output

The notebook outputs:
- Preprocessing steps
- Model training accuracy and F1-score
- Confusion matrix
- Key observations and discussion

## Author

Rahul Velpula  
[GitHub Profile](https://github.com/rahulnani04)


