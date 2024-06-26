Hi everyone,
This is a simple freelance project that I made for a stealth startup. I have utilized the OpenCV library for face recognition and for liveness detection, I used a custom-trained convolutional neural network.
This project implements a real-time face recognition and liveness detection system using OpenCV, face_recognition, and a custom-trained liveness detection model. 
The system captures video frames from a webcam, processes them for liveness detection, and performs face recognition to identify known users.
The liveness detection model ensures that the system only recognizes faces from live persons and not from photographs or videos.
When a live person is detected, the system checks for face matches against a database of known users and displays the user's name if recognized, otherwise, it shows "LOCKED!". 
Additionally, the system displays "UNLOCK" if a known user is detected and liveness is confirmed.
The implementation leverages a convolutional neural network (CNN) for liveness detection and the face_recognition library for accurate face matching. 
The project setup includes loading the liveness model weights, reading known user data, and configuring the video capture. 
The main loop processes video frames for liveness and face recognition, updating the display with real-time results. 
This project is ideal for security applications where verifying the presence of live individuals is crucial.
