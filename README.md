# 🎙️ Speech and Emotion Recognition System

A machine learning-based system designed to recognize and classify human emotions (like Happy, Sad, Angry, etc.) from short live audio inputs. This project is aimed at analyzing vocal patterns and extracting meaningful features to detect emotional states with a real-time application focus.

---

## 🔍 Overview

This project takes a 10-second audio input and classifies it into one of five primary emotions using acoustic features and a trained Support Vector Machine (SVM) classifier. It also features fake voice detection and a Flask-based user interface for real-time emotion prediction.

---

## 🧠 Key Features

- 🎧 Live 10-second voice input recording
- 📊 Emotion classification using SVM
- 🔊 Acoustic feature extraction (MFCC, Chroma, Mel)
- 🧪 Noise cancellation & fake voice detection
- 🌐 Flask web interface for interactive predictions
- 📈 Accuracy: 77% (Male), 75% (Female)

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: NumPy, Pandas, SciPy, scikit-learn, LibROSA, Matplotlib, TextBlob  
- **Web Framework**: Flask  
- **Tools**: Jupyter Notebook, VS Code

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/speech-emotion-recognition.git
   cd speech-emotion-recognition
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Start the Flask app:
   ```bash
   python app/main.py
4. Record your voice and predict emotion!


## 🚧 Future Enhancements
	•	Mobile app integration
	•	Support for multilingual input
	•	Upgrade to deep learning models (CNN/RNN)
	•	Emotional intensity scoring
