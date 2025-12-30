# E-Commerce Product Review Analysis Capstone Project

[![Python](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Gradio App](https://img.shields.io/badge/Gradio-App-red.svg)](https://gradio.app/)

## Overview
This is the final capstone project for AI/ML course, focusing on analyzing Amazon product reviews. The project includes:
- Data preprocessing and EDA
- Feature engineering
- ML models for sentiment classification (Logistic Regression, Decision Tree, Random Forest)
- Regression models for rating prediction (Linear, Lasso, Ridge)
- Deep learning models (LSTM for sentiment, GRU for ratings)
- NLP-based review summarization (Extractive, Abstractive, Hybrid)
- Interactive Gradio web app for review summarization

Date: December 30, 2025  
Author: Edward Yen  

## Features
- **Data Analysis**: Cleaned dataset with 1,465 reviews, visualizations for ratings, categories, etc.
- **Sentiment Analysis**: VADER and TextBlob for scores; classification accuracy up to 85%+.
- **Rating Prediction**: RMSE as low as 0.25 with tuned models.
- **Summarization**: TF-IDF extractive, template-based abstractive, and hybrid methods.
- **Deployment**: Gradio app for real-time review summarization.


##Installation
1. Clone the repository:
git clone https://github.com/EdwardPYen/ecommerce-review-analysis-capstone.git
cd ecommerce-review-analysis-capstone

2. Install Dependencies:
jupyter notebook "AI&ML Capstone 2 Final.ipynb"

3. Run the Jupyter Notebook:
jupyter notebook "AI&ML Capstone 2 Final.ipynb"

4. Launch the Gradio App:
python gradio_app.py
textAccess at http://localhost:7860

## Usage
### Running the Notebook
- Load your dataset (e.g., `amazon_reviews.csv` in `/data`).
- Execute cells sequentially for preprocessing, modeling, and evaluation.
- Models are saved in `/models`; figures in `/figures`.

### Gradio App
- Input multiple reviews separated by `|`.
- Choose method: Extractive, Abstractive, or Hybrid.
- Adjust sentences for extractive summary.
- Get instant Markdown-formatted summary with sentiment insights.

Example Input:  
`Good product, fast charging | Sturdy cable, great value | Slow sometimes but decent`

## Project Structure
- `AI&ML Capstone 2 Final.ipynb`: Main notebook with all code.
- `gradio_app.py`: Standalone script for the summarization app.
- `data/`: Store datasets here.
- `models/`: Saved ML/DL models.
- `figures/`: EDA visualizations.

## Dependencies
See `requirements.txt` for full list. Key libraries:
- pandas, numpy, matplotlib, seaborn
- scikit-learn, tensorflow, keras
- nltk, vaderSentiment, gradio

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Built as part of AI/ML Capstone 2.
- Uses Amazon product review dataset (not included; add your own).

For issues, open a GitHub Issue or contact edwardpyen9@gmail.com
