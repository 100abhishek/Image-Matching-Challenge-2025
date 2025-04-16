# Image-Matching-Challenge-2025 🔍

This project demonstrates a deep learning-based Siamese Network to determine if two images are visually similar (a "match") or not (a "non-match"). The model has been trained to compare features between image pairs and make predictions based on visual similarity.

It is deployed using a user-friendly Gradio interface for testing and visualization.

---

## ✨ Features

- Siamese Neural Network using PyTorch
- Cosine similarity to determine image similarity
- Interactive Gradio interface
- Upload and compare your own image pairs
- Easy deployment-ready structure

---

## 🧠 How It Works

The Siamese Network uses two identical CNN branches (shared weights) to extract feature vectors from two input images. The network then computes the distance or similarity between these vectors. If the similarity is above a threshold (e.g., 0.5), the pair is considered a match.

The model outputs a similarity score between 0 and 1. You can use this score to decide if images are the same (1) or different (0).

---

## 🗂️ Folder Structure

