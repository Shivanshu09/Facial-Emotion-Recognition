# Facial-Emotion-Recognition
model.py: It is the main model. I've made a CNN Model with 4 Convolutional Layers ( Experimental Approach )
Below 4 I encountered Underfitting,
Above 4 accuracy started decreasing because of Overfitting.

test.py: It is the file that helps to detect facial emotion based on live video stream generated through webcam.

The har.xml file is the Harr Casscade Classifier Algorithm.

Dataset:
For the dataset you can look for FER2013 on kaggle. If you couldn't find it, feel free to contact me. I'll provide a Drive link.

For taining the model:
I've trained the model by creating a virtual gpu enviornment using Tensorflow_gpu.
