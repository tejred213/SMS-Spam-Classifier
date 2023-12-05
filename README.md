<h1 align='center'> SMS-Spam-Classifier </h1>

![Python Version](https://img.shields.io/badge/Python-3.x-blue)
![Contributions welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

This is a repository containing code for an SMS spam classifier built using the Multinomial Naive Bayes algorithm and NLTK (Natural Language Processing Toolkit). The classifier is implemented using supervised learning techniques and can effectively classify SMS messages as either spam or non-spam.

## Requirements
- Python 3.6 or higher
- NLTK
- Scikit-learn
- Streamlit

## Installation
Clone the repository:
```shell
git clone https://github.com/tejred213/SMS-Spam-Classifier.git
```

Install the required dependencies:
```shell
pip install -r requirements.txt
```
## Usage
Make sure you have the NLTK stopwords corpus downloaded. If not, open a Python shell and run the following commands:
```shell
import nltk
nltk.download('stopwords')
```

To start the Streamlit app:
```shell
streamlit run app.py
```
## Screenshot
