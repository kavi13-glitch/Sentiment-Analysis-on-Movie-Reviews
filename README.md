# Sentiment-Analysis-on-Movie-Reviewsews

This project focuses on **analyzing and classifying movie review sentiments** into positive or negative categories using machine learning techniques.

### What I Did:
- Used the **NLTK movie_reviews dataset** containing real-world positive and negative movie reviews.
- Built a **text classification pipeline** using:
    - `CountVectorizer` for transforming text data into numerical features.
    - `Multinomial Naive Bayes classifier` for training and predicting sentiments.
- Split data into train and test sets to evaluate model performance.
- Tested the model on custom movie reviews to demonstrate real-time predictions.

---

###  Key Results:
- Achieved **~80-85% accuracy** on unseen test data.
- Generated a detailed classification report for performance analysis.
- Successfully predicted the sentiment of sample custom reviews:
    - Example:  
      - `"This movie was fantastic! The acting and story were brilliant." → Positive`  
      - `"Terrible movie. Waste of time. Bad acting." → Negative`

---

### Tools & Technologies:
- Python  
- NLTK  
- scikit-learn (CountVectorizer, MultinomialNB, Pipeline)  
- Google Colab (for easy execution)
