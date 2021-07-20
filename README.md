# Misinformation Identification Fake news detection

-Performed NLP misinformation identification for the US election (November 8, 2016) and COVID-19 news.
-Employed tokenization and stopwords for data cleaning, used word cloud for data visualization followed by feature engineering via lemmatization and scaled with Tf-IDF.
-Implement four models where logistic regression outperformed SVC, Passive-aggressive classifier and KNneighbours classifier.

About the repository:

The covid-19 dataset is taken from: https://raw.githubusercontent.com/susanli2016/NLP-with-Python/master/data/corona_fake.csv.
Election data is acquired from: https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset.

The Notebook contains a combination of:
- Fake news detection for US election 2016 and
- Fake news or messages detection during COVID-19

The prior implemented fake news detection model (for US election 2016) is further extrapolated to predict the scenarios for fake news detection in the period of the COVID-19 pandemic.
