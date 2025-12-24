#  SpineHealth – Scoliosis Detection Web App

This repository contains a **machine learning model** trained to detect scoliosis from spine images, along with a **web application** where users can upload images and get predictions whether there is scoliosis or not.

---

##  Project Overview

SpineHealth is a computer vision project that combines:

✔ A **trained deep learning model** for scoliosis detection  
✔ A **web interface** for users to upload spine images and view predictions  
✔ A user-friendly frontend with instant feedback from the model

This project is designed to help classify spinal X-ray images as either **scoliosis** or **normal**, and can be used for educational and prototyping purposes.

---

##  How It Works

1. A dataset of spinal images is used to train a classification model.  
2. The model learns to differentiate between **scoliosis** and **non-scoliosis** cases.  
3. A simple web interface allows users to upload an X-ray or photo.  
4. The model returns a **prediction label** (e.g., “Scoliosis detected” or “No scoliosis”) for the uploaded image.

---

##  Built With

This project uses:

✔ Python (ML training & backend)  
✔ Machine learning / Deep learning libraries (e.g., PyTorch or TensorFlow)  
✔ Web frontend (HTML, CSS, JavaScript)  
✔ Backend web framework (e.g., Flask)  
✔ Optional: dataset tools (like Roboflow) for labeling and augmentation

---

##  Repository Structure

/Projekat-SpineHealth
├── model/ # Trained model files
├── backend/ # Flask (or other) API server
│ └── app.py
├── frontend/ # Web interface
│ ├── index.html
│ ├── css/
│ │ └── style.css
│ └── js/
├── utils/ # Model loading & preprocessing scripts
├── requirements.txt # Python dependencies
└── README.md


---

## 🚀 Getting Started

### 1. Clone the repo:

```bash
git clone https://github.com/elvistaruh/Projekat-SpineHealth.git
cd Projekat-SpineHealth


pip install -r requirements.txt

python backend/app.py

http://localhost:5000


