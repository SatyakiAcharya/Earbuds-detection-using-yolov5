# 🎧 Earbuds Detection Using YOLOv5
## Overview
This project demonstrates how to use the YOLOv5 object detection model to detect earbuds in images. Leveraging transfer learning, I have extended the COCO dataset by adding a custom class called earbuds, labeled using the LabelImg tool. The goal is to train a model that accurately identifies earbuds in real-world scenarios.

The project utilizes **PyTorch**, **YOLOv5**, and essential libraries like **NumPy** and **Matplotlib** to visualize and train the model.

## 🛠 Key Features
- Custom Dataset: Extended the COCO dataset by adding an "earbuds" class.
- Transfer Learning: Fine-tuned a pre-trained YOLOv5 model for earbuds detection.
- Real-Time Detection: The model can detect earbuds in images or video streams.
- Data Augmentation: Enhanced model performance with augmentation techniques.
- Visualizations: Used Matplotlib to visualize the detection results.

## 🧠 Technologies Used
- YOLOv5 for object detection
- PyTorch for deep learning and transfer learning
- NumPy for numerical computations
- Matplotlib for visualizing training metrics and results

## 🤖 Transfer Learning
The model was pre-trained on the COCO dataset and fine-tuned for detecting earbuds, using the power of transfer learning. By leveraging a pre-trained YOLOv5 model, we were able to significantly reduce training time while maintaining high detection accuracy.

## ✨ Future Improvements
- Real-Time Detection: Integrate the model into real-time video streams.
- More Classes: Extend the model to detect other small objects alongside earbuds.
