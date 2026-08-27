---
title: "Pastry Cashier"
excerpt: 'Otomatisasi Kasir Pastry Menggunakan Teknologi Object Detection..<br/><img src="/kevin.github.io/images/pastry.jpg" width="300px">'
collection: portfolio
author_profile: true
---

### Ringkasan Proyek
Pengembangan sistem kasir cerdas (*smart cashier*) berbasis *Computer Vision* untuk mempercepat dan mengotomatisasi proses transaksi produk *pastry* melalui deteksi multi-item secara *real-time*.

### Peran & Tanggung Jawab
* **Data Curation & Preprocessing:** Mengumpulkan dataset citra melalui teknik *scraping*, menyaring gambar relevan, mengonversi format file (`.webp` ke `.jpg`/`.png`), dan menyeragamkan kanal warna (RGB).
* **Data Annotation & Splitting:** Melakukan *labeling* koordinat *bounding box* menggunakan Label Studio, serta membagi dataset menjadi *train*, *validation*, dan *test set* secara terdistribusi seimbang.
* **Model Training & Evaluation:** Merancang dan melatih arsitektur YOLOv8s menggunakan *library* Ultralytics, mengevaluasi metrik presisi (mAP/IoU), serta mengonfigurasi model untuk tahapan inferensi transaksi kasir.

### Alur Kerja
* **Dataset:** 2.500 anotasi terkurasi yang terbagi seimbang ke dalam 5 kelas *pastry*.
* **Arsitektur:** YOLOv8s (*Transfer Learning*).
* **Deployment:** Prototipe antarmuka kasir interaktif berbasis Streamlit.

### Hasil Evaluasi
* **mAP@0.5:** XX.XX% *(ganti dengan nilai Anda)*
* **Precision:** XX.XX% *(opsional)*
* **Recall:** XX.XX% *(opsional)*
* **Detection Accuracy:** XX.XX% *(atau akurasi pengujian inferensi)*

### Tech Stack & Tools
* **AI & Object Detection:** Python, Ultralytics (YOLOv8)
* **Data & Annotation:** Label Studio
* **Deployment & Versioning:** Streamlit, Git, GitHub