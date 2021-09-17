<h1>1. Cancer diagnosis classification with multiple models </h1>

<h3>2. Packages Used to solve this classification problem </h3>

      a. import numpy as np
      b. import pandas as pd
      c. import matplotlib.pyplot as plt
      d. import seaborn as sns 
      e. from sklearn.model_selection import cross_val_score
      f. from sklearn.linear_model import LogisticRegression 
      g. from sklearn.model_selection import train_test_split
      h. from sklearn import metrics 
      j. from sklearn.metrics import classification_report
      k. from sklearn.metrics import roc_curve
      l. from sklearn.naive_bayes import GaussianNB
      m. from sklearn.metrics import confusion_matrix
      n. from sklearn.svm import SVC

<h3>3. Load the dataset   </h3>  
<h3>4. EDA </h3>
<h3>5. Checking for missing values. </h3>
    
        a. 569 Null-values are present in the Unnamed: 32 column.
        b. Drop Unnamed: 32 column.
  
<h3>6. Visualization. </h3>

        a. Diagnosis countplot
 
 ![Alt Text](https://github.com/Aamir8539/Cancer-Diagnosis-Classification-with-multiple-models/blob/main/count%20plot%20of%20diagnosis.png)
 
        a. Correlation Heatmap
 
 ![Alt Text](https://github.com/Aamir8539/Cancer-Diagnosis-Classification-with-multiple-models/blob/main/correlation%20heatmap.png)
 
 <h3>7. Split your data into a training set and a testing set. </h3>
 
 <h1>8. Logistic Reggression Model. </h1>
 
        a. Confusion Matrix for Logistic Model
 
 ![Alt Text](https://github.com/Aamir8539/Cancer-Diagnosis-Classification-with-multiple-models/blob/main/confusion%20matrix%20of%20Logistic%20model.png)
 
        b. Classification Report for Logistic Model
        
            precision    recall  f1-score   support

               0       0.94      0.94      0.94       108
               1       0.89      0.90      0.90        63

        accuracy                           0.92       171
       macro avg       0.92      0.92      0.92       171
    weighted avg       0.92      0.92      0.92       171





        c. ROC Curve For Logistic Model.
 
 ![Alt Text](https://github.com/Aamir8539/Cancer-Diagnosis-Classification-with-multiple-models/blob/main/ROC%20curve%20of%20Logistic%20model.png)
 
 <h1>9. Naive Bayes Model. </h1>
 
        a. Confusion Matrix For Naive Bayes Model.
 
 ![Alt Text](https://github.com/Aamir8539/Cancer-Diagnosis-Classification-with-multiple-models/blob/main/confusion%20matrix%20of%20Naive%20Bayes%20model.png)
 
        b. Classification Report For Naive Bayes Model.
        
            precision    recall  f1-score   support

               0       0.95      0.96      0.96       108
               1       0.94      0.92      0.93        63

        accuracy                           0.95       171
       macro avg       0.94      0.94      0.94       171
    weighted avg       0.95      0.95      0.95       171




        c. ROC Curve for Naive Bayes Model.
 
 ![Alt Text](https://github.com/Aamir8539/Cancer-Diagnosis-Classification-with-multiple-models/blob/main/ROC%20curve%20of%20Naive%20Bayes%20model.png)
 
  <h1>10. SVM Model. </h1>
 
        a. Confusion Matrix For SVM Model.
 
 ![Alt Text](https://github.com/Aamir8539/Cancer-Diagnosis-Classification-with-multiple-models/blob/main/confusion%20matrix%20of%20SVM%20model.png)
 
        b. Classification Report For SVM Model.
        
            precision    recall  f1-score   support

               0       0.90      0.98      0.94       108
               1       0.96      0.81      0.88        63

        accuracy                           0.92       171
       macro avg       0.93      0.90      0.91       171
    weighted avg       0.92      0.92      0.92       171




        c. ROC Curve for SVM Model.
 
 ![Alt Text](https://github.com/Aamir8539/Cancer-Diagnosis-Classification-with-multiple-models/blob/main/ROC%20curve%20of%20SVM%20model.png)

