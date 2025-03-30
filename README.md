# Machine-Learning-Marketing_Campaing-

Pada proyek kali ini, saya mengembangkan sebuah Pemodelan Machine Learning yang mencakup dua pendekatan utama, yaitu supervised learning dan unsupervised learning. Dalam pendekatan supervised learning, saya menerapkan teknik klasifikasi untuk membangun model yang mampu mengelompokkan data berdasarkan label yang telah ditentukan sebelumnya. Sementara itu, dalam unsupervised learning, saya menggunakan metode clustering untuk mengelompokkan data tanpa adanya label tertentu, sehingga pola dalam data dapat ditemukan secara otomatis.

Dataset yang digunakan dalam proyek ini adalah Marketing Camping, yang bertujuan untuk menganalisis segmentasi pelanggan berdasarkan pola tertentu. Langkah pertama yang saya lakukan adalah menerapkan proses clustering guna menentukan kelompok atau segmen dalam data secara tidak terawasi. Setelah proses clustering selesai dan cluster telah terbentuk, saya melanjutkan dengan klasifikasi menggunakan data yang telah dikelompokkan tersebut. Tujuannya adalah untuk membangun model prediktif yang dapat secara otomatis mengklasifikasikan data baru ke dalam cluster yang sesuai, sehingga menghasilkan pemodelan yang lebih terstruktur dan dapat digunakan untuk analisis lebih lanjut.

Hasil Clustering dengan K-Means
Berdasarkan hasil clustering menggunakan metode K-Means, pelanggan dapat dikelompokkan ke dalam dua kategori utama dengan karakteristik yang berbeda:

Cluster 0: Pelanggan dengan daya beli lebih rendah, cenderung hemat dalam pengeluaran, dan lebih memilih produk dengan harga yang lebih terjangkau.

Cluster 1: Pelanggan dengan pendapatan lebih tinggi, menunjukkan pola konsumsi yang lebih besar, serta memiliki preferensi terhadap produk premium atau dalam jumlah lebih besar.

Evaluasi Model Klasifikasi
Setelah proses clustering, saya melakukan klasifikasi untuk menentukan model terbaik dalam mengklasifikasikan pelanggan berdasarkan cluster yang telah terbentuk. Hasil evaluasi menunjukkan performa beberapa model sebagai berikut:

Support Vector Machine (SVM) menjadi model terbaik dengan peningkatan akurasi yang signifikan, dari 88.39% menjadi 96.88% setelah tuning. Model ini tidak menunjukkan indikasi overfitting maupun underfitting, mampu mengenali pola data dengan baik, serta memiliki keseimbangan antara precision dan recall yang optimal.

Logistic Regression juga menunjukkan performa yang stabil dengan akurasi meningkat dari 93.97% menjadi 97.32%. Model ini tetap mampu melakukan generalisasi dengan baik dan efektif dalam mengenali kelas negatif.

Decision Tree, meskipun memiliki akurasi awal yang cukup baik, mengalami sedikit penurunan dari 93.75% menjadi 93.30% setelah tuning. Namun, generalisasinya lebih baik dibandingkan sebelumnya.
