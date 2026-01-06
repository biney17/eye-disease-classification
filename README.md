# Eye Disease Classification using Deep Learning 👁️🧠

This project focuses on the automatic classification of eye diseases using deep learning techniques.  
It was developed as part of my first professional project during an internship, aiming to apply machine learning to medical image analysis.

## 📌 Project Overview
Eye diseases can significantly affect vision if not detected early.  
This project leverages **Convolutional Neural Networks (CNNs)** to classify eye disease images and assist in preliminary diagnosis.

The system performs:
- Image preprocessing
- Feature extraction using deep learning
- Disease classification
- Model evaluation using accuracy metrics

## 🧠 Technologies & Tools
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

## 🗂️ Project Structure
eye-disease-classification/
│
├── dataset/ # Dataset (not included)
├── dataset_split/ # Train/Test split (not included)
├── models/ # Model architecture & training scripts
├── notebooks/ # Jupyter notebooks
├── README.md # Project documentation
├── requirements.txt # Dependencies
└── .gitignore

markdown
Copy code

## ⚙️ Model Architecture
- Convolutional layers for feature extraction
- Pooling layers to reduce dimensionality
- Fully connected layers for classification
- Softmax activation for multi-class prediction

## 📊 Results
- High classification accuracy on validation data
- Stable training with reduced overfitting
- Clear class separation in predictions

> Detailed results and training curves are available in the notebooks.

## 🚀 How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/USERNAME/eye-disease-classification.git
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the notebook or training script:

bash
Copy code
python train.py
⚠️ Notes
Datasets and trained models are not included due to size limitations.

This project is intended for educational and research purposes only and should not be used for real medical diagnosis.

🙏 Acknowledgments
This project was developed during my internship.
Special thanks to Mr. Mina Nabil for his guidance and to the company for the opportunity to work on a real-world machine learning problem.

👤 Author
Isra Nour El Yakine Brahimi
Master’s Degree in Embedded Systems
