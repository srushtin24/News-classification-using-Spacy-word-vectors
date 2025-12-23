# News Classification using Spacy Word Vectors

📌 Overview<br>
This project implements a news classification system that classifies news articles as Fake or Real using SpaCy word vectors and traditional machine learning models.<br><br>

🚀 Project Highlights<br>
- Utilized SpaCy en_core_web_lg word vectors to generate semantic document embeddings
- Built an end-to-end NLP pipeline from raw text to predictions
- Implemented and compared multiple ML models:
    - Multinomial Naive Bayes
    - K-Nearest Neighbors (KNN)
- Achieved up to 98% accuracy using KNN on vectorized text<br><br>

📊 Model Performance<br>
🔹 Multinomial Naive Bayes
Accuracy: ~95%<br>
Strong and consistent performance on both classes<br>

<p align="center">
   <img src="/mnb.png" width="400">  
</p>


🔹 K-Nearest Neighbors (Best Model)
Accuracy: ~98%<br>
Excellent precision and recall for both Fake and Real news<br>
Demonstrates effectiveness of dense word embeddings<br>

<p align="center">
   <img src="/knn.png" width="400">  
</p>
