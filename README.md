# Kaggle Competition: BBC News Classification

**Link:** [Kaggle Competition Overview](https://www.kaggle.com/c/learn-ai-bbc/overview)

## Description

Text documents are one of the richest sources of data for businesses. In this competition, we will use a public dataset from the BBC, which is comprised of 2225 articles. Each article is labeled under one of five categories: **business**, **entertainment**, **politics**, **sport**, or **tech**.

The dataset is divided into:
- **1490 records** for training
- **735 records** for testing

The goal is to build a system that can accurately classify previously unseen news articles into the correct category.

For more insights on tackling this problem, refer to the following blog: [Problem Solving with ML: Automatic Document Classification](https://cloud.google.com/blog/products/gcp/problem-solving-with-ml-automatic-document-classification)

## Evaluation

The evaluation metric for this competition is **Accuracy**. A sample solution file is provided to demonstrate the required format for submission. The file should contain a header and the following two columns:
- **ArticleId** (from the Test File)
- **Category** (one of the five categories: sport, tech, business, entertainment, or politics)