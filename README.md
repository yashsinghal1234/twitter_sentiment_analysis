# 🐦 Twitter Sentiment Analysis using Machine Learning

This project focuses on analyzing the sentiment of tweets using machine learning and Natural Language Processing (NLP). The notebook guides you through the full pipeline — from preprocessing raw text to building and evaluating a sentiment classification model.

## 📌 Overview
**Goal**: Classify tweets into categories such as positive, negative, or neutral.

### Techniques used:
- Text preprocessing (cleaning, tokenization, stopword removal)
- Feature extraction using TF-IDF
- Model training using traditional ML algorithms
- Evaluation using accuracy, confusion matrix, etc.

## 🎯 Project Results
- **Training Accuracy**: 99.90%
- **Validation Accuracy**: 95.58%
- **Model**: Random Forest Classifier
- **Dataset Size**: ~74K training samples

## 🎓 For Students and Learners
**Important Note**: This is a **sentiment analysis project**, not a metro/transportation project. If you're a student looking for metro-related projects, you may have the wrong repository.

For students interested in learning about this project, please see our comprehensive [Student Guide](STUDENT_GUIDE.md) which includes:
- Detailed development process
- Learning resources and tutorials
- Step-by-step implementation guide
- Project ideas and variations
- Academic use guidelines

## 📁 Files

| File | Description |
|------|-------------|
| `twitter_sentiment.ipynb` | Jupyter Notebook containing all preprocessing, modeling, and evaluation steps |
| `train_tweet.csv` | Training dataset with labeled tweets |
| `test_tweets.csv` | Test dataset for model evaluation |
| `STUDENT_GUIDE.md` | Comprehensive guide for students and learners |

## ⚙️ Tech Stack
**Language**: Python

**Libraries**:
- pandas, numpy
- scikit-learn
- nltk
- matplotlib / seaborn (optional for visualization)

## 🚀 How to Run

1. **Install required packages**:
   ```bash
   pip install pandas numpy scikit-learn nltk matplotlib seaborn
   ```

2. **Download NLTK data**:
   ```python
   import nltk
   nltk.download('stopwords')
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

4. **Open `twitter_sentiment.ipynb`** and run the cells in sequence.

## 🔎 What's Inside
- **Step 1**: Data Loading
- **Step 2**: Cleaning Tweets (removing links, mentions, hashtags, special chars)
- **Step 3**: Tokenization & Stopword Removal
- **Step 4**: Vectorization using TF-IDF
- **Step 5**: Sentiment Classification (Random Forest)
- **Step 6**: Model Evaluation

## 📈 Model Evaluation
Performance metrics include:
- **Accuracy**: 95.58% (Validation)
- **Precision / Recall / F1 Score**
- **Confusion Matrix**

## 🤝 Contributing
Students and developers are welcome to contribute! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request with your improvements

## 📞 Contact
For questions about this sentiment analysis project or machine learning in general, please open an issue or contact through GitHub.

---
**Note for Students**: If you received this link expecting a metro/transportation project, there may be some confusion. This repository focuses on Twitter sentiment analysis using machine learning. Please refer to the [Student Guide](STUDENT_GUIDE.md) for detailed information about this project.