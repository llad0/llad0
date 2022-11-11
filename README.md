# Model card for "USA State Prediction Model"

## Model details

- Joan Lladó
- 10/11/2022
- Multiclass Classification
- Machine Learning model based in Random Forests, 20 samples and GINI splitting criteria as hyperparametters.
- joan.llado@estudiantat.upc.edu


## Intended use

### Primary intended uses
Intended to be used in state prediction of United States.

### Primary intended users
For anyone who wants to predict a state in the US.

### Out-of-scope use cases
Not intended to be used for any profesional or not-curiosity reasons.


### Factors
Model only applicable in the U.S.A., and only in the following states: California, Texas, Florida, Illinois, Colorado, Michigan, Arizona, Washington, Virginia, Massachusetts, North Carolina, New Jersey, New York, Indiana, Minnesota, Ohio, Maryland.


## Metrics
The accuracy of the model varies between 20% and 30%.


## Evaluation data
Dataset used: "US Cities"
Removed "Race", "Count", "City" and "State Code" variables.
All data were normalized or transformed into proportion.
Some rows were treated to avoid NaN values.
Some rows were deleted to avoid overfitting.


## Quantitative analyses
Low fiability model, accuracy level between 20% and 30%.

Confusion Matrix of model's result of applying a test.
![image](https://user-images.githubusercontent.com/25139526/201430128-e79b2380-3702-4153-aa91-e351d5a438b4.png)


## Ethical considerations
Not intended use for discrimiation between USA states.
