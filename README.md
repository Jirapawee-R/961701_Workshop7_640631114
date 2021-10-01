# 961701_Workshop7_640631114
961701_Workshop7_640631114 is an assignment to compare
self-implement KNN classifier with sklearn knn classifier.
Dataset used in this project is Iris datasets available on 
sklearn datasets.

## Dataset
Iris dataset consists of 3 classes of 50 instances each.
the class refers to a species of iris flower. 

## Class: KNeighboursSelfImplement
class of self-implement KNN classifier composed of 5 functions
including:
###1) fit() : to keep data
-> call KNeighboursSelfImplement.fit(X_train, y_train)
###2) calculateDistance() : calculate distance between neighbours
-> call  KNeighboursSelfImplement.calculateDistance(x1, x2)
###3) getKNeighbors() : group neighbours following k value from cv
-> call  KNeighboursSelfImplement.getKNeighbors(X_test)
###4) predict() : to predict the class
-> call  KNeighboursSelfImplement.predict(X_test)
###5) score() : to show accuracy rate
-> call  KNeighboursSelfImplement.score(X_test, y_test)
###6) model_eval() : consisted of precision, recall, f1-score, and auccuracy project
-> KNeighboursSelfImplement.model_eval(X_test, y_test)

##Example Output
the output from program including DataFrame, cross-valiadation
, Accuracy and confusion matrix.