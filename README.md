# Yolov5-Boat-Detection-Using-Satellite-Imagery
 A YOLOv5-based project for detecting boats in images and videos. Supports real-time inference, custom datasets, and visual output with bounding boxes. Ideal for maritime surveillance and boat detection tasks.



# Boat Detection using YOLOv5

This project implements **YOLOv5** (You Only Look Once v5) for detecting boats in images and video streams. The model is designed for real-time boat detection and can be used in applications like maritime surveillance, waterway monitoring, and coastal analysis.

## 🚀 Features
- **Real-time object detection**: Detects boats in images and videos with bounding boxes and confidence scores.
- **Custom Dataset Support**: Can be trained on custom datasets or use pre-trained weights for detection.
- **Easy Setup**: Simple Python scripts to run detection on your own images or videos.
- **Hardware Acceleration**: Supports **GPU** (T4, A100, etc.) and **TPU** for faster inference.

## 📂 Dataset
- Custom boat datasets can be used for training the model.
- The model is also compatible with publicly available boat datasets or pre-trained weights.

## 📊 Evaluation Metrics
- **Precision**, **Recall**, **F1-Score**, and **mAP** for evaluating detection performance.
- **Confusion Matrix**: Includes metrics like True Positives (TP), False Positives (FP), True Negatives (TN), and False Negatives (FN).

## 🛠 Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/boat-detection-yolov5.git
cd boat-detection-yolov5
