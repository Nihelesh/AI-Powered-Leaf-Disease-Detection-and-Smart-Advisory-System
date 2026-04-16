🌿 Next-Gen Plant Health Monitoring
AI-Powered Leaf Disease Detection & Smart Advisory System

📌 Overview

This project is an AI-based system that detects plant diseases from leaf images and provides intelligent advisory recommendations. It combines Computer Vision, Deep Learning, and Generative AI to deliver accurate and actionable insights for agriculture.

The system uses:

YOLOv8 for leaf detection
DenseNet-121 for disease classification
Google Gemini API for smart advisory

🚀 Features

📷 Upload leaf images
🎯 Automatic leaf detection (YOLOv8)
🌱 Multi-class disease classification (38 classes)
🤖 AI-generated advisory (treatment & prevention)
⚡ Real-time results using Streamlit
📊 High accuracy (~96%)

🧠 Tech Stack

Python
PyTorch
Ultralytics YOLOv8
OpenCV
Streamlit
Google Gemini API
NumPy, Pillow

📂 Project Structure
project/
│
├── app.py                     # Streamlit application
├── densenet_plant_disease.pth # Trained model
├── yolo_leaf_detector.pt      # YOLO model
├── requirements.txt
├── README.md
└── dataset/                   # (optional)

⚙️ Installation

1. Clone the repository
git clone https://github.com/your-username/leaf-disease-detection.git
cd leaf-disease-detection
2. Install dependencies
pip install -r requirements.txt
3. Set up environment variables

Create a .env file:

GEMINI_API_KEY=your_api_key_here
▶️ Run the Application
streamlit run app.py

🧪 Model Details

🔹 DenseNet-121
Transfer learning used
Output classes: 38 plant diseases
Accuracy: ~96%
🔹 YOLOv8
Detects leaf region
Improves classification accuracy

📊 Evaluation Metrics

Accuracy: 95–97%
Precision, Recall, F1-score (per class)
Confusion Matrix