The system uses natural language processing techniques to analyze email content and determine if it is spam or legitimate.
# Gmail Spam Detection using Linear Regression

This repository contains a machine learning-based Gmail spam detection system that utilizes linear regression. The system analyzes the content of emails and predicts whether they are spam or legitimate.

## Features
-Uses NLP libraries in developing the model.
- Utilizes linear regression algorithm for classification
- Achieves an accuracy of 87% in detecting spam emails
- Preprocesses email text data for effective feature extraction
- Performs feature engineering to extract relevant information from emails
- Uses sci-kit-learn library for model training and evaluation

## Dataset
The spam detection model is trained on a labeled dataset of emails, consisting of both spam and non-spam examples. The dataset is not provided in this repository due to size limitations, but you can use your own labeled dataset or explore public email spam datasets for experimentation.

## Usage
1. Clone the repository and navigate to the project directory.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Preprocess your email data and ensure it is in a compatible format.
4. Train the linear regression model by running `python train.py`.
5. Evaluate the trained model on your test data using `python evaluate.py`.
6. Use the trained model to predict spam or non-spam for new emails.

## Contributions
Contributions to this Gmail spam detection system are welcome! If you have suggestions, bug reports, or would like to add enhancements, please feel free to open an issue or submit a pull request.

## Acknowledgements
Would like to acknowledge the contributions of various open-source libraries and the research community for their valuable work in the field of email spam detection.


