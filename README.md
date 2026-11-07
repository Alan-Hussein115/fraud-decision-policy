# Fraud Decision Policy: From Model Scores to Net Value
> **Recommendation:** _[complete when analysis is finished]_

## The business question
A fraud model outputs a probability. A business needs a decision.
This project asks: at what threshold, and under what review capacity,
should a card-not-present (CNP) fraud model act, and what is it worth?

## Headline result
_[complete post analysis]_

## Approach
1. Time-ordered train/test split (avoid leakage from future data)
2. Baseline: logistic regression
3. Comparison: gradient-boosted trees
4. Cost model: missed fraud vs fraud decline vs manual review cost
5. Threshold chosen to maximise net value, then re-tested under a fixed
   daily review capacity
6. Drift check: does performance hold over time?

## Assumption
_[cost assumptions]_

## Data
IEEE-CIS Fraud Detection dataset (Kaggle). The data is not included in this repo.
Download 'train_transaction.csv' and 'train_identity.csv' from Kaggle and place them in 'data/'.

## How to run
_[complete later]_
