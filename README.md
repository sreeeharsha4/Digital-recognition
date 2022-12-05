
# Digit Recognition

## Problems with handwritten digits

The handwritten digits are not always of the same size, width, orientation and justified to margins as they differ from writing of person to person, so the general problem would be while classifying the digits due to the similarity between digits such as 1 and 7, 5 and 6, 3 and 8, 2 and 5, 2 and 7, etc. This problem is faced more when many people write a single digit with a variety of different handwritings. Lastly, the uniqueness and variety in the handwriting of different individuals also influence the formation and appearance of the digits. Now we introduce the concepts and algorithms of  machine learning.










## Data sets
Following points are same in training and testing set along with the set of the images and labels files –

   1) Pixels are arranged row-wise, ranging from 0 to 255, as from RGB color code.
   2) Background as white (0 value from RGB) and foreground as black (255 value from RGB).
   3) Labels of digits classified from 0 to 9.


The first column or value is the “label”, that is, the actual true digit that the handwriting is supposed to classify, such as a “7” or “9”. It is the correct solution to which the classifier is aspiring to classify.
The remaining values or all comma separated values, are the pixel values intensities of the handwritten digit, varying from 0 to 255. The size of an image is 28 by 28, so there are 784 (28*28) values for the label


## Train data set img

## Graph


## CLASSIFIERS
## SVM (Support Vector Machine)

SVM falls into the category of supervised learning, and with the bonus of classification as well as regression problems. Generally, SVM draws an optimal hyperplane which classifies into different categories. In two dimensional space, To start with we plot the data points of the independent variable corresponding to the dependent variables. Then, begin the classification process from looking the hyperplane or any linear or nonlinear plane differentiated the two class at its best.

Grid SearchCV is used to find best parameter in 
class sklearn.svm.SVC("C":[0.1,1,10,100],   "kernel":['ploy','linear','rbf','sigmoid']}


Accuracy score : 0.981

## Prediction of test data by SVM img
## Authors

 @ SREE HARSHA K

