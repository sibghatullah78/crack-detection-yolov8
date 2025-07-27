YOLOv8 Crack Detection 🧠🔍
This repository contains a YOLOv8-based image segmentation project for detecting cracks in concrete structures using image masks.

🧪 Project Summary
The model is trained to detect and segment structural cracks in images using the YOLOv8 segmentation architecture. It uses labeled datasets with binary masks representing the crack regions.

📂 Contents
crackdetection.ipynb: Main Jupyter Notebook containing the complete crack detection pipeline including:

Dataset loading and preprocessing

YOLOv8 training

Inference on test images

Visualization of results

🚀 Tech Stack
Model: YOLOv8 (Segment variant)

Framework: Ultralytics YOLOv8

Language: Python

Notebook: Jupyter Notebook

Libraries:

OpenCV

NumPy

Matplotlib

Ultralytics

📸 Sample Output
Input Image	Predicted Crack Mask
Add input image here	Add output image here

(Optional) Add image files in a samples/ folder and update the table with correct paths.

🧰 How to Run
Clone the repository:

bash
git clone https://github.com/sibghatullah78/crack-detection-yolov8.git
Install dependencies:

nginx
pip install -r requirements.txt
Run the notebook:
Open crackdetection.ipynb in Jupyter and run all cells.

Make sure you have a GPU environment for training and testing YOLOv8 efficiently.

📈 Results
High IoU and precision in detecting crack segments

Real-time inference speed with YOLOv8

📌 Notes
Dataset should be in YOLOv8 segmentation format

Ensure your dataset has train, val, and test folders with proper annotations

📧 Author
Sibghat Ullah
📫 sibghatullah94958@gmail.com

📜 License
This project is open-source and available under the MIT License.
