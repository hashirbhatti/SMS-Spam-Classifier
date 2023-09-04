
# SMS Spam Classifier

SMS Spam Classifier is a machine learning project that predicts whether a given text message is spam or not. It utilizes text preprocessing techniques like stemming and TF-IDF vectorization, along with the Multinomial Naive Bayes algorithm to achieve an impressive accuracy of 97% and a precision score of 100% on the test dataset. Additionally, it includes a simple user interface built with Streamlit for easy interaction.



## Installation

To get started with the SMS Spam Classifier project, you need to follow these installation steps:

1. Clone this repository to your local machine using the following command:
```bash
  git clone https://github.com/hashirbhatti/SMS-Spam-Classifier.git

```

2. Navigate to the project directory:
```
  cd SMS-Spam-Classifier
```

3. Create a virtual environment (optional but recommended):
```
  python -m venv venv
```

4. Activate the virtual environment:
**On Windows:**
```
  venv\Scripts\activate
```
**On macOS and Linux:**
```
  source venv/bin/activate
```

5. Install the required Python packages:
```
  pip install -r requirements.txt
```
## Usage

To use the SMS Spam Classifier, follow these steps:

1. Make sure you have completed the installation steps mentioned above.

2. Run the Streamlit app:
```
  streamlit run app.py
```
3. The app will open in your default web browser. You can input a text message, and the classifier will predict whether it's spam or ham.


## Dataset

The dataset used for training and testing the SMS Spam Classifier is available at [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset). You can find more information about the dataset and its source on the linked page.
## Preprocessing

The preprocessing steps involve text cleaning, stemming, and TF-IDF vectorization. These techniques help prepare the text data for machine learning algorithms by converting it into a numerical format that can be used for training and prediction.
## Model Training

The SMS Spam Classifier uses the Multinomial Naive Bayes algorithm for text classification. It has been trained on a labeled dataset to learn the patterns and characteristics of spam and non-spam (ham) messages.
## Evaluation

The model's performance has been evaluated using various metrics, including accuracy and precision. The classifier achieves an accuracy of 97% and a precision score of 100% on the test dataset, demonstrating its effectiveness in identifying spam messages.
## Interface App

A user-friendly interface has been built using Streamlit, allowing users to interact with the SMS Spam Classifier easily. You can input text messages and receive instant predictions on whether they are spam or ham.


## Demo

Insert gif or link to demo

