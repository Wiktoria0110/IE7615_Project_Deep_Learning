# IE7265 - Deep Learning for AI
## Interpretable Sentiment Analysis of Customer Reviews Using Deep Learning

Wiktoria Lasek
IE 7265 - Deep Learning for AI

---

## Project Overview
This project builds a progressive deep learning pipeline for sentiment 
analysis of Amazon customer reviews - comparing Logistic Regression, 
Feedforward Neural Network, LSTM, and DistilBERT - with attention 
visualization for interpretability and cross-domain testing on Yelp reviews.

## Datasets
- Amazon Reviews (train: 200,000, test: 40,000)
  https://www.kaggle.com/datasets/bittlingmayer/amazonreviews
- Yelp Reviews (5,000 - cross-domain test)
  https://www.kaggle.com/datasets/thedevastator/yelp-reviews-sentiment-dataset
  
## Models
1. Logistic Regression (baseline)
2. Feedforward Neural Network
3. LSTM with GloVe embeddings
4. DistilBERT (fine-tuned transformer)

## Repository Structure
- `/proposals` - Project proposals and progress report
- `/code` - Jupyter notebooks
- `/visualizations` - Charts and outputs
- `/report` - Final report and presentation

## Timeline
| Week | Task |
|---|---|
| Week 1 | Data exploration |
| Week 2 | Data preprocessing |
| Week 3 | Baseline models |
| Week 4 | LSTM |
| Week 5 | DistilBERT |
| Week 6 | Cross-domain testing |
| Week 7 | Report and presentation |

## How to Run
1. Clone this repository
2. Install required dependencies (see below)
3. Download datasets from Kaggle (links below)
4. Open `code/IE7615Project.ipynb` in Jupyter or Google Colab
5. Update file paths to your local dataset location
6. Run cells sequentially from top to bottom

## Dependencies
The following libraries are required to run this project:
- **pandas** - data loading and manipulation
- **numpy** - numerical operations
- **matplotlib** - visualizations
- **scikit-learn** - Logistic Regression and TF-IDF
- **nltk** - text preprocessing and stop words
- **torch** - PyTorch for neural network models
- **transformers** - HuggingFace for DistilBERT

To install all dependencies, run:
pip install pandas numpy matplotlib scikit-learn nltk torch transformers

