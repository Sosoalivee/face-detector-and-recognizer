# 👤 Face Detection & Recognition System using OpenCV (FisherFaces)

This project implements a full face recognition pipeline using OpenCV. It collects face images, trains a recognition model using the **FisherFaceRecognizer**, and recognizes faces in real time from a webcam feed.

## 📸 Features

- Real-time face detection using Haar Cascades
- Dataset creation and automatic labeling
- Model training using FisherFaceRecognizer
- Real-time recognition with name and confidence display
- Logs unknown faces and saves image if unidentified for long
- 
##Step 1: Collect Face Data
sub_data = 'YourName'
Then run:
python collect_faces.py
This will create a folder in datasets/ and capture 100 face images.

Step 2: Train and Recognize Faces
Once dataset is ready, run:
python train_and_recognize.py
The model will:

Train using all face images in datasets/

Recognize faces in webcam feed

Display the name and confidence score

Save an image if an unknown person appears multiple times

📂 Files
create_datapy – for collecting face data

facerecognize.py – for training and recognition

haarcascade_frontalface_default.xml – Haar cascade XML for face detection

datasets/ – automatically created during face capture
