# Model card for "Telephone Company Prediction and Clustering Models"

## Model details

- Joan Lladó
- 20/12/2022
- Binary Classification and Clustering
- Machine Learning models based in KNN, Decision Tree, SVM (Lineal and Radial), K-means and Hierarchical Clustering
- joan.llado@estudiantat.upc.edu


## Intended use

### Primary intended uses
Supervised models intended for use within a telephone company. For the prediction of customers who left the company.
Non-Supervised models intended for use to see hidden patterns through variables.

### Primary intended users
For the workers of the telephone company.

### Out-of-scope use cases
It is not intended to be used for professional or non-curiosity purposes.


### Factors
Model only applicable for the company's customers. It will not work equally well for other companies.


## Metrics
The F1 Score for predicting customers who churned is around 80% for SVM models.


## Evaluation data
Dataset used: "telecom_customer_churn"
Removed "Latitude", "Longitude", "Monthly Revenue" and "City" variables.
All continuous data were normalized.
Some variables were grouped. 
Some methods were applied to avoid unbalanced labels.



## Quantitative analyses
Medium-high fiability model, F1 Score of 80% for SVM models.

Confusion Matrix of Linear SVM's result of applying a test.

![image](https://user-images.githubusercontent.com/25139526/210154434-88019d05-99b0-4063-8ece-e9f064f1d309.png)

Clusters generated from the K-means model

![image](https://user-images.githubusercontent.com/25139526/210154438-c9358338-33f0-45e2-88e6-dc58e5c20cfd.png)


## Ethical considerations
Not intended use for commercial reasons.
