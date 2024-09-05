## Face-Detection-and-Recognition
The idea is to introduce people to the concept of face detection in Python using the OpenCV library and
how it can be utilized to perform tasks like Facial recognition. The model has an accuracy of 99.38% on the
Labeled Faces in the Wild benchmark. 

Steps to run 
1. First run video read.py to check that your webcam is running or not.
2. Run face_detection.py to check that whether camera is able to capture your face or not, with the help of haar cascase classifier
3. Now, run face_data.py --> this will open up the camera and extract your face from video frames multiple time. Test and store faces of multiple people.
4. At last, run face_recognition.py --> this will detect your face from the dataset made and form a bounding box with you name writtern around your face.
