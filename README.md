# Waste Segregation using Convolutional Neural Networks (CNN)

This project focuses on automating the classification of waste materials into categories like plastic, paper, glass, metal, and food waste using Convolutional Neural Networks (CNNs). The aim is to support smarter waste disposal systems and improve recycling efficiency.

## 📂 Dataset

The dataset includes labeled images of different waste types, organized into the following categories:

- **Cardboard**
- **Glass**
- **Metal**
- **Paper**
- **Plastic**
- **Food Waste**

Each image has been preprocessed to ensure consistency during training.

## 🧠 Model Architecture

The model is built using TensorFlow/Keras and includes:

- Multiple convolutional layers for feature extraction
- MaxPooling layers to reduce spatial dimensions
- Dropout layers to prevent overfitting
- Dense layers for classification

Callbacks like **EarlyStopping**, **ModelCheckpoint**, and a **Learning Rate Scheduler** were used to optimize training.

## 🏋️ Model Training

The model was trained using both original and augmented datasets. Augmentation helped to improve generalization by introducing variability.

**Training Details:**

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metrics: Accuracy
- Epochs: 30
- Batch Size: 32

### Results:

- **Validation Accuracy**: ~` 0.72%` 
- **Validation Loss**: `1.3896` 

## 🔍 Evaluation

Model performance was evaluated using the validation dataset. Accuracy and loss trends were monitored to ensure optimal performance and avoid overfitting.

## 🧪 Features

- Image preprocessing and augmentation
- Custom CNN architecture
- Real-time model monitoring using validation metrics
- Model checkpointing and recovery

## 🚀 How to Run

1. Clone the repository
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook CNN_Assg_Waste_Segregation_Starter.ipynb

## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Deep Learning course.

## Developer Information

- **Name**: Snehal Yadav
- **Contact**: [snehalyadav3099@gmail.com](mailto:snehalyadav3099@gmail.com)
