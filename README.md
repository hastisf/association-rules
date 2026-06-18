# Retail Recommendation Engine

Aplikasi web berbasis **Streamlit** untuk memberikan rekomendasi produk yang dipersonalisasi. Proyek ini mengintegrasikan pendekatan **Content-Based Filtering** dan **Collaborative Filtering** untuk mengoptimalkan strategi penjualan dan membantu pelanggan menemukan produk yang relevan.

## 📑 Daftar Isi
- [Tentang Project](#-tentang-project)
- [Fitur Utama](#-fitur-utama)
- [Metodologi](#-metodologi)
- [Tech Stack](#-tech-stack)
- [Cara Menjalankan](#-cara-menjalankan)
- [Manfaat Bisnis](#-manfaat-bisnis)

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

### 2. Collaborative Filtering
Menganalisis pola pembelian antar pelanggan untuk menemukan produk yang sering dibeli oleh pengguna dengan minat yang sama.

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

## ⚙️ Cara Menjalankan

1. **Clone repository:**
   ```bash
   git clone [https://github.com/username/assorules.git](https://github.com/username/assorules.git)
   cd assorules

pip install -r requirements.txt
streamlit run app.py

## 📈 Manfaat Bisnis
* **Personalisasi Pengalaman:** Meningkatkan relevansi produk bagi setiap pelanggan dengan rekomendasi yang dipersonalisasi.
* **Peningkatan Engagement:** Mempercepat proses pencarian produk bagi pelanggan sehingga waktu interaksi di platform lebih efisien.
* **Data-Driven Insight:** Memahami pola preferensi belanja pelanggan secara mendalam untuk mendukung pengambilan keputusan pemasaran yang lebih tepat sasaran.

---

## 🌐 Live Demo
Akses aplikasi melalui browser tanpa perlu instalasi:
👉 **[collaborativerules.streamlit.app](https://collaborativerules.streamlit.app)**

---

*Dibuat untuk tujuan edukasi dan pengembangan sistem rekomendasi retail.*
