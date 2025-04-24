# Human-Pose-Estimation-and-Danger-Detection
# Human Activity Danger & Safe Detection 

This project is designed to detect **human pose activity** in real-time and classify it as either **DANGEROUS** or **SAFE**, using a combination of **MediaPipe** for pose estimation and an **LSTM model** for sequence-based activity classification.

## Objective
Build a robust system that understands human movement patterns from video streams or live feeds, identifies activities, and classifies them into:
- **Safe**
- **Dangerous**

## Features
- **Pose Estimation with MediaPipe**  
  Efficient tracking of 33 body landmarks in real-time.

- **Temporal Modeling with LSTM**  
  A trained LSTM model processes sequences of poses to understand motion patterns over time.

- **Real-Time Prediction**  
  Instant activity detection and classification from video input.

- **Team Project**  
  Developed collaboratively with significant contributions from all group members.

## Tech Stack
- **MediaPipe** – Human pose detection  
- **TensorFlow / Keras** – LSTM-based activity recognition  
- **Python** – Data handling, preprocessing, and system integration  
- **OpenCV** – Video feed handling and display (if used)
  
## Activities Classified
Currently, the model distinguishes between actions such as:
- **Walking**
- **Sitting**
- **Jumping**
- **Fighting**  
These are then categorized into `SAFE` or `DANGEROUS` actions.

## Team Credits
This project is a joint effort by our team.  
**Special thanks to all members for their dedication, collaboration, and innovation.**
