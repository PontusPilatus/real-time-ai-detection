# Real-Time Emotion, Age, and Gender Detection
# Realtids Känslor-, Ålders- och Könsigenkänning

A real-time computer vision application that detects faces and predicts age, gender, and emotions using deep learning models.

En realtidsapplikation för datorseende som detekterar ansikten och förutsäger ålder, kön och känslor med hjälp av djupinlärningsmodeller.

## Repository
```bash
git clone https://github.com/PontusPilatus/real-time-ai-detection.git
cd real-time-ai-detection
```

## Features / Funktioner
- Real-time face detection / Realtids ansiktsdetektion
- Age prediction (categorized into age ranges) / Åldersförutsägelse (kategoriserad i åldersgrupper)
- Gender prediction / Könsigenkänning
- Emotion detection (7 categories: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral) / Känslodetektion (7 kategorier: Arg, Avsky, Rädsla, Glad, Ledsen, Överraskad, Neutral)
- Smooth predictions using rolling averages / Utjämnade förutsägelser med rullande medelvärden
- Color-coded emotion display / Färgkodad känslodisplay

## Project Structure / Projektstruktur
```
├── models/
│   ├── age_gender_detection_model.keras
│   ├── improved_emotion_detection_model.keras
│   └── alternative_emotion_detection_model.keras
├── real_time_AI_detection.ipynb    # Main notebook for real-time detection
├── emotion_detection.ipynb         # Emotion detection development
└── age_gender_detection.ipynb      # Age/gender detection development
```

## Quick Start / Snabbstart
1. Open `real_time_AI_detection.ipynb` in Jupyter Notebook / Öppna `real_time_AI_detection.ipynb` i Jupyter Notebook
2. Run all cells in sequence / Kör alla celler i sekvens
3. The webcam window will open with real-time detection / Webbkamerafönstret öppnas med realtidsdetektion

## Requirements / Krav
- Python 3.x
- OpenCV (cv2)
- TensorFlow
- NumPy
- Pillow (PIL)
- Jupyter Notebook

## Model Information / Modellinformation
- Age/Gender Model: Predicts age (0-100) and binary gender / Ålders-/könsmodell: Förutsäger ålder (0-100) och binärt kön
- Emotion Model: Classifies 7 different emotional states / Känslomodell: Klassificerar 7 olika känslotillstånd
- Models are pre-trained and ready to use / Modellerna är förtränade och redo att användas

## Dataset Information / Datasetinformation
- **Emotion Detection**: Face Expression Recognition Dataset
  - Dataset containing facial expressions categorized into different emotions
  - Dataset som innehåller ansiktsuttryck kategoriserade i olika känslor
- **Age and Gender Detection**: UTKFace Dataset
  - Dataset with labeled ages and genders for facial images
  - Dataset med märkta åldrar och kön för ansiktsbilder

## Notes / Anteckningar
- Requires a webcam for real-time detection / Kräver en webbkamera för realtidsdetektion
- GPU acceleration recommended but not required / GPU-acceleration rekommenderas men krävs inte
- Press 'Q' to quit the application when running / Tryck 'Q' för att avsluta applikationen när den körs
