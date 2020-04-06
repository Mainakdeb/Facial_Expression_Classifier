# Facial_Expression_Recognition
A Deep Learning model to recognise facial expressions.

This uses OpenCV’s Haar cascades to detect and extract
a face region from a webcam video feed, then classifies
it using the CNN model.

### Resources used:
* [FER_2013_Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
* [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
* [Tutorial for using Haar Cascades](https://www.youtube.com/watch?v=88HdqNDQsEk)

## Steps:
1. Download the resources, clone this repo. Save both in the same directory.
2. Either train the model locally or load the existing model.
3. Test out the model using the sample images.
4. Snap photos using the webcam.
5. Pass it through the model.
6. See the results.
7. Run one of the last two cells to run the model with live webcam video feed.

### Warning: 
The last cell might crash the kernel.

## To Do
1. Balance the dataset.
2. Augment training data to increase overall robustness of the model.

## Notes:
* The model has an accuracy of around 64% on the validation set.



## Screenshots:

![Alt text](https://github.com/Mainakdeb/Facial_Expression_Recognition-/blob/master/Screenshots/Screenshot_1.png)

![Alt text](https://github.com/Mainakdeb/Facial_Expression_Recognition-/blob/master/Screenshots/Screenshot_2.png)

![Alt text](https://github.com/Mainakdeb/Facial_Expression_Recognition-/blob/master/Screenshots/Screenshot_3.png)


