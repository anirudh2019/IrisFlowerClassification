## Iris Flower Classification – Machine Learning Project :
**Introduction:**
- This program applies basic machine learning (classification) concepts on Fisher's Iris Data to predict the species of a new sample of Iris flower.

- The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor).

- Four features were measured from each sample (in centimetres):
         - Length of the sepals
         - Width of the sepals
         - Length of the petals
         - Width of the petals

- The central goal here is to design a model that makes useful classifications for new flowers or, in other words, one which exhibits good generalization.

**Software and Libraries:**
 1. Python (Scikit-learn, Pandas, Matplotlib, NumPy)
2. Jupyter Notebook (Anaconda3)

**Summary of this project:**
- The loaded data is summarized to have basic idea about the data and then visualised with the following plots to get the idea of distribution:

          - Box and whisker plots
          - Histograms
          - Scatter Matrix plot (to spot structured relationships between input variables)

- The data is splitted into Training set(80%) and Validation set(20%).

- Following 6 different models are built: (2 linear and last 4 are non-linear algorithms)
          - Logistic Regression (LR)
          - Linear Discriminant Analysis (LDA)
          - K-Nearest Neighbors (KNN)
          - Classification and Regression Trees (CART)
          - Gaussian Naive Bayes (NB)
          - Support Vector Machines (SVM)


- **Stratified 10-fold cross validation technique** is used to estimate accuracy of the 6 models.

- From the results, it is observed that Support Vector Machines (SVM) has the largest estimated accuracy score at about 0.98 or 98%.

- SVM model is fitted on the entire training set and is used to make predictions on the Validation set.

- Finally, the predictions are evaluated by calculating Classification Accuracy, Confusion Matrix and Classification Report.
