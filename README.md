# 🤟 AI American Sign Language (ASL) Recognition

An AI-powered American Sign Language (ASL) Recognition web application built using **TensorFlow**, **MobileNetV2**, and **Streamlit**. This application classifies hand sign images into ASL letters and digits with real-time predictions and confidence scores.

---

## 🚀 Features

- 🔤 Recognizes American Sign Language (ASL) hand signs
- 🧠 Deep Learning model using MobileNetV2 (Transfer Learning)
- 📷 Upload an image for instant prediction
- 📊 Displays prediction confidence
- 🎨 Modern Streamlit user interface
- ⚡ Fast and lightweight inference
- 📱 Responsive design

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2
- Streamlit
- NumPy
- Pillow (PIL)
- Google Colab

---

## 📂 Project Structure

```
AI-ASL-Recognition/
│
├── app.py                 # Streamlit application
├── asl_model.h5           # Trained deep learning model
├── requirements.txt       # Required libraries
├── README.md
├── notebook.ipynb         # Model training notebook
└── images/                # Screenshots (optional)
```

---

## 📊 Model Information

| Property | Value |
|----------|-------|
| Model | MobileNetV2 |
| Framework | TensorFlow |
| Input Size | 224 × 224 |
| Classes | 36 |
| Output | ASL Letters (A–Z) & Digits (0–9) |

---

## 📸 How It Works

1. Upload an image containing an ASL hand sign.
2. The image is resized and preprocessed.
3. The trained MobileNetV2 model predicts the sign.
4. The predicted character and confidence score are displayed.

---

## 💻 Installation

Clone the repository

```bash
git clone https://github.com/your-username/AI-ASL-Recognition.git
```

Move into the project folder

```bash
cd AI-ASL-Recognition
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## 📈 Future Improvements

- 🎥 Real-time webcam recognition
- 🗣️ Text-to-Speech output
- 📖 Sentence prediction
- ☁️ Cloud deployment
- 🌐 Support for multiple sign languages
- 📱 Mobile-friendly interface

---

## 👨‍💻 Author

**Mohammed Rishal**

- Data Science Trainee
- Python Developer
- Machine Learning Enthusiast

---

## ⭐ If you like this project

Please consider giving this repository a **Star ⭐** to support the project.

## 📂 Dataset

The model was trained on a publicly available **American Sign Language (ASL) Image Dataset** obtained from platforms such as **Kaggle** or other open-source dataset repositories.

### 📌 Dataset Details

- **Dataset Type:** Image Classification
- **Total Classes:** 36
- **Classes:**
  - Digits: `0–9`
  - Alphabets: `A–Z`
- **Image Format:** JPG / PNG
- **Image Size:** Resized to **224 × 224** pixels
- **Color Mode:** RGB
- **Training Split:** 80%
- **Validation Split:** 20%

### 📁 Dataset Structure

```
American/
│
├── 0/
├── 1/
├── 2/
├── ...
├── 9/
├── a/
├── b/
├── c/
├── ...
└── z/
```

Each folder represents a unique ASL character and contains multiple images used to train the deep learning model.

### 🔄 Data Preprocessing

- Images resized to **224 × 224** pixels.
- RGB color format maintained.
- Pixel values normalized using TensorFlow.
- Dataset loaded using `image_dataset_from_directory()`.
- Training and validation datasets created with an **80:20 split**.

### 📥 Dataset Source

The dataset can be downloaded from public machine learning repositories such as:

- **Kaggle**
- **TensorFlow Datasets**
- **Roboflow Universe**
- **UCI Machine Learning Repository** (where applicable)

> **Note:** The dataset is **not included** in this repository because of its large size. Please download it from the original source (e.g., Kaggle or another public dataset provider) and place it in the appropriate project directory before training the model.
