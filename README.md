~~--__Vehicle Detection__--~~🚗

__Overview__:
This project is designed to detect and track vehicles in real-time using computer vision and machine learning techniques. It utilizes OpenCV and pre-trained deep learning models to identify vehicles from video streams or static images.

__Table of Contents__:
1.Features
2.Project Structure
3.Installation
4.Usage
5.Results

__Features__:
1. Real-time vehicle detection using OpenCV and deep learning.
2. Supports both video and image input.
3. Visualizes bounding boxes around detected vehicles.


__Project Structure__:

vehicle_detection/
├── data/                 # Dataset and pre-trained models
├── models/               # Saved models and training scripts
├── src/                  # Source code for processing and prediction
│   ├── detect_vehicle.py # Vehicle detection code
│   ├── process_video.py  # Code for processing video input
│   └── utils.py          # Helper functions
├── notebooks/            # Jupyter notebooks for exploration
├── requirements.txt      # Dependencies
└── README.md             # Project documentation

~~ __Installation__ ~~

__Prerequisites__:
1.Python 3.x
2.Git

~~ __Setup__ ~~

__Clone the repository__:
git clone https://github.com/Hrishichaudhary/Vehicle-Detection.git
cd Vehicle-Detection

__Install dependencies__:
-------pip install -r requirements.txt

~~ __Usage__ ~~

__Running Vehicle Detection__:
--------To detect vehicles in a video:- python src/detect_vehicle.py --input_video path_to_video.mp4

__Processing Images__:
-----To detect vehicles in an image:- python src/detect_vehicle.py --input_image path_to_image.jpg

__Jupyter Notebooks__:- Explore notebooks/ for detailed analysis and model testing.

