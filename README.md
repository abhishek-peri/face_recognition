# face_recognition

dependencies :
1) python 2.7 or >
2) opencv >= 3.4
3) xmlwrite, xmlrd

List of things this repo currently does:

1) Performs face detection in the current frame and saves the detected face images into a user directory


instructions to capture the details of the user:

1) Clone the repository
2) have installed the above libraries using pip
3) run python dataset_capture.py
4) enter the user id when prompted(a numerical value will suffice like 1 or 2)
5) wait for the face data to be captured and saved in the newly created dataset folder

After asserting data is captured:

1) Create a new directory named 'training'
2) run python training_dataSet.py
3) run python recognizer.py

