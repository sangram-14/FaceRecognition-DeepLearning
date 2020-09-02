# FaceRecognition-DeepLearning

# A Gentle Introduction to Deep Learning for Face Recognition

Face recognition is the problem of identifying and verifying people in photographs or video by their face.

For performing Face Recognition first we have to train our model and for training our we need Datasets.

# Face_Capture.py
This file capture images for our dataset.
First you have to create a Directory called "Images" for saving the captured images.
This code will capture 100 images. if you want more images to be capture just change count according to you.


# Face_Rec_Model.py
Next we have to create our model.
For that we have to create a proper and clean dataset as follows.

1. Create a directory naming Datasets.
2. In Datasets directory create two more directory called Train & Test Respectively.
3. Under Train & Test directory create directory called "person_name"(person_name = name of person whose image you have capture in Face_Capture.py). 
4. split your images into 80,20(80 images for Training data and 20 Images for testing data)
5. This code will trained the model and save it for further use.


# Face_Rec_Final.py
This code will load the model and predict the output(name of that person).

