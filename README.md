# Twitter_Sentiment_Analysis
Twitter Sentiment Analysis on Russia Ukraine war

Objective

The project aims to analyze public opinion on the Russia-Ukraine war by classifying tweets into two categories: Support for Ukraine and Support for Russia, and further evaluating the sentiment (positive, negative, neutral) expressed in them.

Dataset

Tweets were collected using the Python snscrape library by scraping Twitter for war-related keywords.

Tweets were cleaned using NLTK and RegEx (removing URLs, mentions, stop words, and punctuation).

Only meaningful tweets (more than 100 characters) were retained for analysis.

Methodology & Technologies Used

Libraries: Python, Pandas, NLTK, scikit-learn.

Preprocessing: Data cleansing, tokenization, stopword removal, and bigram extraction.

Sentiment Analysis: VADER sentiment analyzer from NLTK.

Classification: Logistic Regression, KNN, Decision Tree, Random Forest, and SVM were evaluated.

Labelling: Tweets matched against predefined war-related bigram patterns and categorized as “Support for Russia” or “Support for Ukraine.”

Model Training: Train-test split (70–30) applied.

Results

Logistic Regression achieved the highest performance among all tested models.

Accuracy: ~95%

Evaluations included confusion matrices, precision, recall, and F1 scores.
