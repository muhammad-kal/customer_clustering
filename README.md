# Customer Transaction Analytics - Clustering

## 🔍 Deskripsi Proyek

Proyek ini bertujuan untuk melakukan segmentasi pelanggan berdasarkan perilaku transaksi mereka menggunakan algoritma **K-Means Clustering**. Proses ini melibatkan pembersihan data, pra-pemrosesan, penentuan jumlah cluster optimal menggunakan Elbow Method, dan akhirnya interpretasi karakteristik dari setiap cluster yang terbentuk. Tujuan akhirnya adalah untuk memberikan wawasan yang dapat digunakan untuk strategi bisnis yang lebih tertarget.

---

## 📁 Struktur File

- `[Clustering]_Submission_Akhir_BMLP_Muhammad_Haikal.ipynb`  
  Notebook utama yang berisi semua langkah proses, mulai dari pemuatan data, pra-pemrosesan data (penanganan nilai null, encoding, scaling), implementasi K-Means clustering, evaluasi (menggunakan Elbow Method untuk menentukan jumlah cluster), hingga interpretasi hasil segmentasi pelanggan.

- `data_clustering.csv`  
  Dataset yang dihasilkan setelah proses clustering. File ini berisi fitur-fitur yang telah diproses dan kolom 'Target' yang menunjukkan label cluster untuk setiap pelanggan.

- `model_clustering.h5`  
  File model K-Means yang telah dilatih dan disimpan menggunakan joblib. Model ini dapat dimuat kembali untuk penggunaan di masa mendatang.

- `requirements.txt`  
  Berisi daftar library Python yang digunakan dalam proyek beserta versi yang direkomendasikan untuk memastikan reproduktifitas.

---

## ▶️ Cara Menjalankan

1.  **Clone Repositori (jika ada)**
    Jika proyek ini ada dalam sebuah repositori Git, clone terlebih dahulu.

2.  **Install Dependencies**
    Pastikan Anda memiliki Python terinstal. Kemudian, install semua library yang dibutuhkan menggunakan pip:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Jalankan Notebook**
    Buka dan jalankan notebook `[Clustering]_Submission_Akhir_BMLP_Muhammad_Haikal.ipynb` menggunakan Jupyter Notebook atau JupyterLab. Pastikan untuk menjalankan semua sel secara berurutan untuk mereplikasi hasil.

---
