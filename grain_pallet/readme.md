project files
# 🌾 GrainPalette – Rice Type Classification using Deep Learning

GrainPalette is a deep learning-based web application that classifies rice grain images into various types using transfer learning. It features a clean UI, login/register system, and a backend powered by Flask and TensorFlow.

---

## 🚀 Features

- 📷 Upload rice grain image and get predicted type.
- 🧠 Uses MobileNetV2 + Transfer Learning for classification.
- 🔐 Secure user login and registration (JSON-based).
- 🎨 Beautiful frontend design with background and UI customization.

---


## 🗂️ Project file download and extract process

---github link : - https://github.com/JhansiManikonda/-grainpalette---a-deep-learning-odyssey-in-rice-type-classification-through-transfer-learning
## 📦 Download & Extract

### 1. Download the ZIP
[Click here to download GrainPalette.zip]
### 2. Extract the ZIP File

- Right-click the downloaded `.zip` file
- Choose **Extract All...**
- Select a folder to extract and click **Extract**

After extraction, navigate to the folder and follow the setup instructions below.

---
## 🗂️ Project Structure(after extract this is the actual structure)

GrainPalette/
│
├── app.py # Main Flask app
├── train_model.py # Model training script
├── requirements.txt # Python dependencies
├── users.json # User data (login/register)
├── README.md # Project documentation
│
├── model/ # Trained rice_model.h5
├── data/ # Rice dataset(optional)
├── static/ # CSS, JS, background images
├── templates/ # HTML templates (index, login, register)
└── venv/ # Virtual environment .

---
## 3. Set Up the Environment

## Create & Activate Virtual Environment

---
<<< bash
python -m venv venv
venv\Scripts\activate

---


## Install Dependencies


pip install -r requirements.txt

---

## Run the App

python app.py

you get a app link ......!
