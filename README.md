# Deep Learning Group Course Work - 2023

**Yelp Review Data Analysis with Deep Learning Models - Sentiment Analysis**

## Group Members

- Lakshani Nissanka - 20210570
- Suvini Viduneth - 20210569
- Kavindya Koralegei - 20210575

## Overview

Implementation of a Supervised and Unsupervised Models to find the Optimal model that can be used for the sentiment analysis

*Models Using:*
- Convolutional Neural Networks (CNN) 
- BERT with K-Means clustering

## Dataset

- Link to the [Yelp Reviews dataset](https://www.yelp.com/dataset).
- We are using the  - The json file "yelp_academic_dataset_review.json" for our purpose.

## Project Structure

```plaintext
project-root/
│
├── data/
│   ├── yelp_dataset.json       # Downloaded Yelp dataset
│
├── models/
│   ├── supervised_model/       # Code and files related to the supervised model
│   ├── unsupervised_model/     # Code and files related to the unsupervised model
│
├── notebooks/
│   ├── Preprocessing.ipynb  # Notebook for the supervised model
│   ├── Supervised_Model_CW2.ipynb # Notebook for the supervised model
│   ├── Unsupervised_Model_CW2.ipynb # Notebook for the unsupervised model
│
├── README.md                   # This README file
```

## Data Preprocessing

 -You can reference the `Preprocessing.ipynb` notebook for details.

## Supervised Model

-We have used CNN model as the Supervised Model for this task.
-Reference the `Supervised_Model_CW2.ipynb` notebook for code and results.

## Unsupervised Model

-We have used BERT along with K-Means clustering Model for this task.
-We used a pretrained BERT model from hugging face to implement the BERT model.
-Reference the `Unsupervised_Model_CW2.ipynb` notebook for code and results.
