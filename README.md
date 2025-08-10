# task2-

This project is a real-time face detection application built with Python and OpenCV. It uses a pre-trained Haar Cascade Classifier (haarcascade_frontalface_default.xml) to detect human faces from a live webcam feed. The program opens the camera, continuously captures video frames, converts them to grayscale for faster processing, and applies face detection using the detectMultiScale method. When a face is detected, the system draws a green rectangle around it and displays the live feed in a window. The application runs in real time and can be closed by pressing the Q key.
