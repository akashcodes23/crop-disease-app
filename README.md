🌱 Crop Disease Detection using CNN


> AI-powered platform that detects plant leaf diseases in real time.
Built with deep learning (CNNs) and deployed on a Streamlit prototype, this project aims to empower farmers and researchers with faster, more reliable crop health diagnostics.


✨ Key Highlights

📸 Image Upload & Processing – Upload leaf images directly for detection.

🔍 Real-Time Diagnosis – CNN model predicts the disease type instantly.

📊 Insights Dashboard – Model performance metrics & visualizations.

🌐 Deployment Ready – Scalable for web or mobile applications.


🚀 Quick Start

Clone the repository and set up dependencies:

git clone https://github.com/akashcodes23/crop-disease-app.git
cd crop-disease-app
pip install -r requirements.txt
streamlit run app/app.py


🛠️ Tech Stack

Languages: Python

Deep Learning: TensorFlow/Keras

Data Processing: OpenCV, NumPy, Pandas

Visualization: Matplotlib, Seaborn

Frontend Prototype: Streamlit


📂 Project Structure

├── data/                # Dataset (train/test images)  
├── notebooks/           # Jupyter notebooks for training & evaluation  
├── models/              # Trained CNN models (.h5)  
├── app/                 # Streamlit prototype  
├── requirements.txt     # Dependencies  
└── README.md            # Documentation


📊 Model Workflow

1. Data Preprocessing – Image resizing, normalization, augmentation.

2. CNN Training – Classification of healthy vs diseased crops.

3. Evaluation – Accuracy, confusion matrix, and loss curves.

4. Deployment – Streamlit prototype for live testing.


📈 Results 

Training Accuracy: ~97%

Validation Accuracy: ~92%

Precision & Recall: High across all classes (>90%)


🔍 Interpretation

Healthy leaves are detected with near-perfect accuracy, showing the model’s reliability in differentiating diseased vs non-diseased samples.

Disease A & Disease B show minor overlap (misclassifications), which is expected due to visual similarities in leaf patterns.

Disease C is identified with high confidence and minimal confusion.

The model demonstrates strong generalization, with most errors being between visually similar disease classes.


🌍 Future Roadmap

📌 Expand dataset with more crop varieties.

📌 Optimize model for mobile/edge devices.

📌 Deploy API (Flask/FastAPI) for wider integration.

📌 Multilingual farmer support for accessibility.


🤝 Contributing


📜 License

This project is licensed under the MIT License.

⚡ “Empowering farmers with AI-driven crop health diagnostics.” 🌾
