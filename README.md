# Facial Expression Recognition with Keras

Facial expression recognition model is build and trained using Convolutional Neural Network(CNN). The data consists of 48 x 48 pixel grayscale images of face. The objective is to classify each face based on the emotion expressed in the facial expression into one of seven categories (0 = Angry, 1 = Disgust, 2 = Fear, 3 = Happy, 4 = Sad, 5 = Surprise, 6 = Neutral). Faces are detected in videos using OpenCV with an accuracy of 0.6456 and drawing a bounding box around them. The trained model is served to a web interface using Flask and perform real-time facial expression recognition on video & image data or using a webcam. 

![Sad](https://github.com/dA505819/Facial_Expression_Recognition_with_keras/blob/master/Images/Sad.PNG)

![Neutral](https://github.com/dA505819/Facial_Expression_Recognition_with_keras/blob/master/Images/Neutral.PNG)

![Happy](https://github.com/dA505819/Facial_Expression_Recognition_with_keras/blob/master/Images/Happy.PNG)

![Fear](https://github.com/dA505819/Facial_Expression_Recognition_with_keras/blob/master/Images/Fear.PNG)

## Using Webcam

Webcam is used by changing the code in the **camera.py** file:
```
self.video = cv2.VideoCapture(0)
```

