# Facial-Expression-Recognition

Internal steps of the project:

 * Identify face in the image/video/live stream using Haarcascade frontal face detection.
 * Create bounding box around the face.
 * Recoginize the expression.
 * Label the expression.


Convolutional Neural Network Model
![model](https://user-images.githubusercontent.com/9932479/133896074-0a758aa6-9eed-4595-b181-b6aba5927f51.png)


### How to use
* Default using camera for live expression detection.
* Can change to video or other sources in init method of camera.py, **self.video = cv2.VideoCapture(0) #'videos/facial_exp.mkv'**


## References:

* Coursera Guided Project: https://www.coursera.org/learn/facial-expression-recognition-keras/home/welcome
* Emotion FER Dataset: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data
