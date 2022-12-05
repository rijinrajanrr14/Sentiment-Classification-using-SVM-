# Sentiment-Classification-using-SVM-
### Sentiment Classification on COVID-19 Dataset using the Support Vector Model(SVM)

Sentiment Analysis is the NLP technique that performs on the text to determine whether the author’s intentions towards a particular topic, product, etc. are positive, negative, or neutral.For this sentiment analysis experiment we have used covid-19 dataset that contains the tweets and the labels for that specific tweet. The model used int he sentiment prediction is SVM.

### Dataset:
Contains 30000 rows and 2 columns. The columns are 'tweet' and 'label'.
The tweet column consits of three categorical values, neu-for neutral, pos-for positive and neg-for negative.

### Processes
The main processes inthe experiment are:

*Cleaning- removing the undesired characters from the tweet column.(uses the tweet-preprocessing module for removing the emoticions and other undesired characters)

*Splitting the dataset for testing and training

*Vectorizing the tweet column for fitting it in the model

*Finding the accuracy of the model
