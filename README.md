🚨 Hate Speech Detection on Twitter Tweets
This project is a machine learning model that detects whether a tweet is Hate Speech, Offensive Language, or Neutral based on its content.

📌 Features
Cleaned and preprocessed tweets from a CSV file.

Used TF-IDF vectorization to convert text to numerical form.

Trained models like:

Multinomial Naive Bayes

Decision Tree

Random Forest

Logistic Regression

Evaluated models using accuracy, precision, recall, F1-score, and confusion matrix.

Deployed a function to classify new tweet input from users.

🧰 Technologies Used
Python

Pandas, NumPy

scikit-learn

NLTK

Seaborn, Matplotlib

📁 Dataset
The dataset twitter_data.csv must contain at least:

tweet: The tweet text.

class: Labels (0 = Hate Speech, 1 = Offensive, 2 = Neutral).

🧠 Model Workflow
Text Cleaning:

Lowercased text

Removed URLs, mentions, hashtags, digits, punctuation

Removed stopwords using NLTK

Feature Extraction:

Applied TF-IDF Vectorization (TfidfVectorizer(max_features=5000))

Model Training & Evaluation:

Trained models and evaluated them using accuracy, precision, recall, F1-score

Best performing model: Logistic Regression / Random Forest

Prediction on New Tweets:

A function takes user input and predicts the category.

📊 Visualization
Model comparison using bar chart.

Confusion matrix for individual model.

Class distribution using bar plot.

📌 Notes
Make sure you use the same TF-IDF Vectorizer during prediction as during training.

You can optionally save the model using joblib or keep it in memory during live sessions.

📧 Contact
For any questions or suggestions, reach out to:

Krish Bajaj - bajajkrish2352004@gmail.com
