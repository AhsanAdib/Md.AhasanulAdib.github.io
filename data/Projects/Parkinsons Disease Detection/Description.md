We built a machine learning classification system to identify Parkinson's disease from biomedical voice measurements, using Python, Pandas, Scikit-learn and Google Colab.

The dataset has 195 voice recordings with 22 features such as jitter, shimmer and HNR. We cleaned and scaled the data, then compared four classifiers using 3-fold cross-validation: Support Vector Machine (SVM), Logistic Regression, Gradient Boosting and a Multilayer Perceptron (MLP).

## Result

The MLP did best, with a mean accuracy of 89.74% and an F1-score of 93.22%.
