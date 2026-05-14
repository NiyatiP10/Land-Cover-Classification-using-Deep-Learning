# Land Cover Classification of RGB Satellite Images

Deep Learning based image classification project for identifying land cover types from RGB satellite imagery using Convolutional Neural Networks (CNNs) and Transfer Learning.

This project uses the EuroSAT dataset and multiple CNN architectures to classify satellite images into 10 land-cover categories such as Forest, River, Residential, Industrial, Highway, and more.

---

# Project Overview

The objective of this project is to build a Deep Learning model capable of accurately classifying satellite images into different land-cover classes.

This type of system can be useful for:

* Deforestation monitoring
* Environmental conservation
* Urban expansion analysis
* Agricultural monitoring
* Remote sensing applications
* Land development tracking

The final model uses Transfer Learning with VGG16 and achieves high classification accuracy.

---

# Dataset

Dataset Used: **EuroSAT RGB Dataset**

Download Dataset:
[https://zenodo.org/record/7711810](https://zenodo.org/record/7711810)

The dataset contains approximately 27,000 RGB satellite images distributed across 10 classes.

## Classes

* Annual Crop
* Forest
* Herbaceous Vegetation
* Highway
* Industrial
* Pasture
* Permanent Crop
* Residential
* River
* Sea or Lake

---

# Technologies Used

| Technology         | Purpose                 |
| ------------------ | ----------------------- |
| Python             | Programming Language    |
| TensorFlow / Keras | Deep Learning           |
| OpenCV             | Image Processing        |
| NumPy              | Numerical Computing     |
| Pandas             | Data Analysis           |
| Matplotlib         | Data Visualization      |
| Seaborn            | Visualization           |
| Scikit-learn       | Evaluation Metrics      |
| Jupyter Notebook   | Development Environment |

---

# Features

* Image preprocessing and normalization
* Train/Validation/Test split
* Baseline CNN model
* Data augmentation
* Transfer Learning using VGG16
* Fine tuning of pretrained model
* Accuracy and loss visualization
* Confusion matrix evaluation
* Satellite image classification

---

# Project Structure

```bash
Land_Cover_Classification/
│
├── dataset/
│   ├── AnnualCrop/
│   ├── Forest/
│   ├── Highway/
│   └── ...
│
├── Land_Cover_Classification.ipynb
├── README.md
└── requirements.txt
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/NiyatiP10/Land-Cover-Classification-Using-Deep-Learning.git
```

## Move to Project Directory

```bash
cd Land-Cover-Classification-Using-Deep-Learning
```

## Create Virtual Environment

```bash
python -m venv venv
```

## Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Required Libraries

```bash
tensorflow
numpy
pandas
matplotlib
seaborn
scikit-learn
opencv-python
pillow
jupyter
```

---

# How to Run the Project

## Start Jupyter Notebook

```bash
jupyter notebook
```

## Open Notebook

```bash
Land_Cover_Classification.ipynb
```

Run all cells sequentially.

---

# Workflow

1. Import dataset
2. Preprocess images
3. Visualize sample images
4. Split train and test data
5. Build baseline CNN model
6. Apply data augmentation
7. Train VGG16 transfer learning model
8. Fine tune pretrained layers
9. Evaluate model performance
10. Generate predictions

---

# Models Used

The notebook includes experiments with multiple Convolutional Neural Network architectures:

* Baseline CNN
* Augmented CNN
* Transfer Learning Models
* Fine Tuned VGG16 Model

Final model:

* VGG16 pretrained on ImageNet
* Additional Dense layers
* Dropout regularization
* Fine tuning enabled

---

# Evaluation Metrics

The project evaluates model performance using:

* Accuracy
* Validation Accuracy
* Loss Curves
* Confusion Matrix
* Classification Report

---

# Results

The final Transfer Learning model achieved strong classification accuracy on the EuroSAT dataset.

Key improvements came from:

* Data augmentation
* Transfer learning
* Fine tuning
* Dropout regularization

---

# Example Applications

* Environmental monitoring
* Smart agriculture
* Urban planning
* Satellite image analysis
* Land-use monitoring
* Remote sensing research

---

# Future Improvements

* Add object detection
* Use ResNet50 or EfficientNet
* Build web application using Streamlit
* Deploy model online
* Add real-time satellite API integration
* Implement semantic segmentation

---

# Author

Niyati Patil

GitHub: [https://github.com/NiyatiP10](https://github.com/NiyatiP10)

---

# License

This project is for educational and research purposes.
