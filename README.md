# Email Spam Detector using Machine Learning

Welcome to the Email Spam Detector project! This project leverages Python and machine learning to create an effective email spam detection system. With the increasing prevalence of spam and phishing emails, this project aims to classify emails into spam and non-spam categories automatically.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Steps](#project-steps)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

In this project, we use the SMS Spam Collection Dataset to train a machine learning model that can distinguish between spam and non-spam (ham) emails. The steps involved include data exploration, preprocessing, vectorization, model training, evaluation, and prediction.

## Dataset

The dataset used in this project is the SMS Spam Collection Dataset, which can be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection).

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/namanbhansali59/email-spam-detector.git
   cd email-spam-detector
   ```

2. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Download the dataset and place it in the project directory.
2. Run the `spam_detector.py` script:

   ```bash
   python spam_detector.py
   ```

## Project Steps

1. **Import Necessary Libraries:** Import all required libraries for data manipulation, visualization, and machine learning.
2. **Load and Explore the Dataset:** Load the dataset and perform an initial exploration to understand its structure and contents.
3. **Data Preprocessing:** Encode the target variable and split the dataset into training and test sets.
4. **Vectorize the Text Data:** Convert text data into numerical data using `CountVectorizer`.
5. **Train a Machine Learning Model:** Use the Multinomial Naive Bayes algorithm to train the model on the processed data.
6. **Evaluate the Model:** Evaluate the model’s performance using metrics such as accuracy, classification report, and confusion matrix.
7. **Make Predictions:** Use the trained model to predict whether new email samples are spam or ham.


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any improvements or suggestions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

This project was developed as part of a machine learning task given by Oasis Infobyte. Special thanks to Oasis Infobyte for providing the opportunity to work on this interesting project.
