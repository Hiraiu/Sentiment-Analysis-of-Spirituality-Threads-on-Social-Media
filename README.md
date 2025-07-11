# Sentiment-Analysis-of-Spirituality-Threads-on-Social-Media
University project.

This university project performs end-to-end sentiment analysis on social media posts related to spirituality. It includes data cleaning and preprocessing, exploratory data analysis, and sentiment scoring using both the lexicon-based VADER tool and the transformer-based RoBERTa model from Hugging Face. The solution handles challenges such as noisy text and long posts by chunking inputs and averaging results. Technologies used include Python, pandas, NLTK, PyTorch, Transformers, Matplotlib, and Seaborn.

---

## Features
- Data cleaning and preprocessing of noisy social media text  
- Exploratory data analysis and visualization of keywords and comment distributions  
- Sentiment analysis using VADER and RoBERTa transformer models  
- Handling of long texts by chunking and averaging model predictions  
- GPU support for accelerated transformer inference  
- Saving combined sentiment scores for further analysis  

## Installation
1. Clone the repository:  
   git clone https://github.com/yourusername/Sentiment-Analysis-of-Spirituality-Threads-on-Social-Media.git
   cd Sentiment-Analysis-of-Spirituality-Threads-on-Social-Media

2. (Optional) Create and activate a virtual environment:
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install required packages
    pip install -r requirements.txt


## Dependencies
    - Python 3.8+
    - pandas
    - numpy
    - nltk
    - torch
    - transformers
    - matplotlib
    - seaborn
    - tqdm
    - gdown