# 🛒 E-Commerce Customer Churn Prediction

### 1. Ringkasan Proyek
Proyek ini menganalisis perilaku dan data transaksi pelanggan untuk memprediksi kemungkinan churn (berhenti menggunakan layanan) dalam konteks e-commerce. Tujuan utamanya adalah untuk mengidentifikasi pelanggan yang berisiko churn, memahami faktor-faktor penyebabnya, dan memberikan strategi retensi yang dapat ditindaklanjuti.

🎯 Tujuan Utama:
- Memprediksi churn pelanggan dengan akurasi dan efisiensi tinggi menggunakan machine learning.
- Mengidentifikasi fitur-fitur penting yang memengaruhi churn, baik dari perilaku maupun demografi.
- Melakukan segmentasi pelanggan berdasarkan risiko dan nilai ekonomi untuk strategi retensi yang lebih tajam.

### 2. Sumber Data
Dataset Pelanggan – Berisi data perilaku, demografi, dan transaksi pelanggan e-commerce.

Fitur Turunan – Fitur-fitur yang direkayasa seperti IsNewCustomer, Tenure_Cashback, Complain_LowSat, dll., untuk meningkatkan interpretabilitas dan performa model.

### 3. Tools yang Digunakan
- Bahasa Pemrograman: Python (Pandas, NumPy, scikit-learn, XGBoost)
- Visualisasi: Matplotlib, Seaborn
- Modeling: XGBoost, Logistic Regression
- Lingkungan Notebook: Jupyter Notebook via Visual Studio Code

Version Control: Git & GitHub

<img width="547" height="421" alt="image" src="https://github.com/user-attachments/assets/29c39f4f-5f00-4269-8056-d19a48e781f6" />


### 4. Ringkasan Temuan
4.1 Insight Bisnis
Performa Model:

- Precision: 92.79%
- Recall: 76.30%
- F1 Score: 83.74%
- PR AUC: 90.33%

Fitur Penting:

Tenure_Cashback, IsNewCustomer, Complain, LowSatisfaction, PreferredOrderCat_*

Segmentasi Risiko & Nilai Pelanggan:
<img width="756" height="164" alt="image" src="https://github.com/user-attachments/assets/affcbac3-e424-442a-a606-470fdd119e14" />

* Model berhasil mengidentifikasi pelanggan berisiko tinggi dengan presisi tinggi, memungkinkan strategi retensi yang dapat mencegah kerugian lebih dari Rp 350 juta.

4.2 Rekomendasi Strategis

Prioritas Retensi:
- Pelanggan baru
- Pelanggan lama tanpa cashback
- Pelanggan dengan keluhan dan kepuasan rendah

Kampanye Tersegmentasi:
- Gunakan preferensi kategori belanja dan status pernikahan untuk pendekatan yang lebih personal.

Strategi Operasional:
- Integrasikan skor churn ke sistem CRM
- Pantau metrik PR AUC dan recall secara berkala untuk mendeteksi drift model

### 5. Kontak 

Nama: Muhamad Farhan Budiana

Email: [farhan.budiana19@gmail.com]

LinkedIn: (https://www.linkedin.com/in/muhamadfarhanbudiana/)

 Appendix: 
https://www.canva.com/design/DAG4W6r9FSw/8cSht9EhBDW3V1UzI_ZHOg/edit
https://drive.google.com/drive/folders/1PITb78NtK9Ra6wOkQdXCIgItZkj29Ves
https://github.com/FarhanBud/E-Commerce-Customer-Churn
