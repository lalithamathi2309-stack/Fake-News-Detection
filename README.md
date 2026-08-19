Fake-News-Detection

Fake News Detection using Machine Learning and Python

Project Description
This project detects whether a news article is REAL or FAKE using ML algorithms. 
Built during my AI Internship at Approtech R&D Solutions Pvt. Ltd.

Dataset
Source: Kaggle - Fake and Real News Dataset
Files: True.csv and Fake.csv
Download Link: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset
Description: 
  True.csv - Contains 21417 real news articles
  Fake.csv - Contains 23481 fake news articles
  Columns: title, text, subject, date

Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib, Seaborn

How to Run
1. Clone this repository
2. Install requirements: pip install -r Requirements.txt
3. Download dataset from Kaggle link and place in project folder
4. Open FAKE NEWS DETECTION.ipynb in Jupyter Notebook
5. Run all cells

Key Notes
- Data Cleaning: Removed duplicates, handled missing values
- Text Preprocessing: Lowercase, stopword removal, stemming
- Model Used: Logistic Regression / Naive Bayes
- Accuracy: TBD
- Visualizations: Confusion Matrix, WordCloud
