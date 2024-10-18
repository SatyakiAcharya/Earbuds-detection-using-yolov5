#🎧 Earbuds Detection Using YOLOv5
Overview
This project demonstrates how to use the YOLOv5 object detection model to detect earbuds in images. Leveraging transfer learning, I have extended the COCO dataset by adding a custom class called earbuds, labeled using the LabelImg tool. The goal is to train a model that accurately identifies earbuds in real-world scenarios.

The project utilizes PyTorch, YOLOv5, and essential libraries like NumPy and Matplotlib to visualize and train the model.

#🛠 Key Features
Custom Dataset: Extended the COCO dataset by adding an "earbuds" class.
Transfer Learning: Fine-tuned a pre-trained YOLOv5 model for earbuds detection.
Real-Time Detection: The model can detect earbuds in images or video streams.
Data Augmentation: Enhanced model performance with augmentation techniques.
Visualizations: Used Matplotlib to visualize the detection results.
