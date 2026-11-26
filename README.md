# Traffic Sign Detection Using CNN

## Project Overview
Traffic Sign Detection Using CNN is a computer vision project that detects and recognises traffic signs from uploaded images. It identifies different traffic signs, including speed limits, traffic lights, and stop signs.

## Features
- Upload traffic sign images.
- Detect traffic signs using a trained deep learning model.
- Recognise 15 different traffic sign categories.
- Display detected signs with bounding boxes.
- Web-based interface using Flask.

## Technologies Used
- Python
- CNN-based Deep Learning
- YOLOv8
- Flask
- OpenCV
- NumPy
- HTML
- CSS

## Traffic Sign Categories
The model supports 15 classes:

1. Green Light
2. Red Light
3. Speed Limit 10
4. Speed Limit 20
5. Speed Limit 30
6. Speed Limit 40
7. Speed Limit 50
8. Speed Limit 60
9. Speed Limit 70
10. Speed Limit 80
11. Speed Limit 90
12. Speed Limit 100
13. Speed Limit 110
14. Speed Limit 120
15. Stop

## Project Structure

```text
traffic_sign_detection/
├── app.py
├── new.py
├── trainall.py
├── data/
│   └── data.yaml
├── templates/
├── static/
└── README.md
```

## Model Training
The model is trained using the YOLOv8 Nano architecture with the following configuration:

- Model: YOLOv8n
- Epochs: 50
- Image Size: 640 × 640
- Batch Size: 16
- Number of Classes: 15

## Installation

Clone the repository:

```bash
git clone https://github.com/yashwanth4405/traffic-sign-detection-using-cnn.git
```

Navigate to the project:

```bash
cd traffic-sign-detection-using-cnn
```

Install dependencies:

```bash
pip install flask ultralytics opencv-python numpy
```

## Trained Model Setup

The trained model file (`best.pt`) is not included in this repository.

Place your trained model at:

```text
runs/train3/weights/best.pt
```

Alternatively, update the model path in `app.py`.

## Run the Application

```bash
python app.py
```

Open your browser:

```text
http://127.0.0.1:5000/
```

Upload a traffic sign image to view the detection results.

## Author

**Yashwanth**

GitHub: https://github.com/yashwanth4405
