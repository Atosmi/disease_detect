# Guava Detection and Disease Prediction using YOLOv5 on Raspberry Pi 3

This project aims to implement YOLOv5, a popular object detection algorithm, to detect the size of guavas and predict if they are disease-free or not. The project is deployed on Raspberry Pi 3, making it an affordable and accessible solution for farmers and small-scale guava producers.

## Table of Contents

- [Installation]
- [Usage]
- [Dataset]
- [Model Training]
- [Deployment on Raspberry Pi 3]
- [Contributing]


## Installation

To use this project, clone the repository to your local machine:

```

git clone https://github.com/Atosmi/disease_detect.git
```


This project requires the following dependencies:

- Python 3.6 or later
- PyTorch 1.7 or later
- OpenCV 4.5 or later
- NumPy
- SciPy
- Matplotlib

You can install these dependencies by running the following command:

```
pip install -r requirements.txt
```


## Usage

To run the project, navigate to the project directory and run the following command:

```
python rasp_predict.py
python OpenCV.py
python mail_demo.py
```


This will detect the guavas in the specified image and predict if they are disease-free or not. The output image will be mailed to given email address.

## Dataset

The dataset used in this project consists of images of guavas with annotations for size and disease status. The dataset is sourced from COCO dataset. Download it separately.

## Model Training

To train the YOLOv5 model on the guava dataset, run the following command:

```
python rasp_main.py
```


This will train the model on the guava dataset using the YOLOv5s architecture.

## Deployment on Raspberry Pi 3

To deploy the project on Raspberry Pi 3, follow these steps:

1. Install the dependencies listed in the requirements.txt file onto the Raspberry Pi 3.
2. Clone the project repository to the Raspberry Pi.
3. Connect a camera to the Raspberry Pi and ensure that it is working.
4. Run the `rasp_predict.py` script to detect guavas and predict disease status using the Raspberry Pi camera.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

