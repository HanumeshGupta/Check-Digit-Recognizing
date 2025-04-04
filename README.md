# 🔢 Digit Recognizer

Welcome to the **Digit Recognizer** project! This repository contains a deep learning-based model for recognizing handwritten digits using the **MNIST dataset**. 🖊️🔍

## 📌 Project Overview
This project applies neural networks to classify handwritten digits (0-9) based on pixel values. It includes:
- Implementation of **Neural Networks (NN)** for digit recognition.
- Training and evaluation on the **MNIST dataset**.
- A step-by-step Jupyter Notebook for model building and testing.

## 📂 Repository Structure
```
📦 Digit Recognizer
├── .gitattributes                    # Git configuration file
├── Digit_Recognizer.rar               # Compressed project files
├── Digit_Recognizing_NN.ipynb         # Neural Network-based digit recognition
├── Digit_Recognizing_building_Neuro.ipynb  # Another approach for building a neural network
├── Example-of-a-MNIST-input-An-image-is-passed.png # Example of an input image
├── sample_submission.csv              # Sample predictions
```

## ⚙️ Installation & Setup
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/HanumeshGupta/Check-Digit-Recognizing.git
   cd Digit-Recognizer
   ```

2. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   Open **Digit_Recognizing_NN.ipynb** and execute the cells to train and test the model.

## 📊 Dataset Details
- The model uses the **MNIST dataset**, consisting of **60,000 training** and **10,000 testing** grayscale images (28x28 pixels each).
- Each image represents a single handwritten digit (0-9).

## 🔥 Model Summary
- **Input Layer**: 28x28 flattened pixel values
- **Hidden Layers**: Multiple dense layers with ReLU activation
- **Output Layer**: 10 neurons (0-9 classification) with softmax activation
- **Loss Function**: Categorical Crossentropy
- **Optimizer**: Adam

## 📈 Results & Performance
- Achieved an **accuracy of ~98%** on the test dataset.
- Sample input image:
  ![MNIST Input](Example-of-a-MNIST-input-An-image-is-passed.png)

## 🚀 Future Improvements
- Implement **CNNs (Convolutional Neural Networks)** for higher accuracy.
- Add data augmentation for better generalization.
- Deploy the model using Flask or FastAPI.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## 📬 Contact
For any queries, reach out via GitHub issues or email me at [hanumeshgupta2907@gmail.com](mailto:hanumeshgupta2907@gmail.com).
