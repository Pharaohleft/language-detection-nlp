# Language Detection NLP Project

This project detects the language of a given text using a Naive Bayes classifier and basic NLP preprocessing.

## How It Works
- Load dataset (\Language Detection.csv\)
- Clean and preprocess text (remove special characters, lowercase)
- Convert text to numeric using Bag of Words (CountVectorizer)
- Train a Naive Bayes classifier
- Evaluate with accuracy and confusion matrix
- Predict the language of new text samples

## Technologies Used
- Python (pandas, numpy, scikit-learn)
- NLP: Bag of Words (CountVectorizer)
- Naive Bayes classifier
- Data visualization: seaborn and matplotlib

## Usage
1. Install required libraries:
\\\
pip install pandas numpy scikit-learn seaborn matplotlib
\\\

2. Run the script:
\\\
python language_detection.py
\\\

3. To predict a new text, use:
\\\
predict(\
Your
text
here\)
\\\

## Learning Outcomes
- Understanding text preprocessing
- Converting text to numeric representations (BoW)
- Building classification models with scikit-learn
- Visualizing model performance

---

*Developed as a foundational NLP project using real-world language datasets.*
