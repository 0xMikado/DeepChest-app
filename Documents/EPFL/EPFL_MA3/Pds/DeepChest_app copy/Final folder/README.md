

<h3>LUS CNN</h3>

The jupyter notebook LUS CNN classifier regroups the model architecture, the dataset for training and testing + data augmentation, the training and enable you to save the model through a .h5 file. This file is the one used during the scanning process, as we only need the final trained model and  ot to generate and train a new one every time. Pay attention that the tensorflow version you are using when doing prediction needs to be the same than the one used to save the model. If a problem occurs, just retrain the model and save it using the notebook. 

It includes also the dataset used to train the model


<h3>dataset</h3>

The jupyter notebook ImageScanner regroups all the function used for scanning and to verify if the image is a LUS image with the LUS CNN model. It contains also the dataset used to verify the scanning quality on the DeepChest model. Testing_photo contains the picture of the LUS on a screen. Testing_scanned is the result of the scanning and Testing_orignal is the orginal LUS images.

To use it, you have to modify the directory of the images you want to scan and where you want to store the result.


More information on both CNN and scanner can be found in the report of this semester project.