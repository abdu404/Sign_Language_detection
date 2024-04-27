# Sign Language Detection

This project demonstrates sign language detection using TensorFlow for deep learning and OpenCV for real-time image processing. The model is based on the VGG16 architecture pretrained on the ImageNet dataset.

## Requirements

- Python 3.x
- Tensorflow
- opencv
- Anaconda (optional but recommended)

## Installation

1. Clone the repository to your local machine:
git clone https://github.com/abdu404/Sign_Language_detection.git


2. Navigate to the project directory:
cd sign_language_detection

## Data Preparation

1. Create a folder named `SignL` in the project directory.
2. Inside the `SignL` folder, create a folder named `Data`.
3. Organize your sign language data into subfolders for each class (e.g., A, B, C) within the `Data` folder.
4. Each subfolder should contain images of the corresponding sign.

## Running the Code

1. Open Jupyter Notebook:
jupyter notebook


2. Run the provided Jupyter Notebook cells in order:
- Cell 1: Data Preparation
- Cell 2: Model Training
- Cell 3: Model Evaluation and Saving
- Cell 4: Inference with Webcam

