# Potato Disease Classification

## Overview
This project focuses on classifying potato leaf diseases using a Convolutional Neural Network (CNN). The model can identify three categories:
- **Potato Early Blight**
- **Potato Late Blight**
- **Healthy Potato Leaves**

## Project Status
🚀 Currently, I am working on developing an **app** that will allow users to detect potato diseases from images!

## Dataset
The dataset consists of 2,152 images categorized into three classes. The images are loaded and preprocessed using TensorFlow.

## Technologies Used
- **TensorFlow/Keras** for deep learning model development
- **Matplotlib** for data visualization
- **Python** for scripting and automation
- **Google Colab** for model training

## Model Architecture
The model follows a CNN-based approach with layers for:
- Image resizing and rescaling
- Data augmentation
- Multiple convolutional layers with max pooling
- Fully connected dense layers with softmax activation

## Training & Evaluation
- The dataset is split into **Training (80%)**, **Validation (10%)**, and **Testing (10%)**.
- **Adam optimizer** and **Sparse Categorical Crossentropy** loss function are used.
- Model achieves over **98% accuracy** on validation data.

## Next Steps
- Deploy the trained model into an **interactive app**.
- Optimize the model for mobile and web-based inference.
- Implement real-time image detection.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/potato-disease-classification.git
   ```
2. Install dependencies:
   ```bash
   pip install tensorflow matplotlib
   ```
3. Run the notebook in **Google Colab** or locally:
   ```bash
   jupyter notebook Potato_disease_classification.ipynb
   ```

## Contributing
Feel free to open an issue or pull request if you'd like to contribute!

## Acknowledgments
This project was inspired by the need for **early disease detection in agriculture**, helping farmers make informed decisions and reduce crop losses.

---


