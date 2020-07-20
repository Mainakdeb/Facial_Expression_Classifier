# Facial_Expression_Classifier



## Real-time classification from webcam feed:
![](webcam-sample.gif)

## Classifying still images:
<img src="https://github.com/Mainakdeb/Facial_Expression_Recognition-/blob/master/Screenshots/PyTorch_Predictions.png" width="510">



A Deep Learning model to recognise facial expressions.

This uses OpenCV’s Haar cascades to detect and extract
a face region from a webcam video feed, then classifies
it using a trained CNN.

### Resources used:
* [FER_2013_Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
* [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
* [Tutorial for using Haar Cascades](https://www.youtube.com/watch?v=88HdqNDQsEk)


## To Do
1. ~~Balance the dataset.~~
2. ~~Augment training data to increase overall robustness of the model.~~
3. ~~Implement the whole thing using PyTorch.~~
