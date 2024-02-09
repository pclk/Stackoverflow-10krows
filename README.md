# StackOverflow 10k Rows Dataset

## Overview

This repository contains a collection of 10,000 rows of data scraped from StackOverflow discussions related to Python. The dataset offers a unique insight into common questions, programming challenges, and the level of community engagement within the Python section of StackOverflow.

## Contents

- **Scraping Notebook**: A Jupyter notebook detailing the process used to scrape StackOverflow discussions.
- **10k Dataset**: The raw dataset comprising 10,000 rows of scraped data.
- **Categorization Notebook**: A Jupyter notebook that categorizes StackOverflow posts into popularity categories based on scraped features.
- **10k Categorized Dataset**: The dataset after categorization, based on features such as upvotes, views, and answers.

## Dataset Schema

The dataset includes the following columns:

- **link**: URL of the discussion.
- **upvotes**: Number of upvotes (can be negative).
- **answers**: Number of answers in the discussion.
- **views**: Number of views for the discussion.
- **content**: The content of the question, excluding code and post notices.
- **code_length**: The character length of the code within the question.

## Sample Data
### SO_10k
![Dataset sample](https://github.com/Confunius/Stackoverflow-10krows/assets/132553855/ea468ba9-4a09-41fa-8f01-afb2e1c275d3)
### SO_10k_categorized
<img width="519" alt="image" src="https://github.com/Confunius/Stackoverflow-10krows/assets/132553855/681baa68-745b-4b9c-9132-65171e97a036">


## How to Use

1. **Clone the repository**: Get a local copy of the dataset and notebooks for analysis.
2. **Explore the dataset**: Use the provided Jupyter notebooks to understand the scraping and categorization processes.
3. **Analysis**: Leverage the categorized dataset for further analysis, such as identifying trends, common questions, and the impact of different factors on post popularity.

## Contribution

Contributions to improve the dataset, scraping, or categorization methods are welcome. Please submit a pull request or open an issue to discuss potential enhancements.
