# 🧠 Image Matching Challenge 2025

Welcome to the official repository for the **Image Matching Challenge 2025**!  
This project presents a deep learning-based solution to automatically determine whether two images represent the same object, scene, or entity. It leverages Siamese Networks for pairwise image comparison and is designed to be interactive, deployable, and extendable.

---

## 📸 Overview of the Challenge

The Image Matching Challenge is focused on building systems that can:

- Identify whether two images are a match (represent the same object or scene) or not.
- Handle a wide variety of input images such as buildings, objects, logos, or daily scenes.
- Work with different perspectives, lighting conditions, and resolutions.
- Predict similarity scores and generate match/non-match classifications.

The core objective is to train and evaluate a model that can distinguish between image pairs by learning meaningful embeddings through deep learning.

---

## 🧠 Technologies Used

| Component            | Description                                   |
|----------------------|-----------------------------------------------|
| Python               | Programming language                          |
| PyTorch              | Deep learning framework for model training    |
| Torchvision          | Pre-trained CNN architectures (e.g., ResNet) |
| Gradio               | For building a simple web interface           |
| OpenCV / Pillow      | Image loading and preprocessing               |
| NumPy                | Array operations                              |

---

## 🗂️ Project Structure

├── app.py # Gradio app for image matching ├── model.py # Siamese network architecture ├── siamese_model.pth # Trained model weights ├── submission.csv # Output predictions for evaluation ├── requirements.txt # List of Python dependencies └── README.md # Documentation (this file)


---

## ⚙️ Running in Google Colab (No Setup Required)

1. Open Google Colab at [colab.research.google.com](https://colab.research.google.com).
2. Upload the following files to your Colab environment:
   - `model.py`
   - `app.py`
   - `siamese_model.pth`
3. Install required dependencies:

```python
!pip install torch torchvision gradio Pillow numpy
