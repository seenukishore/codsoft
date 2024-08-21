# SPAM SMS Detection

## Overview

This project focuses on building an AI model capable of classifying SMS messages as either spam or legitimate (ham). By leveraging natural language processing techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) combined with the Naive Bayes classifier, the model effectively identifies spam messages.

## Table of Contents

- [Dataset](#dataset)
- [Modeling Techniques](#modeling-techniques)
- [Evaluation](#evaluation)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used for training and evaluating the model consists of labeled SMS messages, where each message is classified as either "spam" or "ham." The dataset can be obtained from sources like [Kaggle](https://www.kaggle.com/uciml/sms-spam-collection-dataset).

## Modeling Techniques

### 1. Text Preprocessing

- Tokenization
- Stop words removal
- Lemmatization/Stemming
- Conversion to lowercase

### 2. Feature Extraction

- **TF-IDF**: Converts the text data into numerical features that represent the importance of each word in the context of the entire dataset.

### 3. Classification Algorithm

- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem with strong independence assumptions between features. It is particularly effective for text classification tasks and was chosen for its simplicity and efficiency.

## Evaluation

The model was evaluated using various metrics, including:

- **Accuracy**: The percentage of correctly classified messages.
- **Precision**: The number of true positive results divided by the number of all positive results.
- **Recall**: The number of true positive results divided by the number of relevant samples (all spam messages).
- **F1 Score**: The harmonic mean of precision and recall.

Cross-validation was employed to ensure the model's robustness and to fine-tune its performance.

## Results

The Naive Bayes classifier, combined with TF-IDF for feature extraction, achieved the following results:

- **Accuracy**: [Your accuracy result here]%
- **Precision**: [Your precision result here]%
- **Recall**: [Your recall result here]%
- **F1 Score**: [Your F1 score result here]

These metrics indicate that the model is effective in distinguishing between spam and legitimate messages, with a strong balance between precision and recall.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
