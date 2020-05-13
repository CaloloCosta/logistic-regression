# logistic-regression
Artificial Intelligence and Computer Graphics - First Assignment

## Problem
The dataset in bank **−marketing−campaign.zip** represents a collection of
examples from a marketing campaign organised by a bank to get its clients
to place a term deposit. The dataset has 21 columns, described in Table 1.
**Your task is to build a classifier based on this dataset. The classifier should
use the regularised logistic regression algorithm, with the regularised cross-
entropy as its cost function. You will use the sum of the magnitude of all
the coefficients (also known as Lasso regularisation or L 1 regularisation) as
your regularisation technique.**

## Assessment Criteria
The following criteria will be followed to assess your submission:
- Data cleaning and preparation in Julia;
- Implementation (from scratch) of the regularised logistic regression al-
gorithm in Julia;
- Design and implementation of the classifier;
- Performance metrics including *(It is advised to use a confusion matrix.)*:
  **accuracy:** the proportion of correct predictions (clients correctly pre-dicted to have placed a term deposit or not) over all       predictions;
  **precision:** the proportion of clients the classifier predicted have placed a term deposit actually did so;
  **recall:** the proportion of clients that actually placed a term deposit which was predicted by the classifier
