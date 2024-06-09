# OCR-Using-ANN-and-Random-Forest

#Description

This project involves developing two distinct Optical Character Recognition (OCR) systems: one utilizing Artificial Neural Networks (ANN) and the other employing a Random Forest classifier. The aim is to compare the performance of these two machine learning approaches in accurately converting handwritten text into machine-encoded text.

#Dataset

The EMNIST Letters dataset is a subset of the EMNIST (Extended MNIST) dataset designed specifically for recognizing handwritten letters. It includes a balanced set of uppercase and lowercase letters merged into a single class for each letter, making it a valuable resource for training and evaluating Optical Character Recognition (OCR) systems focused on alphabetic characters.

#Files

ANN.ipynb: the notebook containing OCR implementation using an Artificial Neural Network with two dense hidden layers and two dropout layers to avoid overfitting. 
RandomForest.ipynb: the notebook containing OCR implementation using a Random Forest Classifier.
OCRUsingANN.h5: the saved ANN trained model
OCRUsingRF.joblib: the saved Random Forest trained model
emnist-letters-test.csv: this subset of the EMNIST dataset consists of a collection of handwritten letters used for training machine learning models.
emnist-letters-train.csv: his subset of the EMNIST dataset is used for testing the trained machine learning models.

#Dependencies

The following Python libraries are required to run the code:
•	scikit-learn (sklearn)
•	tensorflow
•	matplotlib
•	seaborn
•	pandas
•	numpy
•	tkinter
•	PIL (Python Imaging Library)
•	%matplotlib inline (magic command for Jupyter Notebooks)

#Technical Steps

The notebooks cover the following steps:

•	Processing the EMNIST letter dataset to be used as input for the model.
•	Training the model on the pictures in the dataset.
•	Save the trained model for immediate use.
•	Test the accuracy of the model using random images of handwritten characters.

Note: images should have a black background and written in white



