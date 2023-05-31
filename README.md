# codeclause_mask_detector
"Real-Time Face Mask Detection using MobileNetV2" .his project aims to detect face masks in real-time using the MobileNetV2 architecture. By leveraging deep learning techniques, the system identifies whether individuals are wearing masks or not.



# Real-Time Face Mask Detection using MobileNetV2

This project aims to detect whether a person is wearing a face mask in real-time using the MobileNetV2 architecture. The trained model can be used to analyze video streams or webcam input and provide immediate feedback on mask usage.

## Prerequisites

- Python 3.7 or higher
- TensorFlow 2.x
- OpenCV
- NumPy
- Matplotlib (for visualization)

## Installation

1. Clone the repository:
2. Install the required dependencies:

## Dataset

The model has been trained on a custom face mask dataset consisting of images with and without face masks. Unfortunately, we are unable to provide the dataset directly, but you can use your own dataset or find open-source datasets online for training the model.

## Training

To train the face mask detection model, follow these steps:

1. Ensure you have the dataset in the appropriate format (organized in separate folders for mask and no mask images).

2. Open the `train.py` file and modify the necessary parameters like dataset directory, batch size, and number of epochs.

3. Run the training script:
4. 4. The trained model and weights will be saved in the `models/` directory.

## Usage

To use the trained model for real-time face mask detection, follow these steps:

1. Connect a webcam to your computer or ensure that your video stream is accessible.

2. Open the `classify.py` file and modify the confidence threshold for face detection if needed.

3. Run the classification script:
4. 4. A video stream window will open, displaying live webcam footage with bounding boxes and labels indicating mask presence.

## Results

The trained model achieved an accuracy of X% on the validation set. The precision, recall, and F1 score were also calculated, achieving X, X, and X, respectively.

This project is done by Harika Bagadhi 
