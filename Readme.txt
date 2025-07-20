# 🧠 Brain Tumor Detection Using Deep Learning (Google Colab + Gradio)

This project demonstrates a simple and effective way to detect brain tumors from MRI images using a Convolutional Neural Network (CNN). The model is deployed via a web interface using **Gradio**, and the whole workflow runs in **Google Colab** — no installation needed.

---

## 🔍 Project Highlights

- ✅ Binary classification: Tumor vs. No Tumor
- 🖼️ Takes MRI images as input
- 🧠 Deep learning model (CNN) built using TensorFlow/Keras
- 🌐 Live web interface via [Gradio](https://gradio.app/)
- ☁️ Entire project runs in Google Colab

---

## 🚀 How to Use

1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/).
2. Upload your own brain MRI image or use the provided test images.
3. Run all cells in the notebook.
4. A **Gradio interface** will appear with a link.
5. Upload an image to get a real-time prediction:
   - ✅ **No Tumor Detected**
   - ❌ **Tumor Detected**
   - 📊 Displays confidence score

---

## 🧠 Dataset Used

- **Source**: [Kaggle - Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
- Format: `.jpg` images categorized into:
  - `yes` (Tumor)
  - `no` (No Tumor)

---

## 🏗️ Model Summary

- Input: 150x150 RGB MRI images
- Layers:
  - Convolution + MaxPooling
  - Flatten
  - Dense layers
- Activation: `sigmoid` (binary classification)
- Optimizer: `adam`
- Loss Function: `binary_crossentropy`

---
##Demo video-https://drive.google.com/drive/folders/11R_H9yBeh5uqwmb4-w8XZM5SbOyhRtdV?usp=drive_link

## 📦 Requirements

If you plan to run this locally (not in Colab), install the following:

```bash
pip install tensorflow gradio numpy matplotlib
