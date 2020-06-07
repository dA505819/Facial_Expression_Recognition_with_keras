# Facial Expression Recognition with keras

Facial expression recognition model is build and trained using Convolutional Neural Network(CNN). The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). To detect faces in images OpenCV is used and draw a boudning box around them. After exporting the CNN, the trained model is served to a web interface using Flask and perform real-time facial expression recognition on video and image data or using a webcam. 


