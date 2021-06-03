
<h3>DeepChest app</h3>
  
  The aim of DeepChest is to deliver a tool to clinicians to help them analyse lung ultrasound
  (LUS) images and make diagnostic and prognostic predictions. While LUS could be used to
  predict many kinds of lung pathologies, this first effort focuses on COVID-19
  The end product will consist of a phone app which guides the clinicians through the
  acquisition and uploading of LUS images, to then analyze them and provide a prediction.
  This tool aims, for now, to inform clinicians only and not to drive the diagnosis or even to
  make it. Therefore it falls in the category of a class IIa medical device.
  The DeepChest app project can be broken down into three work packages:<br>
  - Mobile app<br>
  - Image reprocessing<br>
  - DeepChest model

My work during this project was focus on the image preprocessing pipeline as well as the UI of the mobile app.
  
  <img src="https://github.com/NMartinod/DeepChest-app/blob/main/app.png" width="500" >
  
<h3>LUS CNN</h3>

The jupyter notebook LUS CNN classifier regroups the model architecture, the dataset for training and testing + data augmentation, the training and enable you to save the model through a .h5 file. This file is the one used during the scanning process, as we only need the final trained model. 


<h3>Image scanner</h3>

The jupyter notebook ImageScanner regroups all the function used for scanning and to verify if the image is a LUS image with the LUS CNN model.

<img src="https://github.com/NMartinod/DeepChest-app/blob/main/scanner.png" width="500" >
