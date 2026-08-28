---
title: "Klasifikasi Citra Sampah Elektronik (E-Waste) 13 Kelas Berbasis Deep Learning"
excerpt: "Pengembangan model klasifikasi multi-kelas citra limbah elektronik (E-Waste) menggunakan Transfer Learning ResNet-50.<br/><img src='/kevin.github.io/images/e-waste.jpg' width='300px'>"
collection: portfolio
author_profile: true
---

### Ringkasan Proyek
Penelitian tugas akhir yang bertujuan mengotomatisasi klasifikasi 13 kategori sampah elektronik (*E-Waste*) guna mengatasi isu ketidakseimbangan data dan *overfitting*.

### Alur Kerja
* **Dataset:** 17.160 citra e-waste.
* **Arsitektur:** ResNet-50 (*Transfer Learning* & *Fine-Tuning*).
* **Optimasi:** Dropout 0.3, Early Stopping, Grid Search.
* **Deployment:** Prototipe inferensi interaktif berbasis Streamlit.

### Hasil Evaluasi
* **Training Accuracy:** 97.72%
* **Validation Accuracy:** 96.43%
* **Testing Accuracy:** 95.00%
* **Out-of-Dataset:** 90.76%

### Tech Stack & Tools
* **Bahasa & Framework:** Python, TensorFlow, Keras, OpenCV
* **Platform:** Google Colab, Git / GitHub
* **Deployment:** Streamlit

## Sumber & Pengumpulan Dataset
* **Kaggle Datasets:**
  * [Solar Panel Images](https://www.kaggle.com/datasets/pythonafroz/solar-panel-images)
  * [E-Waste Image Dataset](https://www.kaggle.com/datasets/akshat103/e-waste-image-dataset)
  * [E-Waste Compressed](https://www.kaggle.com/datasets/mxtuhin/e-waste-compressed)
  * [E-Waste by Ranti Maulidaningsih](https://www.kaggle.com/datasets/rantimaulidaningsih/e-waste)
* **GitHub Dataset:** [EWasteNet Repository](https://github.com/NifulIslam/EWasteNet-A-Two-Stream-DeiT-Approach-for-E-Waste-Classification.git)
* **Web Scraping:** Pengumpulan citra web mandiri via [Image-Downloader](https://github.com/QianyanTech/Image-Downloader.git)

## Link Demo
* **Link Demo:**[Demo](https://skripsi-4qqdhhzwyh76t3m52wwrzc.streamlit.app/)
* **Repository:**[Repository](https://github.com/kevinchristian24/Skripsi.git)