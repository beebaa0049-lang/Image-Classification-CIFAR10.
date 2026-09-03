# Image Classification using CNN (CIFAR-10)
## 📌 Project Overview
This project is developed as part of the EncoderX Internship. The goal is to build a Convolutional Neural Network (CNN) capable of classifying images into 10 different categories using the CIFAR-10 dataset.
## 🛠️ Tools & Technologies
- **Language:** Python
- **Framework:** TensorFlow / Keras
- **Environment:** Google Colab
- **Libraries:** NumPy, Matplotlib, Seaborn, Scikit-learn
## 📂 Dataset
The **CIFAR-10** dataset consists of 60,000 32x32 color images in 10 classes: 
`airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck`.
## 🏗️ Model Architecture
The model uses a Convolutional Neural Network (CNN) with the following layers:
- **Convolutional Layers:** To extract spatial features from images.
- **MaxPooling Layers:** To reduce dimensionality and computation.
- **Flatten Layer:** To convert 2D maps into a 1D vector.
- **Dense Layers:** For final classification.
- **Softmax Activation:** To output probabilities for each class.
## 📈 Performance
- **Accuracy:** [Yahan apni accuracy likhein, e.g., 72%]
- **Loss:** [Yahan apna final loss likhein]
- **Evaluation Metrics:** Precision, Recall, and F1-Score are calculated using a Confusion Matrix.
## 🚀 How to Run
1. Clone this repository.
2. Open the `.ipynb` file in Google Colab.
3. Set Runtime to GPU (T4).
4. Run all cells sequentially.
