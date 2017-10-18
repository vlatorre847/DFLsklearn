DFLsklearn is a method to find the hyperparameters of a machine learning algorithm in scikit-learn. 
The method automatically supports many estimators among the ones present in sklearn, but it is also capable of handling all the algorithms that inherit from the base estimator class of  sklearn.

Installation
The code can be downloaded from github and then installed by terminal by using the following instruction in the folder where the codes has been downloaded:
Python setup.py install

Usage

See how to use the code in the examples.py. 
The file examples.py has examples both for classification and regression, plus an example to initialize a custom estimator from sklearn.

The file "custom_funct_interfaces.py" contains some examples of custom functions that interface DFL to the estimators of sklearn. Such functions can be used as templates for a user made function.
