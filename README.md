# Face-Recognition
In order to perform face recognition with opencv i installed two additional libraries:-
1)dlib
2)face_recognition

So i have applied face recognition on the dataset it will:-
1) Create the 128-d embeddings for each face in the dataset
2) Use these embeddings to recognize the faces of the characters in both images and video streams

I have 6 files in the root directory:-
### search_bing_api.py
I used bing API to build a dataset
### encode_faces.py
Encodings 128-d  for faces are built with this script.
### recognize_faces_image.py
Recognize faces in a single image based on encodings from your dataset.
### recognize_faces_video.py
Recognize faces in a live video stream from your webcam and output a video.
### recognize_faces_video_file.py
Recognize faces in a video file residing on disk and output the processed video to disk. 
### encodings.pickle
Facial recognitions encodings are generated from your dataset.

# How to Run
Dataset of images is created with search_bing_api.py. we’ll run encode_faces.py  to build the embeddings. Then recognize_faces-image file by using encoding.pickle file . Then if you want to recognize face in video run recognize_faces_video_file.
