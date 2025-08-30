# Chili Detection using YOLOv8

This project is a deep learning application for **object detection** that identifies chili peppers in images.  
It uses **YOLOv8 (Ultralytics)** as the detection model and is trained on a dataset from [Roboflow](https://universe.roboflow.com/weri-unib/chili-jhxhz/dataset/11).  

The goal of this project is to build an efficient computer vision system that can detect and classify chili objects accurately, which can be useful for agricultural analysis, quality control, and automation.

---

## Features
- Pre-trained YOLOv8 model with transfer learning.  
- Dataset integration from Roboflow.  
- Real-time detection and prediction on custom images.  
- GPU acceleration support for faster training and inference.  
- Visualization of detection results with bounding boxes.

---

## Technologies Used
- **Python 3** – main programming language  
- **Google Colab** – environment with GPU acceleration  
- **Ultralytics YOLOv8** – object detection framework  
- **PyTorch** – deep learning backend  
- **OpenCV** – image preprocessing and visualization  
- **Roboflow** – dataset management and augmentation  
- **Matplotlib** – visualization of training results and metrics  

---

## How to Run
1. Open the notebook in **Google Colab**.  
2. Change the runtime to **GPU** for better performance.  
3. Install the dependencies:
   ```bash
   pip install ultralytics
