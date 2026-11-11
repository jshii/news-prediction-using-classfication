
# News Category Classifier 📰
## Project Overview
News Category Classifier is a Machine Learning project that automatically classifies news articles into five different categories using Natural Language Processing (NLP).

The model uses **Logistic Regression** with **TF-IDF Vectorization** to analyze text and predict its category.

## Categories
The model classifies news articles into the following categories:

- Business
- Entertainment
- Politics
- Sport
- Tech

## Technologies & Libraries
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Matplotlib

## Dataset
The dataset contains news-related text and category labels, along with additional features such as readability scores and text summaries.

The main columns used in this project are:
- `text`: News article content.
- `labels`: News category.

## Project Workflow

1. Data loading and exploration.
2. Data cleaning and preprocessing.
3. Splitting data into training and testing sets.
4. Converting text into numerical features using TF-IDF.
5. Training a Logistic Regression model.
6. Evaluating model performance.
7. Testing predictions on new text samples.

## Model Performance

The model achieved approximately **98.8% accuracy** on the test dataset.

### Classification Report

| Category | Precision | Recall | F1-Score |
|---|---:|---:|---:|
| Business | 1.00 | 0.97 | 0.98 |
| Entertainment | 0.99 | 1.00 | 0.99 |
| Politics | 0.99 | 0.99 | 0.99 |
| Sport | 1.00 | 1.00 | 1.00 |
| Tech | 0.96 | 0.99 | 0.97 |

## How to Run

Clone this repository:

```bash
git clone YOUR-REPOSITORY-LINK
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the Jupyter Notebook and run the cells.

## Future Improvements

- Experiment with other Machine Learning algorithms.
- Improve text preprocessing.
- Test the model on more unseen news articles.
- Explore advanced NLP techniques.

## Author

Created as a practical Machine Learning project to explore text classification and Natural Language Processing.

