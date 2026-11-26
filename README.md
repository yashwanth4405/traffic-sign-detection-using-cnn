# Traffic Sign Detection Using CNN

## Project Overview
Traffic Sign Detection Using CNN is a computer vision project designed to detect and identify traffic signs from uploaded images. The system recognises different traffic signs, including speed limits, traffic lights, and stop signs.

## Features
- Upload traffic sign images.
- Detect traffic signs from uploaded images.
- Identify multiple traffic sign categories.
- Display prediction results with bounding boxes.
- Web-based interface using Flask.

## Technologies Used
- Python
- Convolutional Neural Networks (CNN)
- OpenCV
- NumPy
- Flask
- Ultralytics

## Traffic Sign Categories
The model is trained to recognise 15 classes:

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
│
├── app.py
├── new.py
├── trainall.py
├── data/
│   └── data.yaml
├── templates/
│   ├── index.html
│   └── results.html
├── static/
│   └── style.css
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yashwanth4405/traffic-sign-detection-using-cnn.git
```

Navigate to the project directory:

```bash
cd traffic-sign-detection-using-cnn
```

Install the required packages:

```bash
pip install flask ultralytics opencv-python numpy
```

## Model Setup

The trained model file `best.pt` is not included in this repository.

Place your trained model in the location configured in `app.py`, or update `TRAINED_MODEL_PATH` to match its actual location.

## Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

Upload a traffic sign image to view the detection results.

## GitHub Repository

https://github.com/yashwanth4405/traffic-sign-detection-using-cnn
