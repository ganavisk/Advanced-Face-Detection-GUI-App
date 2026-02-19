# Advanced-Face-Detection-GUI-App
A Tkinter-based Face Detection GUI application using OpenCV Haar Cascade for real-time image and video face detection with customizable detection parameters.
Advanced Face Detection GUI Application

A powerful and user-friendly Face Detection Desktop Application built using Python, Tkinter, and OpenCV.

This application allows users to detect faces in:

🖼 Images

🎥 Live Webcam

📁 Video Files

It also provides customizable detection settings for improved accuracy.

🚀 Features

✅ Image face detection
✅ Real-time webcam face detection
✅ Video file processing
✅ Adjustable detection parameters
✅ Save processed images
✅ Multi-tab GUI interface
✅ Settings stored in JSON file
✅ Thread-based video processing

🛠 Technologies Used

Python

OpenCV

Tkinter

Pillow (PIL)

NumPy

JSON

Threading

📂 Project Structure
Advanced-Face-Detection-GUI-App/
│
├── face_detection.py
├── face_detection_settings.json
├── README.md
└── requirements.txt

⚙️ Installation Guide
1️⃣ Clone Repository
git clone https://github.com/yourusername/Advanced-Face-Detection-GUI-App.git
cd Advanced-Face-Detection-GUI-App

2️⃣ Install Dependencies
pip install -r requirements.txt


Or manually:

pip install opencv-python pillow numpy

3️⃣ Run the Application
python face_detection.py

🎯 How It Works
🖼 Image Processing Tab

Upload image

Click Detect Faces

Faces are highlighted using bounding boxes

Save processed image

🎥 Video Processing Tab

Enter:

0 → For webcam

Or video file path

Start processing

Real-time face detection

Stop anytime

⚙ Settings Tab

Adjust:

Scale Factor

Minimum Neighbors

Minimum Face Size

Settings are saved automatically in:

face_detection_settings.json

🧠 Face Detection Algorithm

The application uses:

Haar Cascade Classifier

Pre-trained frontal face detection model from OpenCV

Grayscale image conversion

Multi-scale detection

📸 Sample Output

Faces are detected and marked using blue rectangular bounding boxes in both image and video streams.

🔥 Future Improvements

Deep Learning-based face detection (DNN)

Face recognition integration

Emotion detection

Face mask detection

GUI enhancements

Model switching option

👩‍💻 Author

Ganavi SK
Computer Science Student
Machine Learning & Computer Vision Enthusiast

📜 License

This project is open-source and available under the MIT License.

📦 requirements.txt Content

Create a file named requirements.txt and paste:

opencv-python
pillow
numpy
