# Neural network implementation of a classification model aimed at breast cancer diagnosis
Final project for my Computational Intelligence lab, it consist in the creation of a classification neural network.
## Dataset
The project uses the breast cancer Wisconsin dataset.

SMOTE (Synthetic Minority Over-sampling Technique) is used to rebalance the training set and reduce bias.
## Model
The project makes use of a (not so) deep neural network (2 hidden dense layers). The network also includes dropout and normalization layers which may or may not be active depending on the results of the random search.

I tried implementing a more sophisticated random search that included a variable number of dense layers but in the short time i worked on this project i was not able to.

## Results
The results are overall satisfying with an accuracy on the test set over 90% in the great majority of cases and sometimes even >98%.

The relatively small dimensions of the dataset leave me some doubt on the generalization capabilities for a theoretical use over larger scale.