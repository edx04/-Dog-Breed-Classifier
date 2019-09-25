[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview
Thisproject was part of Udacity’s Deep learnig nanodegree 

In this project, I build a convolutional neural network (CNN) that can classify the breed of dog from any user-supplied image. If the image is of a human and not a dog, the algorithm will provide an estimate of the dog breed that is most resembling.
The code is written in Python 3 and Keras with Tensorflow backend all presented in Jupyter Notebook. I used AWS EC2 gpu instance for training the model.

Given an image of a dog, my algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. Along with exploring state-of-the-art CNN models for classification, I have made important design decisions about the user experience for our app. By completing this lab, I understood the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.


![Sample Output][image1]

# Datasets
- Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in this project's home directory, at the location `/dogImages`. 
- Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the home directory, at location `/lfw`.  




