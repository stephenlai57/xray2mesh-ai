# 🧠 Revolutionizing Medical Imaging: AI-Driven 3D Reconstruction from Bi-Planar X-Ray Scans

![3D Reconstruction Demo](reports/figures/3d_example.png)

> **A cutting-edge deep learning pipeline for reconstructing accurate 3D anatomical models from dual-view 2D X-rays — advancing radiology, diagnostics, and surgical planning.**

---

## 🚀 Overview

This project pioneers an AI-powered method to transform **bi-planar (frontal and lateral)** 2D X-ray images into realistic **3D anatomical models**. It eliminates the need for CT or MRI in certain clinical scenarios, lowering costs and increasing accessibility to precision diagnostics — especially in orthopedics.

By combining **Convolutional Neural Networks (CNNs)** for feature extraction and a **Generative Adversarial Network (GAN)** for 3D reconstruction, the pipeline produces high-fidelity 3D representations of human anatomy from just two X-ray views.

---

## 🎯 Objectives

- 📸 Extract spatial features from dual-view X-rays using transfer learning.
- 🧬 Reconstruct detailed 3D models using a GAN-based generator-discriminator framework.
- 🧪 Validate reconstruction accuracy with ground truth 3D models (e.g., from CT).
- 💡 Enable AI-assisted diagnostics, surgical planning, and medical education.

---

## 🛠️ Technologies & Tools

- **Python 3.11**
- **PyTorch** & `torchvision`
- **Xception** (via `timm`) for deep feature extraction
- **GAN** (custom architecture)
- **Trimesh / PyVista** for 3D mesh visualization
- **OpenCV** for image preprocessing
- **Matplotlib / TensorBoard** for monitoring & visualization

---

## 📁 Project Structure

