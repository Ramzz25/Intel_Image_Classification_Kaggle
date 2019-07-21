# Intel_Image_Classification_Kaggle

Applying CNN on the Intel Image Classification data set available on kaggle

About Dataset:
Dataset has totally 6 different classes - mountain, glacier, street, buildings, sea, forest.
Each class has about 2100 images in .jpg format for training and about 470 images for test.
Link to download dataset :https://www.kaggle.com/puneet6060/intel-image-classification.

About Model:
Code was written and executed on google colab. #Page might crash sometimes due to higher use of RAM
Libraries like matplotlib and seaborn are used for visualisations.
This code uses libraries like tensorflow, cv to apply CNN to the available dataset.
Image is read from the directory using CV2 library and the CNN model is built using tensorflow.keras.

Test Accuracy of about 80% is achieved using this model.
