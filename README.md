# Transformer-Based E-Commerce Review Analysis-On Going 

> 🚧 **Research Status: Ongoing / Manuscript Under Review**

This repository presents my ongoing research on automated product rating generation and rating-review inconsistency detection using transformer-based natural language processing models.

The research focuses on multilingual and code-mixed e-commerce reviews, particularly Bangla, Banglish, English, and mixed-language customer feedback.

## 🔬 Research Problem

E-commerce platforms commonly use numerical star ratings together with written customer reviews.

However, the star rating does not always reflect the sentiment expressed in the review text.

Examples include:

- High star ratings with strongly negative reviews
- Low star ratings with positive reviews
- Manipulated or biased ratings
- Inconsistent rating behavior
- Multilingual and code-mixed review challenges

This research investigates whether product ratings can be generated from review sentiment and whether inconsistencies between review text and platform ratings can be detected automatically.

## 💡 Proposed Framework

The proposed framework includes:

- Multilingual review collection
- Language detection
- Translation and text normalization
- Five-class sentiment classification
- Transformer-based model training
- Sentiment-driven rating generation
- Comparison with platform ratings
- Product-level inconsistency detection

## 🤖 Models Used

The research evaluates:

- BART
- DeBERTa
- RoBERTa-Base
- RoBERTa-Large
- Logistic Regression
- Support Vector Machine

## 🌐 Language Coverage

The dataset includes:

- English
- Bangla
- Banglish
- Mixed / Code-Mixed Reviews

## 📊 Dataset

The current dataset contains:

**13,620 e-commerce product reviews**

The review data includes:

- Product category
- Review text
- User rating
- Platform product rating
- Language type
- Sentiment label

## 🧠 Sentiment Classes

The research uses a five-class sentiment taxonomy:

1. Very Negative
2. Negative
3. Neutral
4. Positive
5. Very Positive

These sentiment classes are mapped to a 1–5 star rating scale.

## 🏗️ Research Pipeline

Product Reviews
        ↓
Language Detection
        ↓
Translation & Preprocessing
        ↓
Sentiment Annotation
        ↓
Transformer Model Training
        ↓
Sentiment Classification
        ↓
Sentiment-Driven Rating
        ↓
Compare with Platform Rating
        ↓
Consistency Analysis
        ↓
Consistent / Overrated / Underrated

## 📈 Current Results

Among the evaluated models, RoBERTa-Large currently provides the strongest performance.

Current results include:

- Accuracy: 89.02%
- Macro-F1: 0.9025
- Weighted-F1: 0.8930
- MAE: 0.1512
- QWK: 0.9386

Transformer-based approaches outperform the traditional machine-learning baselines in the current experiments.

## 🔍 Rating Inconsistency Detection

The system compares:

**Platform Rating**
vs.
**Sentiment-Driven Predicted Rating**

Products are categorized as:

- ✅ Consistent
- 🔺 Overrated
- 🔻 Underrated

A consistency threshold is used to determine whether the difference between the two ratings is significant.

## 🎯 Research Contributions

The current research focuses on:

- Multilingual e-commerce sentiment analysis
- Bangla and Banglish review processing
- Five-class sentiment classification
- Sentiment-driven product rating generation
- Rating-review inconsistency detection
- Comparison of multiple transformer architectures

## ⚠️ Current Limitations

Current limitations include:

- Mixed-sentiment reviews can be difficult to classify with one label
- Translation quality affects downstream sentiment classification
- Products with very few reviews may produce unreliable aggregate ratings
- Additional regional languages need further study
- Larger-scale validation is still required

## 🔭 Ongoing Work

Future and ongoing work includes:

- Expanding the dataset
- Adding more regional languages
- Improving code-mixed review processing
- Investigating aspect-level sentiment analysis
- Testing efficient LLM-based models
- Improving inconsistency detection
- Evaluating real-time e-commerce deployment

## 🧠 Research Areas

- Natural Language Processing
- Machine Learning
- Deep Learning
- Transformer Models
- Sentiment Analysis
- Multilingual NLP
- E-Commerce Analytics
- Recommendation Systems
- Rating Prediction
- Review Reliability

## 📄 Research Status

🚧 Ongoing Research / Manuscript Under Review

The complete manuscript and full dataset are not publicly released at this stage.

Selected implementation details, figures, experimental summaries, and research updates may be added to this repository as the work progresses.

## 👨‍💻 Researcher

**Pranta Kumar Sarkar**

Research interests include Machine Learning, Deep Learning, Computer Vision, Natural Language Processing, and Artificial Intelligence.
