# 🎵 Human Emotion Detection with Music Recommendation

This project detects human emotions from facial images using a pre-trained `.h5` model and recommends songs based on the detected mood. It combines computer vision, deep learning, and music recommendation via the Spotify API.

---

## 🚀 Tech Stack

### 🎯 Backend
- **Flask** – Web server and API handler.
- **Spotify API** – Fetches and recommends songs based on the detected emotion.
- **TensorFlow/Keras** – Loads and runs the pre-trained emotion detection model.

### 🎯 Model Creation
- **OpenCV** – Image processing and face detection.
- **NumPy** – Numerical operations.
- **Pandas** – Data manipulation.
- **Matplotlib** – Visualization and model evaluation.
- **TensorFlow/Keras** – Model building and training.

---
## 🎧 How It Works
### 🔍 Emotion Detection
- Accepts a test image.
- The .h5 model predicts the emotion (e.g., happy, sad, angry, etc.).

## 🎵 Music Recommendation
- Based on the predicted emotion, the app queries the Spotify API to fetch songs that match the user's mood.
