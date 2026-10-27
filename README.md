Analisis Sentimen Review Menggunakan LSTM
Aplikasi machine learning untuk melakukan analisis sentimen pada teks review menggunakan model Long Short-Term Memory (LSTM). Aplikasi ini dibuat sebagai bagian dari tugas mata kuliah Text Mining dengan menerapkan teknik vibe coding dan menyediakan antarmuka pengguna berbasis Streamlit.
🚀 Live Demo
Aplikasi yang telah di-deploy dapat diakses melalui tautan berikut:

Analisis Sentimen Review — Streamlit App
🎯 Tujuan Proyek
- Membangun aplikasi analisis sentimen berbasis machine learning.
- Melatih model menggunakan arsitektur LSTM untuk memproses teks.
- Menyediakan antarmuka yang mudah digunakan untuk mencoba analisis sentimen.
- Melakukan deployment aplikasi agar dapat diakses secara online melalui Streamlit.
📊 Dataset
Dataset yang digunakan berasal dari repositori GitHub berikut:
- Dataset: data.csv
- Kolom pada dataset: text dan label
Dataset ini digunakan sebagai sumber data untuk proses pelatihan model analisis sentimen.
🧠 Metode
Model yang digunakan adalah Long Short-Term Memory (LSTM), yaitu jenis Recurrent Neural Network (RNN) yang dirancang untuk mempelajari pola berurutan dalam data. Dalam proyek ini, LSTM digunakan untuk mempelajari pola pada teks review dan memprediksi label sentimennya.

Secara umum, alur pengerjaan meliputi:
1. Memuat dataset.
2. Menyiapkan dan melakukan preprocessing teks.
3. Mengubah teks menjadi representasi numerik yang dapat diproses oleh model.
4. Melatih model LSTM menggunakan data berlabel.
5. Mengintegrasikan model ke dalam aplikasi Streamlit.
6. Melakukan deployment aplikasi agar dapat digunakan secara online.
🖥️ Aplikasi
Aplikasi menyediakan antarmuka berbasis Streamlit untuk mencoba analisis sentimen pada teks review. Silakan buka tautan Live Demo di atas untuk menggunakan aplikasi yang telah di-deploy.
🛠️ Teknologi
- Python — bahasa pemrograman
- LSTM — model deep learning untuk pemrosesan teks berurutan
- Streamlit — framework untuk membangun antarmuka aplikasi web
- GitHub — sumber dataset
▶️ Menjalankan Secara Lokal
Untuk menjalankan aplikasi di komputer sendiri:
1. Clone atau unduh repositori proyek.
2. Pastikan Python telah terpasang.
3. Instal library yang dibutuhkan sesuai file dependensi proyek (requirements.txt, jika tersedia).
4. Jalankan aplikasi Streamlit dengan nama file aplikasi utama yang digunakan dalam proyek:
   streamlit run nama_file_aplikasi.py
   Ganti nama_file_aplikasi.py dengan nama file Python utama pada repositori.
📌 Catatan
README ini menjelaskan tujuan, dataset, metode utama, dan tautan deployment proyek. Detail implementasi seperti konfigurasi model, pembagian data, metrik evaluasi, serta nama file aplikasi dapat ditambahkan sesuai kode yang benar-benar digunakan.
👩‍💻 Author
Leora Natania
Text Mining Assignment
