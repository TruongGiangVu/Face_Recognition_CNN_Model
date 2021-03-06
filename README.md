# Face_Recognition_CNN_Model
Using CNN Model for face recognition.

Python language.

## Dataset 
- Local Faced in the Wild (lfw)
- 13233 face images, 5749 people
- Link download: http://vis-www.cs.umass.edu/lfw/

## Preprocessing
- Using HaarCascades in OpenCV for extracting faces from images.
- Using Dlib to detect 68 landmarks on faces and extract parts.
- Using AlignDlib to align faces.

## Build CNN Model
- Using Sequential, Keras model.
- We build CNN Model with:
  * 4 Conv2D layers, 4 MaxPooling2D layers, 1 Dropout, 1 Flatten and 1 Dense layer.
  * Activation include Relu and softmax.
  * Loss function: categorical_crossentropy, optimizer: adam, metrics: accuracy.

## Get started
- Library: numpy, matplotlib, pandas, tensorflow, glob, os, tqdm, time, datetime.
- Link google colab: https://colab.research.google.com/drive/1aFVXQeK7DSoIFWG4i4Xkxlubzx-4bmAH#scrollTo=2ZVlioBZDYol
- Run file "Face_CNN_Model.ipynb".
