# Diagnosing CKD with KNN and Logistic Regression Classifiers

### Summary
In this project, I use Logistic Regression and K-Nearest Neighbors (KNN) to diagnose CKD. Both were able to classify patients with 100% accuracy on unseen test data.  CKD appears to be highly predictable given the right health/blood metrics. 

KNN required class balancing, scaling, and model tuning to perform with 100% accuracy, while Logistic Regression was 100% accurate without tuning (note: still had to stratify the train test split).

Logistic Regression is deemed a better model for this case, because in addition to being 100% accurate, it also allows us to quantify the impact of unit increases in specific variables on likelihood of having CKD.

There are three links you may find important:
- [A set of chronic kidney disease (CKD) data and other biological factors](./chronic_kidney_disease_full.csv).
- [The CKD data dictionary](./chronic_kidney_disease_header.txt).
- [An article comparing the use of k-nearest neighbors and support vector machines on predicting CKD](./chronic_kidney_disease.pdf).

