# Capstone Project 2 Proposal

## Problem
Quora users post a large number of questions every day. A lot of these questions have very similar meaning and intent.
In this project, we need to identify the duplicate question pairs so that the effort in answering and managing them is not duplicated.

## Client
The client of this project is Quora itself. They do already have one algorithm that uses random forest. 
Now've they've put up this project on Kaggle so that people can submit their better solutions. 

## Dataset
The dataset is available from Kaggle.

## Approach
There are a number of approaches that can be tried.
1. Build LDA topic vectors for each question and build a classifier that can label duplicates.
2. Use LSA / LSI topics and use t-SNE for visualization and dimensionality reduction.
3. Use word2vec or doc2vec and build a classifier on the vectors.

## Deliverables
1. Preliminary Report
2. Exploratory data analysis report having the descriptive statistics and visualizations of the dataset.
3. Prediction model building
4. Associated Pandas code
5. Slidedeck for final presentation
6. Executive summary with recommendations.
