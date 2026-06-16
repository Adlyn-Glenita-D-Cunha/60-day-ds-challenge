# Project 1: Sentiment Analyser

Classifies movie reviews as positive or negative using NLP.

## Dataset
IMDB 50K Movie Reviews (Kaggle)

## Approach
- Text cleaning (HTML removal, lowercasing)
- TF-IDF vectorization
- Logistic Regression baseline

## Results
| Model | Accuracy |
|---|---|
| Logistic Regression + TF-IDF | ~89% |

## Next Steps
- Fine-tune DistilBERT for higher accuracy
- Deploy as Streamlit app