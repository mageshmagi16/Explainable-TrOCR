# 🧠 Explainable TrOCR  
### Making Transformer-based OCR Interpretable using Cross-Attention Visualization

---

## 🔍 Overview

Optical Character Recognition (OCR) systems are widely used in document processing, finance, education, and legal workflows.  
While modern OCR models achieve high accuracy, they often behave as **black boxes**, providing no explanation for *why* a particular word was predicted.

This project focuses on **Explainable OCR**, built on top of **Microsoft’s TrOCR (Transformer-based OCR)** model.

Instead of only extracting text, this project visualizes **where the model attends in the image for each predicted token**, using **cross-attention maps** from the Transformer decoder.

🎯 **Goal**  
Understand model behavior at inference time — **without retraining the model**

---

## ✨ Key Features

- ✅ Pretrained **TrOCR inference** (no retraining required)
- 🔍 **Cross-attention extraction** from Transformer decoder
- 🧠 Token-level explainability
- 🔥 Attention **heatmap overlay** on input image
- 📊 Patch-level visual grounding of text predictions
- 🚀 Runs on **Google Colab (Tesla T4 GPU)** or local machine

---

