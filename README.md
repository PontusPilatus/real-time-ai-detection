# Real-Time Emotion, Age, and Gender Detection

## Projektbeskrivning

Detta projekt använder djupinlärning för att i realtid detektera och klassificera känslor, ålder och kön från ansiktsbilder via en webbkamera. Modellerna har tränats på välkända dataset och används för att analysera och visa prediktioner i realtid.

## Dataset

- **Emotion Detection**: [Face Expression Recognition Dataset](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset)
  - Detta dataset innehåller bilder av ansiktsuttryck som kategoriseras i olika känslor, inklusive glädje, ilska, rädsla, överraskning, sorg, avsky och neutralitet.
  
- **Age and Gender Detection**: [UTKFace Dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new)
  - Detta dataset innehåller bilder av ansikten med märkta åldrar och kön, vilket gör det möjligt att träna modeller för att förutsäga en persons ålder och kön baserat på deras ansiktsdrag.

## Funktioner

- **Realtidsdetektering**: Använd webbkamera för att analysera och visa ålder, kön och känslor på skärmen.
- **Stabilisering av förutsägelser**: Genomsnittliga förutsägelser över flera bildrutor för att undvika hoppiga resultat.
- **Anpassningsbar UI**: Resultaten visas med text och färgkodad bakgrund för att förbättra läsbarheten.

## Installation

För att komma igång, klona detta repository och installera nödvändiga bibliotek:

```bash
git clone https://github.com/ditt-användarnamn/real-time-ai-detection.git
cd real-time-ai-detection
pip install tensorflow keras opencv-python numpy matplotlib seaborn
