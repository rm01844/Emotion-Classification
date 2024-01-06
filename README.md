# Emotion Detection using NLP

## Project Overview
This project aims to detect emotions from text using Natural Language Processing (NLP). It explores various NLP techniques and models to analyze textual data and classify emotions effectively.

## Installation
To set up the project environment, install the required Python packages:
```bash
pip install numpy pandas scikit-learn tensorflow
```

## Dataset and Preprocessing
The project employs a dataset of textual content, with preprocessing steps including stopword removal, stemming, and lemmatization. TfidVectorizer is used for text vectorization.

## Model Architecture and Evaluation
- **Naive Bayes**: Served as the baseline model, with hyperparameter tuning particularly on the alpha value.
- **Logistic Regression**: Demonstrated superior performance with an accuracy of 0.66, outperforming Naive Bayes.

## Results and Insights
- The evaluation highlighted Logistic Regression's effectiveness, yielding a higher accuracy and F1-score than Naive Bayes.
- Text featureization techniques like Bag of Words (BoW), TF-IDF, and Word2Vec were compared, with BoW showing the best performance.

## Usage
Example command to run the emotion detection model:
```python
python run_emotion_detection.py --input "input_text.txt"
```
