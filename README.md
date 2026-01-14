# __BERT Sentiment Analysis__

This is a Python project that uses Bidirectional Encoder Representations from Transformers (BERT) to classify text into sentiments (positive and negative).

* Dataset used: sentiment140 [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
* Documentation used: [sentiment analysis using BERT](https://www.kaggle.com/code/prakharrathi25/sentiment-analysis-using-bert/notebook#Data-Preprocessing)

- ___I filtered the sentiment140 dataset to only include 10,000 rows with equal amounts of positive (4) and negative (0) text___

#### ___If you are using the same dataset (or any large dataset), it is recommended to run it in Google Colab or using a powerful GPU___

- I trained the model on my MacBook Air M1 and it took nearly `8` hours to finish

### Purpose

This project uses BERT, which is a pre-trained model by Google. I fine-tuned it for sentiment analysis. The model identifies whether a sentence is positive or negative. 

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/NKLoffi/bert_sentiment_analysis.git
   ```


2. Create a virtual environment and install dependencies:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```



### License

This project is licensed under the [MIT License](LICENSE).
