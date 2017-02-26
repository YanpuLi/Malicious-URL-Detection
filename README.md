# Malicious-URL-Detection
Identify whether it's a malicious url or good one.

## Step
1. cut urls into tokens, split by / . and remove com net

2. calculating TF-IDF by using TfidfVectorizer

3. using Gridsearch to get best parameters

4. doing logistic regression

## Result

Accuracy: 97.6%(training set) 95.6%(testing set)