Milestone Assignment 2: Principal Component Analysis (PCA) Project Summary



 



This project uses Principal Component Analysis (PCA) on the Breast Cancer dataset from sklearndatasets.



The goal of this project is to find the most relevant factors that affect cancer diagnosis and lower the number of dimensions in the dataset while still being able to make accurate predictions.



 



The dataset has medical measurements of tumors and sorts them into two groups: malignant (cancerous) and benign (not cancerous).



 



Goals



1.Use the Breast Cancer dataset to run PCA.



2.Cut the dataset down to two main parts.



3.Find the variables that have the biggest effect.



4.Picture the PCA projection.



 



Set of data



 



You may get the dataset directly from scikit-learn by installing in on your python.



Details about the dataset:



1.569 records of patients



2.30 medical traits



3.1 target variable:



4.0 → Cancerous



5.1 → Not harmful



 



How It Was Done



1\. Preparing the Data



1.I Used load\_breast\_cancer() to load the dataset.



2.I Changed to a pandas DataFrame



3\. Separated features (X) from the target (y)



 



2\. Standardizing Data



I used StandardScaler to normalize all of the features so that PCA would operate well.



 



3\. Analysis of Principal Components



 



I used PCA to do the PCA (n\_components=2).



This cut the dataset down from 30 variables to 2 main components.



 



4\. Finding Important Variables



I looked at the PCA loadings to see which original features had the biggest impact on the main components.



5\. Visualization



To show the difference between malignant and benign tumors, I made a scatter plot of the two main components.



6.A Logistic Regression model was developed utilizing the two PCA components to forecast tumor diagnosis.



 



Results



1\. PCA was able to minimize the number of dimensions from 30 to 2.



2\. The two main components kept much of the important information.



3\. Logistic regression was able to predict tumor classification with almost 99% accuracy.



 



This shows that the dataset may be made much simpler without losing its ability to make predictions.



 



Final Thoughts



 



Principal Component Analysis successfully pinpointed critical diagnostic information within the dataset.



Even when the dataset was cut down to just two parts, the model still had a high level of predicted accuracy. This shows that PCA was able to find the most important variables that affect cancer diagnosis.



 



How to Start the Project



Indicate in the library that you need



1\. pip install matplotlib, pandas, numpy, and scikit-learn



2\. Open the notebook:



3\. milestone2\_pca.ipynb



4\. Run all of the cells from top to bottom.



5\. Files that are included



6\. milestone2\_pca.ipynb → PCA model and analysis



 



Name: Iwunze Trinitas Chideziri



Course: BAN6420



Assignment: Milestone 2 Assignment

