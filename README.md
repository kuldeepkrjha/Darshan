# 👁️‍🗨️ DARSHAN – Visionary AI for Preventing Blindness

![darshan-banner](assets/darshan_banner.png)

**DARSHAN** (दर्शन) is an intelligent AI-driven platform that leverages deep learning to detect eye diseases from retinal fundus images—aiming to stop blindness *before it begins*. This project was developed as part of the CDAC Hackathon **"Visionary AI: Hacking Blindness Before It Begins"**, hosted by the Ministry of Electronics & IT, Govt. of India.

---

## 🚀 Objective

Early diagnosis of retinal diseases like Diabetic Retinopathy (DR), Glaucoma, ARMD, and more is critical in preventing irreversible vision loss. **DARSHAN** automates this process using state-of-the-art AI models, packaged into a responsive web-based interface for widespread, real-world screening.

---

## 🧠 Core Features

- 🔍 **Multi-Class Eye Disease Detection**  
  Real-time prediction of 25+ eye conditions using deep learning on fundus images.

- 🧪 **AI Model**  
  EfficientNetV2 (custom-tuned) trained on multi-source datasets (Kaggle, G1020, etc.) with image preprocessing and augmentation.

- 🌐 **Progressive Web App (PWA)**  
  Built with **Next.js** for seamless, installable cross-device experience.

- 🧬 **Explainable AI (XAI)**  
  Visual Grad-CAM overlays to show disease focus regions.

- ⚡ **FastAPI Backend**  
  Optimized Python API for rapid inference, hosted on GPU/Colab backend.

---

## 🗂️ Project Structure

```bash
Darshan-AI/
├── frontend/            # Next.js based PWA interface
│   ├── pages/
│   ├── components/
│   └── public/
├── backend/             # FastAPI model inference server
│   ├── predictor.py
│   ├── main.py
│   └── requirements.txt
├── model/               # Saved trained model weights
│   └── model.h5
├── assets/              # Banners, demo screenshots, Grad-CAMs
├── docs/                # Reports, presentations, README files
├── darshan_demo.mp4     # Full walkthrough video
└── README.md
