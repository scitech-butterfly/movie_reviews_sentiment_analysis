# movie_reviews_sentiment_analysis

<h3> <b>Introduction:</b></h3>
<p>This project is based on analyzing the sentiment of a set of movie reviews, and training a model to predict the sentiment of such movie reviews. In this, I used a dataset of 50k IMDb reviews obtained from Kaggle. The dataset contains two columns, 'review' and 'sentiment', each review labeled as positive or negative. </p>

<h3> <b>Data Preprocessing:</b></h3>
<p>To clean the data, the function cleanText() converts all text to lowercase, removes punctuation, numbers, and stopwords, and lemmatizes the words to their base form. This step was crucial to ensure that the text data was in a consistent and usable format.</p>

<h3> <b>Feature Engineering:</b></h3>
<p>Next, I used the Term Frequency-Inverse Document Frequency (TF-IDF) method to transform the cleaned text into numerical features. This technique helps in capturing the importance of words in the context of the entire dataset, giving more weight to informative words.</p>

<h3> <b>Model Selection:</b></h3>
<p>I experimented with several models, including Random Forest, Naive Bayes, XGBoost, and Logistic Regression. For each model, I performed hyperparameter tuning using GridSearchCV to find the best set of parameters. This step involved trying different combinations of parameters and selecting the ones that gave the best performance.</p>

<h3> <b>Evaluation:</b></h3>
<p>After testing various models, Logistic Regression performed the best out of all. It achieved an accuracy of 88%, which was the highest among all the models I tried. It also has the best precision, recall, and F1 score, making it the most reliable model for this task.</p>

<h3> <b>Conclusion:</b></h3>
<p>In conclusion, by working on this project, I gained hands-on experience in text preprocessing, feature engineering, model selection, and evaluation. Working through the challenges helped me understand the complexities of sentiment analysis and the importance of thorough testing and validation.</p>
