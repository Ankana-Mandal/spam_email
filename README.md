# **Spam Email Classification**

This project uses machine learning techniques to classify emails as either "spam" or "ham" (non-spam). The model is trained using a dataset of labeled emails and applies the **Logistic Regression** algorithm, with **TF-IDF** vectorization for feature extraction from the text.

## **Table of Contents**
- [Overview](#overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## **Overview**
This spam classification model is built using Python and leverages various libraries such as **scikit-learn**, **pandas**, and **numpy** for data manipulation and machine learning tasks. The goal is to preprocess email text data, train a classifier, and evaluate its performance on a test dataset. The model predicts whether an email is "spam" or "ham."

### **Key Components**:
- **TfidfVectorizer**: For transforming text data into numerical features.
- **Logistic Regression**: A classification model used for spam prediction.
- **Train-Test Split**: Splits the dataset into training and testing subsets for model evaluation.

## **Installation**

To run this project locally, you need to have Python installed. If you don't have Python installed, you can download it from [here](https://www.python.org/downloads/).

### 1. Clone this repository:

```bash
    git clone https://github.com/Ankana-Mandal/spam_email.git

2. Install dependencies:
    cd spam-classification
    pip install -r requirements.txt

requirements.txt should include the following libraries (if not already installed):
numpy
pandas
scikit-learn
gdown

