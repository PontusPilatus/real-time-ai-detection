# Real-Time Emotion, Age, and Gender Detection

A real-time computer vision application that detects faces and predicts age, gender, and emotions using deep learning models.


## Repository
```bash
git clone https://github.com/PontusPilatus/real-time-ai-detection.git
cd real-time-ai-detection
```

## Features
- Real-time face detection
- Age prediction (categorized into age ranges)
- Gender prediction
- Emotion detection (7 categories: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral)
- Smooth predictions using rolling averages
- Color-coded emotion display

## Project Structure
```
├── models/
│   ├── age_gender_detection_model.keras
│   ├── improved_emotion_detection_model.keras
│   └── alternative_emotion_detection_model.keras
├── real_time_AI_detection.ipynb    # Main notebook for real-time detection
├── emotion_detection.ipynb         # Emotion detection development
└── age_gender_detection.ipynb      # Age/gender detection development
```

## Quick Start
1. Open `real_time_AI_detection.ipynb` in Jupyter Notebook
2. Run all cells in sequence
3. The webcam window will open with real-time detection

## Requirements 
- Python 3.x
- OpenCV (cv2)
- TensorFlow
- NumPy
- Pillow (PIL)
- Jupyter Notebook

## Model Information
- Age/Gender Model: Predicts age (0-100) and binary gender
- Emotion Model: Classifies 7 different emotional states
- Models are pre-trained and ready to use

## Dataset Information
- **Emotion Detection**: Face Expression Recognition Dataset
  - Dataset containing facial expressions categorized into different emotions

## Notes
- Requires a webcam for real-time detection
- GPU acceleration recommended but not required
- Press 'Q' to quit the application when running
