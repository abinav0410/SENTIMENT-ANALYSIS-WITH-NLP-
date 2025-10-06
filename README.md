# SENTIMENT-ANALAYSIS-WITH-NLP
COMPANY: CODTECH IT SOLUTIONS NAME: ABINAV G INTERN ID: CT06DY2764 DOMAIN: MACHINE LEARNING DURATION: 6 WEEKS MENTOR : NEELA SANTOSH

# SENTIMENT-ANALAYSIS-WITH-NLP- Task Description 

In this project, we perform sentiment analysis on a dataset containing customer reviews and their associated sentiment labels.
The workflow includes the following key steps:

# Data Loading and Exploration

Load a dataset of customer reviews stored in a CSV file (customer_reviews.csv).

Each record contains a review (text) and its sentiment label (label → 1 for positive, 0 for negative).

Examine dataset size, missing values, and label distribution.

# Text Preprocessing

Clean the text data by converting it to lowercase, removing punctuation, numbers, and extra spaces.

Remove common stop words that do not contribute to sentiment meaning (like “the”, “and”, “is”).

Optionally, perform lemmatization or stemming to reduce words to their root forms.

# Feature Extraction using TF-IDF

Apply TF-IDF (Term Frequency–Inverse Document Frequency) vectorization to convert text into numerical feature vectors.

This technique gives higher weight to unique and important words in each review.

Model Building with Logistic Regression

Split the dataset into training (80%) and testing (20%) subsets.

Train a Logistic Regression classifier on the TF-IDF features to learn sentiment patterns.

# Model Evaluation

Predict sentiments for the test set.

Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

Display the classification report and confusion matrix for deeper insight.

# Result Interpretation

Analyze which words contribute most to positive and negative classifications.

Draw conclusions about model effectiveness and potential improvements.

 # Tools & Technologies Used:

Language: Python

Environment: Jupyter Notebook / Google Colab

Libraries:

pandas, numpy → data handling

scikit-learn → TF-IDF, Logistic Regression, metrics

nltk → text cleaning and stopword removal

matplotlib / seaborn → visualization

# Expected Outcome:

A trained Logistic Regression model capable of classifying customer reviews as positive or negative.

An accuracy score of around 80–90% for small datasets (higher for large real datasets).

Visualizations showing the distribution of sentiments and model performance.

# Applications:

Analyzing product or service reviews on e-commerce websites.

Monitoring brand sentiment on social media.

# Output 
<img width="1070" height="670" alt="Image" src="https://github.com/user-attachments/assets/afb671ed-54aa-496d-ba5b-5ac826647b19" />

<img width="643" height="386" alt="Image" src="https://github.com/user-attachments/assets/96bd87b7-b99a-4211-9b38-ea359d7642da" />

<img width="706" height="686" alt="Image" src="https://github.com/user-attachments/assets/e0af3bcf-6387-4d6b-86e1-52edb3102b57" />

Automating feedback analysis for businesses.
