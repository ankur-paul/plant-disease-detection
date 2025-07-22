# 🌿 Plant Disease Detection using Deep Learning

Welcome to the repository for my **Summer Training Project** on AI-based **Plant Disease Detection** using deep learning. This project explores deep learning approaches for classifying leaf diseases across five important crops using transfer learning.

## 📌 Project Overview

This project focuses on identifying plant diseases using image classification. Leveraging transfer learning with MobileNetV2, I developed individual and combined models for five crops.

### 👨‍🌾 Target Crops:

- Tomato
- Corn
- Grape
- Mango
- Peanut

## 📁 Repository Structure

```
plant-disease-detection/
├── tomato_mnv2/
│ ├── tomato_MNV2.ipynb
│ └── Tomato_MNV2.keras
├── corn_mnv2/
│ ├── corn_MNV2.ipynb
│ └── Corn_MNV2.keras
├── grape_mnv2/
│ ├── grape_MNV2.ipynb
│ └── Grape_MNV2.keras
├── mango_mnv2/
│ ├── mango_MNV2.ipynb
│ └── Mango_MNV2.keras
├── peanut_mnv2/
│ ├── peanut_MNV2.ipynb
│ └── Peanut_MNV2.keras
├── combined_mnv2/
│ ├── plant_disease_MNV2.ipynb
│ └── Plant_disease_MNV2.keras
├── 📄 README.md
```

## 🧪 Key Features

- ⚙️ Trained with **MobileNetV2**
- 🔁 Balanced dataset using oversampling & rotation augmentation
- 📊 Accuracy, confusion matrices, and test performance plots
- 🧠 Individual and unified model approaches
- 📉 Bias and overfitting addressed using dataset curation
- 🌱 Tested on **real-world unseen leaf images**

## 🧺 Dataset

Balanced dataset curated from multiple open sources (PlantVillage, Mendeley, etc.). Each class contains 1200 images. Major classes were **undersampled** randomly, and minor classes were **oversampled** using augmentation (rotations of 90°, 180°, and 270°).  
📦 Hosted on **[Kaggle](https://www.kaggle.com/api/v1/datasets/download/ankurpaul52/balanced-multi-crop-plant-disease-dataset)**
