# 🛒 Dashboard Association Rules Recommendation

Aplikasi web berbasis **Streamlit** untuk memberikan rekomendasi produk yang dipersonalisasi. Proyek ini mengintegrasikan pendekatan **Content-Based Filtering** dan **Collaborative Filtering** untuk mengoptimalkan strategi penjualan dan membantu pelanggan menemukan produk yang relevan.

🔗 Live Demo: collaborativerules.streamlit.app

---

## 🎯 Tentang Project
Proyek ini bertujuan untuk menyediakan sistem rekomendasi yang membantu pelanggan menemukan produk sesuai dengan minat mereka. Dengan memanfaatkan histori transaksi, aplikasi ini memberikan saran berdasarkan karakteristik produk serta perilaku belanja pelanggan lain.

---

## 🚀 Fitur Utama
* **Product Recommendation:** Saran produk otomatis berdasarkan input pilihan pengguna.
* **Content-Based Filtering:** Menampilkan produk dengan atribut atau karakteristik serupa.
* **Collaborative Filtering:** Menampilkan produk yang disukai oleh pelanggan dengan perilaku belanja yang mirip.
* **Interactive Dashboard:** Eksplorasi data transaksi dan sistem rekomendasi secara *real-time* melalui antarmuka yang intuitif.

---

## 📊 Metodologi

### 1. Content-Based Filtering
Menggunakan kemiripan fitur produk untuk merekomendasikan item yang memiliki karakteristik serupa dengan produk yang dipilih oleh pengguna.
Contoh : 

KNITTED UNION FLAG HOT WATER BOTTLE
→ WHITE SKULL HOT WATER BOTTLE

### 2. Collaborative Filtering
Menganalisis pola pembelian antar pelanggan untuk menemukan produk yang sering dibeli oleh pengguna dengan minat yang sama.

Contoh :
RED WOOLLY HOTTIE WHITE HEART
→ SCOTTIE DOG HOT WATER BOTTLE

---

## 🛠️ Tech Stack

* **Language:** Python
* **Framework:** Streamlit
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Deployment:** Streamlit Community Cloud

---

## 📂 Struktur Project

```text
assorules/
├── app.py                # Main Streamlit application
├── model/                # Pre-trained models & processed data
├── requirements.txt      # Dependencies
└── README.md

---

## 🚀 Cara Menjalankan Lokal

1. Clone repository
git clone https://github.com/hastisf/association-rules.git

2. Masuk ke folder project
cd assorules

3. Install dependency
pip install -r requirements.txt

4. Jalankan aplikasi
streamlit run app.py

Aplikasi akan berjalan di:
http://localhost:8501

---

## 🌐 Deploy

Aplikasi dideploy menggunakan Streamlit Community Cloud sehingga dapat diakses secara online melalui browser tanpa instalasi tambahan.

---

## 🚀 Fitur Dashboard

| Fitur | Keterangan |
| :--- | :--- |
| **Product Recommendation** | Rekomendasi produk berdasarkan item yang dipilih pengguna |
| **Content-Based Filtering** | Menampilkan produk dengan karakteristik atau atribut serupa |
| **Collaborative Filtering** | Menampilkan produk yang disukai oleh pelanggan dengan perilaku serupa |
| **Market Basket Analysis** | Analisis kombinasi produk yang sering dibeli bersama dalam satu transaksi |
| **Interactive Dashboard** | Visualisasi dan eksplorasi data transaksi secara interaktif |

---

## 📈 Manfaat Bisnis
* **Personalisasi Pengalaman:** Meningkatkan relevansi produk bagi setiap pelanggan dengan rekomendasi yang dipersonalisasi.
* **Peningkatan Engagement:** Mempercepat proses pencarian produk bagi pelanggan sehingga waktu interaksi di platform lebih efisien.
* **Data-Driven Insight:** Memahami pola preferensi belanja pelanggan secara mendalam untuk mendukung pengambilan keputusan pemasaran yang lebih tepat sasaran.

---

## ⚠️ Catatan
Hasil rekomendasi bergantung pada kualitas dan jumlah data transaksi yang tersedia.
Tidak semua produk akan menghasilkan association rules yang kuat.
Project ini dibuat untuk tujuan pembelajaran data mining, machine learning, dan sistem rekomendasi pada data retail.
