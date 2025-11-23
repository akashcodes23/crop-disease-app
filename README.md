## 🌱 KrishiRakshak — Crop Disease Detection using CNN

![WhatsApp Image 2025-09-23 at 10 02 21](https://github.com/user-attachments/assets/4bc43001-de48-40fe-9143-7a52787ac623)


> KrishiRakshak is an AI-powered system designed to detect crop leaf diseases instantly using deep learning.
Built with Convolutional Neural Networks (CNNs) and deployed through a clean Streamlit interface, this project provides fast, accessible, and reliable crop health diagnostics for farmers, researchers, and agri-tech innovators.

## ✨ Key Highlights

📸 Image Upload & Processing – Upload leaf images directly for detection.
🔍 Real-Time Diagnosis – CNN model predicts the disease type instantly.
📊 Insights Dashboard – Model performance metrics & visualizations.
🌐 Deployment Ready – Scalable for web or mobile applications.
🧪 Reproducible ML Pipeline – Clean notebooks for training & evaluation.


## 🎥 Demo Video

[![Watch the Demo](https://img.youtube.com/vi/iJjUglD_1Nc/0.jpg)](https://youtu.be/iJjUglD_1Nc)


## 🚀 Quick Start

Clone the repository:
```
git clone https://github.com/akashcodes23/crop-disease-app.git
cd crop-disease-app
```
Install the dependencies:
```
pip install -r requirements.txt
```
Run the Streamlit application:
```
streamlit run app/app.py
```

 ## Tech Stack

Programming Language: Python
Deep Learning: TensorFlow, Keras
Data Processing: OpenCV, NumPy, Pandas
Visualization: Matplotlib, Seaborn
Frontend Prototype: Streamlit


## 📂 Project Structure

├── data/                # Dataset (train/test images)  
├── notebooks/           # Jupyter notebooks for training & evaluation  
├── models/              # Trained CNN models (.h5)  
├── app/                 # Streamlit prototype  
├── requirements.txt     # Dependencies  
└── README.md            # Documentation


## Model Workflow

1. Data Preprocessing – Image resizing, normalization, augmentation.

2. CNN Training – Classification of healthy vs diseased crops.

3. Evaluation – Accuracy, confusion matrix, and loss curves.

4. Deployment – Streamlit prototype for live testing.


## 📈 Results 

Training Accuracy: ~97%

Validation Accuracy: ~92%

Precision & Recall: High across all classes (>90%)


## 🔍 Interpretation

-Healthy leaves are detected with near-perfect accuracy, showing the model’s reliability in differentiating diseased vs non-diseased samples.

-Disease A & Disease B show minor overlap (misclassifications), which is expected due to visual similarities in leaf patterns.

-Disease C is identified with high confidence and minimal confusion.

-The model demonstrates strong generalization, with most errors being between visually similar disease classes.


## 🌍 Future Roadmap

- Add more crop varieties (tomato, rice, maize, sugarcane).
- Optimize for mobile and edge devices (TensorFlow Lite).
- Deploy as API using Flask/FastAPI.
- Add multilingual farmer interface (Hindi / Kannada / English).
- Integrate weather & IoT data for advanced predictions.

## 🤝 Contributing

Contributions are welcome!
You can contribute by:
	•	Adding new crop disease classes
	•	Improving model accuracy
	•	Enhancing the UI/UX
	•	Integrating APIs or mobile deployment
	•	Expanding datasets and preprocessing pipelines

Submit a Pull Request or open an Issue to get started.


## 📜 License

This project is licensed under the MIT License — free to use, modify, and distribute with proper attribution.

Empowering farmers with AI-driven crop health diagnostics🌾
