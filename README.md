# COVID-19-Image-Detection

Here, I have implemented two different types of models that classify an X-ray image into three categories: Normal, Viral Pneumonia and COVID-19.
You can find the dataset [here](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset).

It contains around 137 cleaned images of COVID-19 and 317 in total containing Viral Pneumonia and Normal Chest X-Rays structured into the test and train directories.

We have downloaded this dataset from Kaggle and worked on it on the Google Colab Platform

It is a simple directory structure branched into test and train and further branched into the respective 3 classes which contains the images.

Model 1 is a single layered model, which is a CNN model with 4 convolution layers, 4 Pooling and 4 Neural Network layers.

While Model 2 is a two layered model, where each layer is a CNN model with 4 convolution layers, 4 Pooling and 4 Neural Network layers.
THe first layer classifies the image as Normal or Abnormal, and the second layer further classifies an Abnormal image as either COVID-19 or Viral Pneumonia.

Model 1 gives a test accuracy of 91% while Model 2 gives a test accuracy of 87%
