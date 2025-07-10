# Personal ID Reader using YOLO & EasyOCR

This repository contains a complete pipeline for detecting and reading information from personal identification documents using YOLOv8 and EasyOCR.

---

## 🚀 Features

- **YOLOv8 Object Detection**: Trains a model to locate key regions in ID cards.
- **EasyOCR Text Extraction**: Reads text from detected regions accurately.
- **Dataset Integration**: Uses Roboflow for dataset management and augmentation.
- **Evaluation and Testing**: Visualizes predictions and extracts data with bounding boxes.

---

## 🧰 Requirements

Install the required Python packages using pip:

```bash
pip install easyocr
pip install ultralytics
pip install roboflow
```

---

## 📁 Project Structure

```
YOLO_OCR_Personal_ID_Reader.ipynb   # Main notebook for training and testing
README.md                           # Project description and setup
```

---

## 🧪 How to Use

1. Clone the repository.
2. Open the notebook `YOLO_OCR_Personal_ID_Reader.ipynb`.
3. Follow the steps:
   - Install dependencies
   - Load and preprocess data
   - Train the YOLO model (via Roboflow/Ultralytics)
   - Use EasyOCR to extract text from ID fields
   - Visualize and evaluate results

---

## 📦 Use Cases

- Digital onboarding (KYC)
- Identity validation systems
- Automated data entry from physical ID cards

---

## 📄 License

MIT License.

---

## 🙌 Acknowledgements

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- [EasyOCR](https://github.com/JaidedAI/EasyOCR)
- [Roboflow](https://roboflow.com)

