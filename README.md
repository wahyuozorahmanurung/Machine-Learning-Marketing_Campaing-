# Machine Learning for Marketing Campaign Analysis

## 📝 Overview
> Pada proyek ini, saya mengembangkan Pemodelan Machine Learning yang mencakup dua pendekatan utama:
> Supervised Learning: Menggunakan klasifikasi untuk mengelompokkan pelanggan berdasarkan label yang telah ditentukan.
> Unsupervised Learning: Menerapkan clustering untuk mengidentifikasi pola dalam data tanpa label yang sudah ada.
> Tujuan utama dari proyek ini adalah untuk menganalisis segmentasi pelanggan berdasarkan pola konsumsi dalam kampanye pemasaran menggunakan dataset Marketing Campaign.

## 📌 Metodologi
> Clustering (Unsupervised Learning):
> Menggunakan K-Means untuk membagi pelanggan ke dalam beberapa cluster berdasarkan perilaku pembelian.
> Klasifikasi (Supervised Learning):
> Setelah cluster terbentuk, data tersebut digunakan untuk membangun model klasifikasi guna memprediksi segmen pelanggan baru.

## 🔍 Hasil Clustering dengan K-Means

Berdasarkan hasil clustering menggunakan metode K-Means, pelanggan terbagi ke dalam dua kategori utama :
```
> Cluster 0: Pelanggan dengan daya beli lebih rendah, cenderung hemat dalam pengeluaran, dan lebih memilih produk dengan harga terjangkau.
> Cluster 1: Pelanggan dengan pendapatan lebih tinggi, memiliki pola konsumsi lebih besar, dan lebih memilih produk premium atau dalam jumlah lebih banyak.
```
## 📊 Evaluasi Model Klasifikasi
Untuk menentukan model terbaik dalam mengklasifikasikan pelanggan berdasarkan cluster yang terbentuk, beberapa algoritma diuji, dengan hasil sebagai berikut:
```
### ✅ Support Vector Machine (SVM)
Akurasi meningkat dari 88.39% menjadi 96.88% setelah tuning.
Tidak menunjukkan indikasi overfitting maupun underfitting.
Memiliki keseimbangan yang baik antara precision dan recall.

### ✅ Logistic Regression
Akurasi meningkat dari 93.97% menjadi 97.32%.
Tetap mampu generalisasi dengan baik dan efektif dalam mengenali kelas negatif.

### ✅ Decision Tree
Akurasi sedikit menurun dari 93.75% menjadi 93.30% setelah tuning.
Namun, generalisasi lebih baik dibandingkan sebelumnya.
```
## 🎯 Kesimpulan

Dari hasil evaluasi, SVM menjadi model terbaik dalam proyek ini karena memiliki:
Akurasi tinggi setelah tuning.
Kemampuan generalisasi yang baik terhadap data baru.
Ketahanan terhadap overfitting dan underfitting.
