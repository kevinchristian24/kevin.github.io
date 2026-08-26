---
title: "Klasifikasi Citra Sampah Elektronik (E-Waste) 13 Kelas Berbasis Deep Learning"
excerpt: "Pengembangan model klasifikasi multi-kelas citra limbah elektronik (E-Waste) menggunakan Transfer Learning ResNet-50.<br/><img src='/images/e-waste.jpg'>"
collection: portfolio
author_profile: true
---

### Ringkasan Proyek
Penelitian tugas akhir yang bertujuan mengotomatisasi klasifikasi 13 kategori sampah elektronik (*E-Waste*) guna mengatasi isu ketidakseimbangan data dan *overfitting*.

### Alur Kerja
* **Dataset:** 17.160 citra e-waste terkurasi (*XnView MP*, *dupeGuru*).
* **Arsitektur:** ResNet-50 (*Transfer Learning* & *Fine-Tuning*).
* **Optimasi:** Dropout 0.3, Early Stopping, Grid Search.
* **Deployment:** Prototipe inferensi interaktif berbasis Streamlit.

### Hasil Evaluasi
* **Training Accuracy:** 97.72%
* **Validation Accuracy:** 96.43%
* **Testing Accuracy:** 95.00%
* **Out-of-Dataset:** 90.76%
