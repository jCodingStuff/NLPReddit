# 1. Introduction #

# 2. Tasks #

# 3. Reddit API #

# 4. Am I The Asshole? #

# 5. ProTips #
## 5.1. Data Retrieval and split ##
**Post retrieval**
- *r/lifeprotips* (8 years old): 30k
- *r/shittylifeprotips* (7 years old): 30k
- *r/unethicallifeprotips* (3 years old): 30k
- *r/illegallifeprotips* (2 years old): 10k

<!-- Train / Validation / Test split -->
**Train / Validation / Test split**
- Train: $4/9$
- Validation: $2/9$
- Test: $1/3$

## 5.2. Validation and performance of ML models ##
**Validation for Naive Bayes (BOW)**<br>
<img src="report/imgs/plots_nb_inv.png" alt="Optimization for NB (BOW)" width="700"/>

**Validation for SVM (Word2Vec)**<br>
<img src="report/imgs/plots_svm1_inv.png" alt="Optimization for SVM (Word2Vec)" width="700"/>

**Validation for SVM (Pre-trained Word2Vec)**<br>
<img src="report/imgs/plots_svm2_inv.png" alt="Optimization for SVM (Pre-trained Word2Vec)" width="700"/>

<!-- Performance on test set -->
**Performance on test set**<br>
<img src="report/imgs/performance_inv.png" alt="Performance on test set" width="700"/>

<!-- Confusion matrices -->
**Confusion matrix for Naive Bayes (BOW)**<br>
<img src="report/imgs/nb_cf_inv.png" alt="Confusion matrix for Naive Bayes (BOW)" width="400"/>

**Confusion matrix for SVM (Word2Vec)**<br>
<img src="report/imgs/svm1_cf_inv.png" alt="Confusion matrix for SVM (Word2Vec)" width="400"/>

**Confusion matrix for SVM (Pre-trained Word2Vec)**<br>
<img src="report/imgs/svm2_cf_inv.png" alt="SVM (Pre-trained Word2Vec)" width="400"/>

# 6. Conclusions #
