# Email Spam Detection — NLP Project

A Natural Language Processing (NLP) project to classify emails as spam or not spam using a Naive Bayes classifier.

## Model Performance
- **Algorithm:** Naive Bayes Classifier
- **Dataset Size:** 5,728 email records

## Project Structure

```
Email-Spam-Detection/
├── main.ipynb            # Main Jupyter Notebook
├── requirements.txt      # Required packages
├── dataset/
│   └── emails.csv        # Email dataset
├── models/
│   ├── model.pkl         # Trained Naive Bayes model
│   └── vectorizer.pkl    # Fitted TF-IDF vectorizer
└── Images/
    └── Email_Spam_Detection_Cover.png
```

## Libraries Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- NLTK

## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Smarajit03/spam_detection.git
   ```
2. Install dependencies
   ```sh
   pip install -r requirements.txt
   ```
3. Open `main.ipynb` in Jupyter or Google Colab

## Workflow

### 1. Data Loading & Visualization
- Loaded dataset of 5,728 emails with binary spam labels
- Visualized class distribution and key features

### 2. Data Preprocessing (NLP Pipeline)
- Removed stopwords using NLTK
- Removed duplicates and cleaned raw email text
- Applied **TF-IDF Vectorization** to convert text to numerical features
- Split data into training and testing sets

### 3. Model Training
- Trained a **Naive Bayes classifier** (well-suited for text classification)
- Model and vectorizer serialized using `pickle` for reuse

### 4. Model Evaluation
- Evaluated using accuracy score, classification report, and confusion matrix

## Dataset

- 5,728 email samples
- Target column: `spam` (1 = spam, 0 = not spam)

## Connect

**Smarajit** — [GitHub](https://github.com/Smarajit03)
