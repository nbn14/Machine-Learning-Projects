Implementation of Sentiment Analysis using IMDB database on movie reviews and rating 
### Problem statement
- The analysis aims to predict whether a reviewer is more likely to give a movie a good rating (>= 6 stars) or a bad one (<= 5 stars) based on the content of the review
- The project uses imdb dataset available @ ai.standford.edu/~amaas/data/sentiment
- The project looks at:
    - 50,000 reviews 
    - Compare the classification of good (positive) / bad (negative) review using various ML techniques (Logistic Regression, PassiveAggressive Classifier, Perceptron, SGDClassifier)
    - Implement out-of-core learning to reduce run time 
### Acknowledgement:
- Resources from: Python Machine Learning by Sebastian Raschka
- https://scikit-learn.org/stable/auto_examples/applications/plot_out_of_core_classification.html#sphx-glr-auto-examples-applications-plot-out-of-core-classification-py
- https://www.pluralsight.com/guides/building-a-twitter-sentiment-analysis-in-python
