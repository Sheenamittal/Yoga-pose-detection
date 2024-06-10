This project demonstrates how to use MediaPipe to perform pose estimation and classification on images and video streams. MediaPipe provides efficient and accurate pose detection, which can be used for various applications such as fitness tracking, gesture recognition, and more.

Setup
Install Required Libraries:
Ensure you have the necessary Python libraries installed. You can install them using pip:
pip install opencv-python mediapipe matplotlib

Initialize MediaPipe Pose:
MediaPipe's Pose class is used for detecting human poses. You can configure it with parameters like static_image_mode, min_detection_confidence, and model_complexity.

Usage
1.	Pose Detection on Images: Read an image, process it using MediaPipe, and visualize the detected landmarks.
2.	Pose Detection on Video: Use the webcam to perform real-time pose detection. The frames are processed, landmarks are drawn, and the frames per second (FPS) are displayed.
3.	Pose Classification: Classify poses based on the angles between specific landmarks. Define a function to calculate angles and another to classify the pose.
