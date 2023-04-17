# EmotionRecognition

## Description

EmotionRecognition is a Python-based deep learning project that aims to recognize facial expressions and classify them into different emotions using Convolutional Neural Networks (CNNs). The project provides an end-to-end solution for emotion recognition from images or real-time video streams.

## Features

- Pre-trained CNN models for emotion recognition
- Real-time emotion recognition from webcam or video files
- Image-based emotion recognition
- Easy-to-use API for integrating into other projects
- Modular and extensible architecture
- Supports multiple emotions classification, including but not limited to: happy, sad, angry, surprise, disgust, fear, neutral

## Installation

To use EmotionRecognition, please follow these steps:

1. Clone the repository:

git clone https://github.com/SryNext/EmotionRecognition.git

2. Install the required dependencies:

pip install -r requirements.txt

3. Download the pre-trained model weights:

[Download Model Weights](https://drive.google.com/file/d/1aBefY9T1zgJgZ-0F-yv-JVK-pQ-luhTW/view?usp=sharing) and place it in the `models` directory.

## Usage

### Image Emotion Recognition

To recognize emotions from an image, run the following command:

python image_emotion_recognition.py --image_path /path/to/image.jpg

### Real-time Webcam Emotion Recognition

To perform real-time emotion recognition from webcam, run the following command:

python webcam_emotion_recognition.py

### Real-time Video Emotion Recognition

To perform real-time emotion recognition from a video file, run the following command:

python video_emotion_recognition.py --video_path /path/to/video.mp4

### Emotion Recognition API

You can also use the EmotionRecognition API to integrate emotion recognition into your own projects. See `api.py` for more details.

## Contributing

Contributions to EmotionRecognition are welcome! Please refer to the [Contributing Guidelines](CONTRIBUTING.md) for more information.

## License

EmotionRecognition is released under the [MIT License](LICENSE).
