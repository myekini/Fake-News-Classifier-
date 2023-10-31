# Fake News Classifier Machine Learning Project

This repository contains a machine learning project focused on classifying news articles as either real or fake using Natural Language Processing (NLP) techniques. The project utilizes NLTK (Natural Language Toolkit) for text preprocessing and employs the Multinomial Naive Bayes (MultinomialNB) algorithm and the Passive Aggressive Classifier for text classification. Additionally, the project includes the use of a confusion matrix for evaluating the model's performance and TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction.

## Table of Contents

- [Fake News Classifier Machine Learning Project](#fake-news-classifier-machine-learning-project)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Data](#data)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
  - [License](#license)

## Project Overview

The objective of this project is to develop a machine learning model capable of classifying news articles as either real or fake. The model's core components include text preprocessing with NLTK, feature extraction using TF-IDF, and text classification with the Multinomial Naive Bayes algorithm and the Passive Aggressive Classifier.

Key project objectives:

- Implement text preprocessing to prepare the data for classification.
- Use TF-IDF to convert text data into numerical features.
- Train and evaluate a MultinomialNB model and a Passive Aggressive Classifier.
- Utilize a confusion matrix to assess model performance.
- Provide a tool for identifying potentially fake news articles.

## Data

The dataset used for this project includes labeled news articles with two classes: real and fake. The dataset can be found in the `data` directory as `news_data.csv`. It includes the following columns:

- `Title`: The title of the news article.
- `Text`: The content of the news article.
- `Label`: The label indicating whether the article is real or fake.

## Installation

To run the project and use the code, you need to set up your environment. Start by cloning this repository:

```bash
git clone https://github.com/yourusername/fake-news-classifier.git
cd fake-news-classifier
```

Then, create a virtual environment and install the required dependencies:

```bash
virtualenv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

## Usage

You can follow these steps to use the project:

1. Ensure you have completed the installation steps mentioned above.

2. Run the Jupyter notebooks provided in the `notebooks` directory to explore the data, preprocess the text, extract features with TF-IDF, and build classification models.

3. Train and evaluate both the MultinomialNB model and the Passive Aggressive Classifier.

4. Utilize a confusion matrix to assess model performance, measuring accuracy, precision, recall, and F1 score.

5. Use the trained model to classify news articles as real or fake.

6. Interpret the results and provide a tool for identifying potentially fake news articles.

## Project Structure

The project structure is organized as follows:

```
fake-news-classifier/
    ├── data/
    │   ├── news_data.csv
    ├── notebooks/
    │   ├── 01_Data_Exploration.ipynb
    │   ├── 02_Text_Preprocessing.ipynb
    │   ├── 03_TF-IDF_Feature_Extraction.ipynb
    │   ├── 04_Modeling_and_Evaluation.ipynb
    ├── src/
    │   ├── utils.py
    ├── README.md
    ├── requirements.txt
    ├── LICENSE
```

- The `data` directory contains the dataset for news articles.
- The `notebooks` directory contains Jupyter notebooks for data exploration, text preprocessing, TF-IDF feature extraction, and modeling and evaluation.
- The `src` directory includes utility functions used in the notebooks.
- `README.md` (this file) provides an overview of the project and instructions.
- `requirements.txt` lists the project dependencies.
- `LICENSE` specifies the project's license.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

**Note**: Ensure you replace `yourusername` in the repository URL with your actual GitHub username when cloning the repository.

For any questions or issues related to this project, please feel free to contact the project contributors.

Stay informed, and use the tools provided by this project to identify fake news articles effectively! 📰🕵️‍♂️