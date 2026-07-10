# Urdu OCR Project | Code Saviours SI-26 | Hafiza Tehreem Fatima
Week 1 OCR project: Urdu OCR dataset collection, preprocessing, labeling and project setup using Google Colab, GitHub and Hugging Face.


## 📌 Project Title
Urdu Optical Character Recognition (OCR) – Dataset Collection & Project Setup


## 🎯 Objective

The objective of this project is to build an Urdu Optical Character Recognition (OCR) system capable of recognizing Urdu text from images. During Week 1, the focus was on setting up the development environment, collecting a suitable dataset, organizing the images, and preparing the ground truth labels required for model training.


## 📂 Dataset Source

**Source:** Kaggle

The dataset was downloaded from Kaggle and contains Urdu text images that will be used for training and evaluating the OCR model.


## 🖼️ Dataset Information

- Dataset Source: Kaggle
- Language: Urdu
- Image Format: PNG
- Total Images: **119+**
- Dataset Type: Urdu text/character images
- Labels File: `labels.csv`

---

## 📁 Folder Structure

```text
Urdu-OCR-Project/
│
├── README.md
├── Week1.ipynb
│
├── data/
│   ├── labels.csv
│   └── raw/
│       └── Urdu OCR/
│           ├── Urdu lines/
│           ├── آ/
│           ├── ب/
│           ├── پ/
│           ├── ت/
│           ├── ...
│
└── notebooks/
```

---
## 🛠️ Tools & Technologies Used

- Python
- Google Colab
- GitHub
- Pandas
- CSV
- Pillow (PIL)
- OCR Dataset from Kaggle



## ✅ Week 1 Progress

The following tasks were completed during Week 1:

- Created the GitHub repository.
- Set up the project folder structure.
- Downloaded the Urdu OCR dataset from Kaggle.
- Uploaded and extracted the dataset in Google Colab.
- Verified the dataset and counted the images.
- Organized the dataset into the required directory structure.
- Generated the `labels.csv` file for ground truth labeling.
- Prepared the project for the preprocessing and model training phases.



## 🚀 Next Steps

In the upcoming weeks, the project will focus on:

- Image preprocessing
- Data cleaning and augmentation
- OCR model development
- Model training
- Performance evaluation
- Model optimization


## Why We Need a Better Model

During Week 2, Tesseract OCR was tested on multiple Urdu text images after preprocessing. The results showed that Tesseract struggled to recognize Urdu text accurately. In several cases, it produced no output, while in others it recognized only a few words or generated incomplete and incorrect text.

This happens because Urdu is a cursive language with connected characters, context-dependent letter shapes, and complex ligatures. General-purpose OCR engines like Tesseract are not optimized for these characteristics.

These observations demonstrate the need to develop a dedicated machine learning/deep learning OCR model trained specifically for Urdu text.





## 👩‍💻 Author

**Hafiza Tehreem Fatima**

Machine Learning Intern at **Code Saviours**
