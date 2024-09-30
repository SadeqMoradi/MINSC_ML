# KNeighborClassifier and MINST dataset
# Introduction
This code is originally written for Kaggle's Digit Recognizer competetion. It uses MINST dataset to train a digit recognition model. The code is added as a Jupyter notebook.
# MINST dataset 
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning. It was created by "re-mixing" the samples from NIST's original datasets. The creators felt that since NIST's training dataset was taken from American Census Bureau employees, while the testing dataset was taken from American high school students, it was not well-suited for machine learning experiments. Furthermore, the black and white images from NIST were normalized to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.
# The k-nearest neighbors algorithm
The k-nearest neighbors (KNN) algorithm is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. It is one of the popular and simplest classification and regression classifiers used in machine learning today. KNN algorithm is used in this code to classify images into their correct catagory.

While the KNN algorithm can be used for either regression or classification problems, it is typically used as a classification algorithm, working off the assumption that similar points can be found near one another.
# Perfromance Measurment
Measurments have been done using the confusion matrix method. The figure 1 shows that all digits have a recognition accuaracy of more than 94 percent. The figure 2 also shows that the most errors are caused because of the model confusing 9 and 4 with each other.


<p align="center">
  <img src="https://github.com/SadeqMoradi/MINSC_ML_KNeighborClassifier/blob/main/Images/ConfusionMatrix1.png" alt="Image 1 Description" width="500">
  <img src="https://github.com/SadeqMoradi/MINSC_ML_KNeighborClassifier/blob/main/Images/ConfusionMatrix2.png" alt="Image 2 Description" width="500">
</p>

<p align="center">
  <b>Fig 1 : Confusion Matrix</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <b>Fig 2 : Confusion Matrix</b>
</p>



# Refrences
* MNIST database - https://en.wikipedia.org/wiki/MNIST_database
* IBM : What is the k-nearest neighbors (KNN) algorithm? - https://www.ibm.com/topics/knn#:~:text=The%20k-nearest%20neighbors%20(KNN,used%20in%20machine%20learning%20today
