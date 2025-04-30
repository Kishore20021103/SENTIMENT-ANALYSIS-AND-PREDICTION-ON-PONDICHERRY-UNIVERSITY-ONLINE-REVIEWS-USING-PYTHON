# SENTIMENT-ANALYSIS-AND-PREDICTION-ON-PONDICHERRY-UNIVERSITY-ONLINE-REVIEWS-USING-PYTHON
## Description

This project leverages Natural Language Processing (NLP) and machine learning techniques to analyze and predict sentiment in online reviews related to Pondicherry University. The goal is to automatically determine whether feedback from students is positive, negative, or neutral, providing actionable insights for institutional improvement.

## Objective

The main objectives of this project are:

 * To perform sentiment analysis on online reviews related to Pondicherry University using Python.
 *	To categorize sentiments as positive, negative, or neutral regarding key aspects such as infrastructure, faculty, campus life, and overall satisfaction.
 * To identify recurring themes and concerns in the feedback to support data-driven decision-making for university improvement.
 * Employing predictive modeling using machine learning


## Steps Involved
Steps Involved in Sentiment Analysis and Prediction Project

1. **Data Collection**
   
   * Gather online reviews related to Pondicherry University from sources such as university websites, social media platforms, or review portals.

   * Store the collected data in a structured format (e.g., CSV, JSON) with relevant fields like review text, date, and rating if available.

3. **Data Preprocessing**
   
   * Cleaning: Remove unwanted characters, HTML tags, punctuation, and special symbols.

   * Normalization: Convert text to lowercase to maintain consistency.

   * Tokenization: Split text into individual words or tokens.

   * Stopword Removal: Eliminate common words (e.g., “is”, “the”) that do not contribute to sentiment.

   * Stemming/Lemmatization: Reduce words to their root form to unify variations (e.g., “running” → “run”).

4. **Exploratory Data Analysis (EDA)**
   
   * Analyze the distribution of review lengths, ratings, and sentiment classes.

   * Visualize common words using word clouds or frequency plots.

   * Identify trends or patterns in the data.

4. **Feature Extraction**
   
   * Convert text data into numerical form using techniques such as:

   * Bag of Words (BoW)

   * Term Frequency-Inverse Document Frequency (TF-IDF)

   * Word Embeddings (e.g., Word2Vec, GloVe)

   * These features enable machine learning algorithms to process textual data.

5. **Model Building**
   
   * Select suitable machine learning algorithms such as Logistic Regression, Support Vector Machines, Random Forest, or deep learning models like LSTM.

   * Split the dataset into training and testing sets.

   * Train the model on the training data using the extracted features.

   * Tune hyperparameters to optimize performance.

6. **Model Evaluation**
   
   * Evaluate the model using metrics like accuracy, precision, recall, F1-score, and confusion matrix.

   * Perform cross-validation to ensure robustness.

   * Analyze misclassified examples to understand model limitations.

7. **Sentiment Prediction**
   
   * Use the trained model to predict sentiment labels (positive, negative, neutral) on new or unseen reviews.

   * Provide an interface or script for users to input reviews and receive instant sentiment predictions.

8. **Visualization and Reporting**
   
   * Visualize sentiment distribution and trends over time.

   * Generate reports summarizing key insights from the sentiment analysis.

   * Use charts such as bar graphs, pie charts, and word clouds to communicate findings effectively.
     
  **POSITIVE WORD CLOUD**
  ![image](https://github.com/user-attachments/assets/d57421d4-1ed0-4458-be99-f19b657a532b)

  **NEGATIVE WORD CLOUD**
 ![image](https://github.com/user-attachments/assets/57f54a9b-9c9a-4880-8d40-14547588df9b)

  **DISTRIBUTION OF SENTIMENT RATING**
 ![image](https://github.com/user-attachments/assets/383db9bd-eab4-433e-bd7b-3d98bb384cf8)

  **FREQUENCY OF POSITIVE WORDS**
  ![image](https://github.com/user-attachments/assets/77c06848-9d4d-4749-9eb0-349954e85323)

  **FREQUENCY OF NEGATIVE WORDS**
  ![image](https://github.com/user-attachments/assets/30afb9e0-49f1-4b3f-b7b1-076de098ea62)



## Findings

**Infrastructure:** Most students view the university’s facilities positively, with over 65% rating it 4 or 5. Negative ratings are minimal, indicating general satisfaction with physical and technological resources.

**Faculty:** Feedback is highly favorable; about 67% of students gave faculty ratings of 4 or 5, reflecting appreciation for teaching quality and support.

**Campus Life:** Campus environment is a strong point, with nearly 70% of students rating it highly, highlighting vibrant social and extracurricular activities.

**Overall Satisfaction:** The majority of students express contentment, with 71% rating their overall experience as 4 or 5.

**Sentiment Categorization:** Using NLP and machine learning, reviews were classified into positive, negative, and neutral sentiments. Positive themes include supportive faculty and good infrastructure, while concerns focus on placements, hostel facilities, and food quality.
