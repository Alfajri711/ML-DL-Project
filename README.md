# ML-DL-Project
# **Project 04_01_Earth_Muhammad-Asri-Alfajri.ipynb**

**Judul Proyek**
Analisis Pengguna yang Berhenti Menggunakan Layanan Bank

**Deskripsi Singkat**
Proyek ini bertujuan untuk memprediksi apakah seorang nasabah bank akan berhenti menggunakan layanan bank berdasarkan data demografis dan perilaku nasabah tersebut.

**Data**
Data yang digunakan berasal dari file SC_HW1_bank_data.csv. Data berisi informasi seperti:

**Demografi nasabah (umur, jenis kelamin, lokasi)**
Perilaku nasabah (jumlah produk yang dimiliki, apakah memiliki kartu kredit, dan lain-lain)
Target: Apakah nasabah berhenti menggunakan layanan bank (kolom Exited)

**Pemodelan**
Dilakukan pemodelan menggunakan 3 model:
1. Logistic Regression
2. K-Nearest Neighbors
3. Random Forest
Ketiga model dievaluasi menggunakan metrik akurasi, precision, recall, F1-score, dan confusion matrix.

**Kesimpulan**
Berdasarkan evaluasi, model Random Forest merupakan model terbaik karena memiliki akurasi, F1-score, dan recall yang lebih tinggi dibandingkan model lainnya.

# **Project 04_02_Earth_Muhammad-Asri-Alfajri.ipynb**

**Clustering Data Acak Menggunakan K-Means**
**Deskripsi Singkat**
Melakukan clustering pada data acak (random) menggunakan algoritma K-Means. Data acak yang digunakan di-generate secara random.

**Data**
Data berasal dari file cluster_s1.csv yang berisi 500 baris data acak dengan kolom:
x: nilai acak 1
y: nilai acak 2

**Tahapan**
Beberapa tahapan yang dilakukan:
1. Import library yang dibutuhkan
2. Membaca data dari file csv
3. Melakukan visualisasi data dengan scatter plot
4. Mencari jumlah cluster terbaik dengan Elbow Method
5. Melakukan clustering dengan K-Means
6. Menghitung silhouette score untuk mengevaluasi hasil cluster
7. Melakukan visualisasi hasil cluster dengan scatter plot dan memberi warna berbeda untuk setiap cluster
   
**Kesimpulan**
Dari analisis Elbow Method, didapatkan bahwa jumlah cluster terbaik adalah 15 cluster. Kemudian dilakukan proses clustering menggunakan K-Means dengan 15 cluster. Hasil cluster dievaluasi menggunakan silhouette score.

# **Project 04_03_Earth_Muhammad-Asri-Alfajri.ipynb**

**Klasifikasi Digit Tulisan Tangan MNIST dengan PyTorch**
**Deskripsi Singkat**
Melakukan klasifikasi digit tulisan tangan pada dataset MNIST menggunakan jaringan syaraf (neural network) sederhana dengan PyTorch.

**Dataset**
Dataset MNIST terdiri dari 70.000 gambar grayscale 28x28 piksel yang berisi digit tulisan tangan 0 sampai 9.
Dataset dibagi menjadi:
1. 60.000 data latih
2. 10.000 data uji

**Arsitektur Model**
Model terdiri dari 3 lapisan fully connected layer dengan aktivasi ReLU:
1. Layer 1: 128 node
2. Layer 2: 64 node
3. Layer 3 (output): 10 node (sesuai jumlah kelas 0-9)
Fungsi loss menggunakan Cross Entropy Loss dan optimizer Adam dengan learning rate 0.001.

**Hasil**
Melalui 10 epoch training, didapatkan akurasi sekitar 97.5% pada data testing. Hal ini menunjukkan model berhasil mengklasifikasikan digit tulisan tangan dengan baik. Confusion matrix dan classification report juga menunjukkan performa yang baik untuk semua kelas digit.

# **Project 04_Bonus_Earth_Muhammad-Asri-Alfajri.ipynb**
