# Facial Expression Recognition with keras

Facial expression recognition model is build and trained using Convolutional Neural Network(CNN). The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). To detect faces in images using OpenCV with an accuracy achieved is 0.6456 and draw a bounding box around them. The trained model is served to a web interface using Flask and perform real-time facial expression recognition on video and image data or using a webcam. 

![Sad](https://github.com/dA505819/Facial_Expression_Recognition_with_keras/blob/master/Images/Sad.PNG)

![Neutral](https://github.com/dA505819/Facial_Expression_Recognition_with_keras/blob/master/Images/Neutral.PNG)

![Happy](https://github.com/dA505819/Facial_Expression_Recognition_with_keras/blob/master/Images/Happy.PNG)

![Fear](https://github.com/dA505819/Facial_Expression_Recognition_with_keras/blob/master/Images/Fear.PNG)

## Using Webcam

Webcam was also used by changing the code in _camera.py_ file by 
```
self.video = cv2.VideoCapture(0)
```

