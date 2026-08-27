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
* **Model Training & Evaluation:** Merancang dan melatih arsitektur YOLOv8n menggunakan *library* Ultralytics, mengevaluasi metrik presisi (mAP/IoU), serta mengonfigurasi model untuk tahapan inferensi transaksi kasir.

### Alur Kerja
* **Dataset:** 2.500 anotasi terkurasi yang terbagi seimbang ke dalam 5 kelas *pastry*.
* **Arsitektur:** YOLOv8s (*Transfer Learning*).
* **Deployment:** Prototipe antarmuka kasir interaktif berbasis Streamlit.

### Hasil Evaluasi
* **mAP@50:** 97%.0% 
* **Precision:** 92.6% 
* **Recall:** 93.4% 
* **mAP@50-90:**76.4%


### Tech Stack & Tools
* **AI & Object Detection:** Python, Ultralytics (YOLOv8)
* **Tool Scraping:** [Scraping](https://github.com/QianyanTech/Image-Downloader.git)
* **Data & Annotation:** Label Studio
* **Deployment & Versioning:** Streamlit, Git, GitHub

## Link
* **Link Demo:**[Demo](https://pastry-crx6mmxbaafnaohmodohq9.streamlit.app/)
* **Repository:**[Repository](https://github.com/kevinchristian24/Pastry.git)