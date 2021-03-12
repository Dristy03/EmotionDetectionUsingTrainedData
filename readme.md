# Emotion Detection Using DeepFace

In this project, emotion detection from images is done without using  predefined untrained dataset CSV file. I have used DeepFace Library for trained dataset.A modern face recognition pipeline consists of 4 common stages: detect, align, represent and verify. Deepface handles all these common stages in the background. 

Deepface is a lightweight face recognition and facial attribute analysis (age, gender, emotion and race) framework for python. It is a hybrid face recognition framework wrapping state-of-the-art models: VGG-Face, Google FaceNet, OpenFace, Facebook DeepFace, DeepID, ArcFace and Dlib. The library is mainly based on Keras and TensorFlow.

https://github.com/serengil/deepface

## Packages and Library
- pip install opencv-python
- pip matplotlib
- pip deepface

 You can find the libraries in requirements.txt

 ## Usage
 Any images can be used for emotion detection. For that the desired image file has to be kept in the main project file. Next in the image url, you have to put the right image name with the right extension.


 img = cv2.imread('image url') 

 if your image name is happyface with an extension of png. Then you have to write: img = cv2.imread('happyface.png') and run the cell.

 Caution: You have to run each and every cell pressing shift+enter one by one in the serial they appear.



