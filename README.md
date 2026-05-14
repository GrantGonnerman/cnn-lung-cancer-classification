# CNN Lung Cancer Classification

**Deep Learning for Medical Imaging** | Convolutional Neural Network for classifying lung cancer types from CT scan images.

## 📋 Project Overview
This project develops a Convolutional Neural Network (CNN) to accurately classify different types of lung cancer from CT scan images. The model helps support early and accurate diagnosis, which is critical for improving patient outcomes in oncology.

## 🎯 Business / Real-World Impact
Lung cancer is one of the leading causes of cancer-related deaths worldwide. Automated image classification can assist radiologists by reducing diagnostic time and improving detection accuracy, especially in high-volume clinical settings.

## 🗂️ Dataset
- **Source**: Lung cancer CT scan dataset (Kaggle / AWS S3)
- **Target**: Multi-class classification of lung cancer types
- **Features**: Medical images (CT scans)

## 🔧 Key Techniques & Models
- **Data Preprocessing**: Image loading, resizing, normalization, and data augmentation
- **Exploratory Data Analysis**: Image visualization and class distribution analysis
- **Modeling**:
  - Custom CNN architecture using TensorFlow/Keras
  - Multiple Conv2D + MaxPooling layers
  - Dropout regularization and hyperparameter tuning
  - Data augmentation to improve generalization
- **Evaluation**: Accuracy, Precision, Recall, F1-score, Confusion Matrix, and training curves

## 📊 Results
- Achieved **97% accuracy** on the test set through careful hyperparameter tuning and data augmentation
- Strong performance across different lung cancer classes
- Demonstrated effective use of CNNs for medical image classification

## 📄 Reports
- [Full Project Report (PDF)](CNN%20Lung%20Cancer%20Classification/Reports/CNN%20Lung%20Cancer%20Classification%20Report.pdf)
- [Presentation Slides (PDF)](CNN%20Lung%20Cancer%20Classification/Reports/CNN%20Lung%20Cancer%20Classification%20Slides.pdf)

## 🛠️ Technologies Used
**Python** • **TensorFlow / Keras** • **Convolutional Neural Networks (CNN)** • **Data Augmentation** • **Matplotlib** • **Seaborn** • **pandas**
