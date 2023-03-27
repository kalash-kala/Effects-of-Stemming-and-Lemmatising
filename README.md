# Effects of Stemming and Lemmatisation

### Objective of this Exercise :

- Getting used to Stemming and lemmatisation libraries on NLTK
- Using these concepts in actual code to test various classification algorithms on textual data
- Seeing the effect of these processes on the accuracy of various classification algorithms

### The experiments we have considered are as follows :

1. Without removing stop words and without using lemmatisation
2. Removing stop words but not using lemmatisation
3. Removing stop words and using stemmer and lemmatisation (separately)

### Classification Algorithms used. :

- Logistic regression
- Linear SVC
- SVC with kernel = rbf
- Random Forrest Classifier
- Multinomial Naive Bayes
- K nearest neighbours

## Results :

### Accuracy of Experiment 1 :

| Classifier | Accuracy |
| --- | --- |
| Logistic regression | 97% |
| Linear SVC | 98% |
| SVC (Kernel = rbf) | 97% |
| Random Forrest | 95% |
| Multinomial Naive Bayes | 95% |
| K nearest neighbour | 92% |

### Accuracy of Experiment 2 :

| Classifier | Accuracy |
| --- | --- |
| Logistic regression | 98% |
| Linear SVC | 98% |
| SVC (Kernel = rbf) | 98% |
| Random Forrest | 97% |
| Multinomial Naive Bayes | 97% |
| K nearest neighbour | 93% |

### Accuracy of Experiment 3 (Using Snow ball Stemmer):

| Classifier | Accuracy |
| --- | --- |
| Logistic regression | 98% |
| Linear SVC | 98% |
| SVC (Kernel = rbf) | 98% |
| Random Forrest | 96% |
| Multinomial Naive Bayes | 97% |
| K nearest neighbour | 93% |

### Accuracy of Experiment 3 (Using lemmatisation) :

| Classifier | Accuracy |
| --- | --- |
| Logistic regression | 97% |
| Linear SVC | 97% |
| SVC (Kernel = rbf) | 97% |
| Random Forrest | 96% |
| Multinomial Naive Bayes | 97% |
| K nearest neighbour | 94% |

## Conclusion :

- Removal of stop words has positively affected the performances of all the classifiers
- Using Advanced operations like stemming and lemmatisation has had no major effect on Logistic Regression and SVC (linear and rbf), but has increased the accuracy for rest of the models
- Assessing the overall performances , we see that the simpler models are performing better than the complex ones, we have indirectly proven the common notion in machine learning that often time simpler models do the task better than the complex ones
- NOTE : There are chances that if you run this on your system then you might get different values of Accuracy