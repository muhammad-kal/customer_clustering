# Customer Transaction Analytics - Clustering & Classification

## 🔍 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis data transaksi pelanggan guna melakukan segmentasi pelanggan dan kemudian membuat model klasifikasi untuk memprediksi segmen tersebut.

1.  **Clustering** 📊
    Proses ini melibatkan segmentasi pelanggan berdasarkan berbagai fitur transaksi menggunakan algoritma K-Means. Tujuannya adalah untuk mengelompokkan pelanggan ke dalam cluster-cluster yang memiliki karakteristik serupa. Langkah-langkah utama meliputi pra-pemrosesan data (penanganan nilai null, scaling, encoding), penentuan jumlah cluster optimal menggunakan Elbow Method, dan pelatihan model K-Means.

2.  **Klasifikasi** 🎯
    Setelah pelanggan disegmentasi ke dalam cluster, hasil clustering tersebut digunakan sebagai variabel target. Model klasifikasi, seperti Decision Tree, dilatih untuk memprediksi cluster pelanggan berdasarkan fitur-fitur transaksi mereka. Kinerja model dievaluasi menggunakan metrik seperti akurasi dan F1-score.

---

## 📁 Struktur File

-   `[Clustering]_Submission_Akhir_BMLP_Muhammad_Haikal.ipynb`
    Notebook yang berisi semua langkah untuk pra-pemrosesan data, analisis eksploratif (EDA), proses clustering dengan K-Means, interpretasi cluster, dan penyimpanan hasil clustering.

-   `[Klasifikasi]_Submission_Akhir_BMLP_Muhammad_Haikal.ipynb`
    Notebook yang digunakan untuk memuat data hasil clustering, melatih model klasifikasi (Decision Tree), mengevaluasi model, dan menyimpan model klasifikasi.

-   `data_clustering.csv`
    Dataset yang dihasilkan dari notebook clustering. Berisi fitur-fitur yang telah diproses dan kolom 'Target' yang merupakan label cluster untuk setiap pelanggan. File ini digunakan sebagai input untuk notebook klasifikasi.

-   `model_clustering.h5`
    File model K-Means yang telah dilatih dan disimpan dari notebook clustering.

-   `decision_tree_model.h5`
    File model Decision Tree yang telah dilatih dan disimpan dari notebook klasifikasi.

-   `requirements.txt`
    File yang berisi daftar pustaka (library) Python yang dibutuhkan untuk menjalankan kedua notebook beserta versi yang direkomendasikan.

---

## ▶️ Cara Menjalankan

**Clone repositori dan install dependencies**  
  ```bash
  pip install -r requirements.txt
