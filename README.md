# 1. Introduction #

# 2. Tasks #

# 3. Reddit API #

# 4. Am I The Asshole? #

# 5. ProTips #

<!-- Optimization for ML models -->
**Naive Bayes (BOW)**<br>
![alt text](report/imgs/plots_nb_inv.png "Optimization for Naive Bayes (BOW)")

**SVM (Word2Vec)**<br>
![alt text](report/imgs/plots_svm1_inv.png "Optimization for SVM (Word2Vec)")

**SVM (Pre-trained Word2Vec)**<br>
![alt text](report/imgs/plots_svm2_inv.png "Optimization for SVM (Pre-trained Word2Vec)")

<!-- Performance on test set -->
|         Repr.         |  Classifier | Lapl. | Reg. | Accuracy | Precision | Recall | FScore |
|:---------------------:|:-----------:|:-----:|:----:|:--------:|:---------:|:------:|:------:|
|          BOW          | Naive Bayes |  0.58 |   -  |  62.70%  |    0.64   |  0.64  |  0.64  |
|        Word2Vec       |     SVM     |   -   | 1.78 |  62.12%  |    0.64   |  0.62  |  0.63  |
|  Pre-trained Word2Vec |     SVM     |   -   | 4.00 |  65.79%  |    0.68   |  0.65  |  0.66  |

# 6. Conclusions #
