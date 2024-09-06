# hbN-crack-detection YOLOv8n Model Inference

This repository contains a Python script for running inference using a pre-trained YOLOv8n model. It is designed to process images and detect features with bounding boxes, segmentation masks, pose keypoints, and classification probabilities. This setup is intended to be easily reproducible for researchers interested in testing and extending the model's capabilities.

## Prerequisites

To run this script, you will need:
- Python 3.x
- `ultralytics` Python package
  - Install this package using the command: `pip install ultralytics`

## Repository Structure

- `weights/`: Folder containing the YOLO model weights.
- `sample_images/`: Folder containing images to test the model.
- `results/`: Folder where the output images will be saved.
- `inference.py`: Script to perform inference.

Ensure that you clone the repository and maintain this structure for seamless execution.

## Setup

1. **Clone the Repository**:
   - Clone this repository to your local machine using `git clone <repository-url>`.

2. **Prepare the Environment**:
   - Install the required Python package: `pip install ultralytics`.

3. **Add Your Data**:
   - Place your pre-trained model weight file (e.g., `best_223.pt`) in the `weights` directory.
   - Ensure that the `sample_images` directory contains the images you want to process.

## Running the Script

Navigate to the project directory and run the script using the following command:

```bash
python inference.py
