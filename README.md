# Project Report :
## Heart Disease Prediction using multiple Machine Learning Classifiers
* In this mini-project, I've trained multiple models on a small dataset [(Link)](https://www.kaggle.com/ronitf/heart-disease-uci) to identify if a person has a heart disease or not.
* The following machine learning models were trained in this project :
	* Decision Tree
	* Random Forest 
	* Support Vector Machine with a Polynomial Kernel
	* K-nearest neighbors
	* Logistic Regression
	* Naive Bayes
	* Hard Voting based Ensemble
* The dataset of 303 examples was split into 242 training examples & 61 test examples.
* Evaluation Metrics used for determining model accuracy - Accuracy Score & F1 Score.
* Hyperparameters for the first 6 models (as listed above) were tuned via 10-fold cross validation using GridSearchCV.
* For the Ensemble-based model, a Hard Voting Ensemble Classifier was implemented using Logistic Regression, Support Vector Machine with a Gaussian RBF Kernel, Decision Tree & Random Forest Classifiers.
* Model performance details : 

	|Serial No.| Tables        | Are           | Cool  |
	|---| ------------- |:-------------:|-------|
	|s     | col 3 is      | right-aligned | $1600 |
	|s     | col 2 is      | centered      |   $12 |
	|s-    | zebra stripes | are neat      |    $1 |

#### Results :
The **Hard Voting Ensemble Model** has the highest out-of-sample accuracy score of 0.87 as well as highest F1 score of 0.87 whereas the Decision Tree Model has the lowest out-of-sample accuracy score of 0.75 as well as lowest F1 score of 0.76. The second-best performing model is - with an out-of-sample accuracy score of - as well as an F1 score of -

>*Note : Because of the small size of the dataset, a better test-set performance couldn't be attained. Also, a small dataset puts a constraint on the test-set size, which in turn prevents us from getting an accurate estimation on our out-of-sample evaluation metrics which actually help us estimate how our models will perform in the real world.*
