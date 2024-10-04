# Object Detection and Audio Description from Webcam Capture

This project captures an image using the webcam, performs object detection using the [DETR (DEtection TRansformer)](https://huggingface.co/facebook/detr-resnet-50) model, and generates an audio description of the detected objects.
The project is implemented in Python and designed to run in a Google Colab environment.

## Project Overview
This project demonstrates how to:
1. Capture an image using the webcam.
2. Use the DETR (DEtection TRansformer) model to detect objects in the captured image.
3. Generate a real-time audio description of the detected objects using Google Text-to-Speech (gTTS).
4. Display the image with bounding boxes around the detected objects.

The object detection model is based on Facebook's [DETR ResNet-50](https://huggingface.co/facebook/detr-resnet-50) from Hugging Face.

## Features
- **Webcam Image Capture**: Capture an image using the device's webcam.
- **Object Detection**: Detect objects in the captured image with bounding boxes using the DETR model.
- **Audio Description**: Generate a spoken description of the objects detected using gTTS (Google Text-to-Speech).
- **Real-Time Feedback**: Display the processed image and play the audio description directly in Google Colab.

## Installation

Follow these steps to set up the project environment in Google Colab:

### 1. Clone or download the repository
```bash
git clone https://github.com/BHUVANESWARI-2005/Deep_Learning-model-for-Visually-Impaired.git
