# HANDIFY ✋  
## Real-Time Sign Language to Text Conversion System

Handify is a real-time Sign Language Recognition (SLR) system that converts American Sign Language (ASL) hand gestures into readable text using Computer Vision and Machine Learning.

The project is designed to bridge the communication gap between deaf or hard-of-hearing individuals and the general population by providing an efficient, lightweight, and accessible solution that works on standard consumer hardware without requiring specialized gloves or GPUs.

---

## 🚀 Features

- Real-time ASL gesture recognition
- Detects 21 hand landmarks using MediaPipe
- Converts hand gestures into readable text instantly
- Lightweight and efficient system
- Works using a standard webcam
- No GPU or external hardware required
- Supports ASL alphabets (A–Z) and digits (0–9)
- Real-time performance of around 15–20 FPS

---

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- Scikit-learn
- Random Forest Classifier
- NumPy
- PyQt5

---

## 📌 System Workflow

1. Capture real-time video from webcam  
2. Convert frame from BGR to RGB  
3. Detect hand using MediaPipe  
4. Extract 21 hand landmarks  
5. Generate normalized spatial features  
6. Predict gesture using Random Forest classifier  
7. Display recognized text on screen  

---

## 🧠 Machine Learning Model

The project uses a **Random Forest Classifier** trained on approximately **10,000–11,000 labeled ASL gesture samples**.

### Model Details

| Parameter | Value |
|---|---|
| Algorithm | Random Forest |
| Dataset Size | ~10,000–11,000 |
| Number of Classes | ~38 |
| Feature Type | Normalized Landmark Coordinates |
| Input Features | 42 |

---

## 📊 Performance

| Lighting Condition | Accuracy | FPS |
|---|---|---|
| Optimal Lighting | 91.7% | 18–20 |
| Moderate Lighting | 88.4% | 18–20 |
| Low Light | 76.0% | 15–18 |

---

## 💡 Advantages

- Cost-effective solution
- Easy to deploy
- Real-time interaction
- No wearable sensors needed
- Accessible for differently-abled individuals
- Lightweight compared to deep learning approaches

---

## ⚠️ Limitations

- Currently supports only static gestures
- Accuracy decreases in extremely low-light environments
- Does not support two-handed gestures
- Facial expressions and non-manual cues are not included

---

## 🔮 Future Scope

- Dynamic gesture recognition using LSTM/RNN
- Mobile application deployment
- NLP integration for sentence formation
- Multi-hand gesture support
- Better low-light robustness

---

## 👨‍💻 Team Members

- Saumya  
- Vansh Sihania  
- Vidit Sharma  
- Sumit Chauhan  

### Guided By
**Ms. Anjali Chauhan**  
KIET Group of Institutions, Ghaziabad
