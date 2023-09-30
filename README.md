# Rain_Prediction_Model_By_ML

# Process of making Model
1) Importing Data
2) Data Preprocessing
3) One Hot Encoding
4) Train and Test Data Split
5) Train Logistic Regression, KNN, Decision Tree, SVM, and Linear Regression models and return their appropriate accuracy scores

## We used following algo. for Train model.
1) Linear Regression
2) KNN
3) Decision Trees
4) Logistic Regression
5) SVM

## We will evaluate our models using:
1) Accuracy Score
2) Jaccard Index
3) F1-Score
4) LogLoss
5) Mean Absolute Error
6) Mean Squared Error
7) R2-Score

### Source of Dataset :-  Australian Government's Bureau of Meteorology and extra feature like RainToday and RainTomorrow from rattle website.

Our Final dataset contain:-
rows :- 3271
features :- 68 After hot_encoding

## Performance Matrix of our Model.

1) Linear regression :-
Metric Value
MAE 0.256321
MSE 0.115720
R2 0.427135

2) KNN :-

KNN Accuracy Score is :- 81.83206106870229
KNN_Jaccard_Index is :- 0.4251207729468599
KNN_F1_Scoreis :- 0.5966101694915255

3) Decision Tree :-

Tree_Accuracy_Score is :- 0.7587786259541984
Tree_JaccardIndex is :- 0.3923076923076923
Tree_F1_Score is :- 0.56353591160221

4) Logistic Regression
LR Accuracy Score by predict method is:- 0.8259541984732824
LR Accuracy Score by predict_proba method is:- 0.8259541984732824
LR Jaccard Index by predict method is:- 0.47706422018348627
LR Jaccard Index by predict_proba method is: - 0.47706422018348627
LR F1 Score by predict method is: - 0.6459627329192547
LR F1 Score by predict_proba method is:- 0.6459627329192547
LR Log Loss by predict_proba method is:- 0.3880358597324609

5) SVM ( Support vector Machine) :-
Metric Value
A_SC 83.816794
J_SCR 0.506977
F1_SCR 0.672840
