# Facial_Expression_Recognition

<img src="https://github.com/Mainakdeb/Facial_Expression_Recognition-/blob/master/Screenshots/PyTorch_screenshot.png" width="510">


A Deep Learning model to recognise facial expressions.

This uses OpenCV’s Haar cascades to detect and extract
a face region from a webcam video feed, then classifies
it using the CNN.

I'm trying to implement the same using PyTorch, check out the colab notebook. I'll delete the keras notebook once the PyTorch version is done.

* [Colab Notebook (PyTorch)](https://colab.research.google.com/drive/1mjbN_x_6SxZkj4_q_3Thcb-MWVnDTysB)
* [View Keras notebook in NBViewer](https://nbviewer.jupyter.org/github/Mainakdeb/Facial_Expression_Classification/blob/master/Expression_Detector_alpha.ipynb)


### Resources used:
* [FER_2013_Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
* [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
* [Tutorial for using Haar Cascades](https://www.youtube.com/watch?v=88HdqNDQsEk)
* [Reference article for classifying espressions (with 57% accuracy)](http://sefiks.com/2018/01/01/facial-expression-recognition-with-keras/)



## To Do
1. ~Balance the dataset.~
2. ~Augment training data to increase overall robustness of the model.~
3. Implement the whole thing using PyTorch.
