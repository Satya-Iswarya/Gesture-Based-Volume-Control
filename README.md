# Gesture-Based-Volume-Control
Gesture-Based Volume Control 🎛️🖐️

A computer vision-based project that allows users to control system volume using hand gestures. This project uses OpenCV, Mediapipe, and PyCaw to detect hand gestures and adjust the volume accordingly.

✨ Features

Real-time hand tracking using Mediapipe Hand Tracking.

Adjusts system volume based on hand distance.

Smooth volume transition for a better user experience.

Works with any webcam.

🛠️ Tech Stack

Python

OpenCV - For video processing.

Mediapipe - For hand tracking.

PyCaw - For controlling system volume.

🔧 Installation

1.Clone the repository:

  git clone https://github.com/Satya-Iswarya/Gesture-Based-Volume-Control.git
  cd gesture-volume-control
  
2.Install dependencies:

  pip install opencv-python mediapipe pycaw numpy
  
3.Run the script:

  python volume_control.py  

📌 How It Works

   The webcam captures the live feed.
   
   The Mediapipe Hand Tracking model detects hand landmarks.
   
   The distance between the thumb and index finger is calculated.
   
   The volume is adjusted based on this distance.
   
📷 Example

🤏 Fingers Close → Volume Low

🖐️ Fingers Apart → Volume High

📜 License

    This project is open-source under the MIT License.

🤝 Contributing

   Contributions are welcome! Feel free to fork the repository and submit a pull request.
