# Petals-to-the-Metal---Flower-Classification-on-TPU-
This is a model built using machine learning to predict the label of the flower. This is an image classification problem. 
The code was executed on google colab, as it is easier to access TPU on google colab. The code needs to be slightly changed when running google colab from kaggle, with regard to the input path.
Few of the parameters that can be changed to check for performance are:
Epoch, Batch size.
The dataset provides data for 4 different image specifications: 192x192, 224x224, 331x331, 512x512.
If you want to run the code for different files, then you should edit the GCS_PATH to read the correct inout file path and also change the parameter IMAGE_SIZE to have the correct inout specification.
Once these changes are done, then we can run the code to predict the images of the flowers. 
