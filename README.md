# Destracted_Driver_Detection
Based upon images and videos detection 

Each model have the same procedure except weights by changing layers 
**CNN :: VGG 16 :: VGG 16-FINE-TUNED :: VGG 16-MODIFIED (COMPLETE PROCESSING)**
1:- Importing the libraries 
2:- Defining the train,test and model directories
3:- Data Prepration
4:- Observation 
5:- Converting Input into numerical values
6:- Splitting into Train and Test sets
7:- Converting into 64*64 images
8:- Defining the Model
9:- Train upon (train , ytrain , validation-data)
10:- Model Analysis
        =>By calling function
11:- Checking Result by using Heatmap
12:- Precision Recall F1 Score

**-::DRIVER-PREDICTION(MODEL)::-**

1:- Importing Libraries
2:- Prediction using-->Self Trained Model (CNN Scratch)
3:- Read the all test images 
         =>testing on the only 10000 images as loading the all test images requires ram>8gb
         =>Converts a Python object hierarchy into a byte stream written to a buffer or to a disk file.
4:- Labeling & Testing
         =>predicting model at both train and valid with single single animated progress bar 
         =>to create a human readable and understandable class_name 
         =>creating the prediction results for the image classification and shifting the predicted images to another folder
           with renamed filename having the class name predicted for that image using model
           
