# NLP Model: Sentiment Classification

A Jupyter notebook that compares text classifiers for sentiment analysis, using NLTK's Twitter sample corpus.

## What is inside

- Cleaning and tokenizing text (stop words, stemming, lemmatization, part-of-speech tags)
- Bag-of-words and TF-IDF features
- Naive Bayes, logistic regression, SGD and SVM classifiers, plus a voting ensemble
- VADER sentiment scoring for comparison
- Confusion matrices, normalized and not

## Run

```bash
pip install nltk scikit-learn matplotlib beautifulsoup4 googletrans==4.0.0rc1 jupyter
jupyter notebook NLP_Model.ipynb
```

The notebook downloads the NLTK corpora it needs.
