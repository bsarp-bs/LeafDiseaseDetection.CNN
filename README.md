# 🌿 Leaf Disease Detection Using Deep Learning

This project focuses on detecting plant leaf diseases using a Convolutional Neural Network (CNN). The model is trained on plant leaf images to classify different types of plant diseases automatically.

## 📌 Project Overview

Plant diseases significantly affect agricultural productivity. Early detection helps farmers take preventive measures and reduce crop losses.

In this project, a deep learning model is trained to classify plant leaf diseases using image data. The system analyzes leaf images and predicts the type of disease.

## 🚀 Features

* Deep Learning based plant disease classification
* Image preprocessing and dataset preparation
* CNN model training using TensorFlow/Keras
* Visualization of training accuracy and loss
* Model saving for future predictions

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Pillow
* Jupyter Notebook

## 📂 Project Structure

```
leaf-disease-detection
│││
├── leaf_disease_classification.ipynb
│
├── requirements.txt
│
└── README.md
```

## 📊 Dataset

This project uses the **PlantVillage Dataset**, which contains thousands of labeled images of healthy and diseased plant leaves.

Dataset Source:
https://www.kaggle.com/datasets/emmarex/plantdisease

## ⚙️ Installation


Install required libraries:

```
pip install -r requirements.txt
```

## ▶️ Running the Project

Open the notebook and run the cells:

```
jupyter notebook leaf_disease_classification.ipynb
```

The notebook includes:

* Dataset loading
* Model creation
* Model training
* Performance visualization
* Disease prediction

## 📈 Model

The model uses a Convolutional Neural Network (CNN) architecture to extract features from leaf images and classify them into disease categories.

## 💾 Model Output

The trained model is saved as:

```
leaf_disease_model.h5
```

This model can later be used for predictions or deployed in applications.

## 📷 Example Workflow

1. Load plant leaf image
2. Preprocess image
3. Feed image into CNN model
4. Predict disease class

## 📚 References

PlantVillage Dataset
https://www.kaggle.com/datasets/emmarex/plantdisease
