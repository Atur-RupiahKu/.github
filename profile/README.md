# Atur RupiahKu

**Atur RupiahKu** adalah aplikasi manajemen keuangan yang dirancang untuk membantu masyarakat Indonesia dalam mengelola keuangan pribadi dengan lebih efektif dan efisien. Dibangun dengan pendekatan statistika dan sains data, aplikasi ini menawarkan tiga fitur utama yang dirancang untuk memandu pengguna menuju kesejahteraan finansial. Kami percaya bahwa pengelolaan keuangan yang baik adalah salah satu kunci untuk mendukung visi **Indonesia Emas 2045** yaitu menjadi negara maju dengan ekonomi yang berkelanjutan, tangguh, dan inklusif

## Fitur Aplikasi

### 1. Financial Forecast
Fitur ini membantu pengguna memprediksi kondisi keuangan mereka untuk beberapa hari ke depan berdasarkan data historis pendapatan dan pengeluaran. Kami menggunakan model **XGBoost** untuk melakukan forecasting keuangan pada dua kasus utama:
- **Kasus Penghasilan Tidak Tetap :** Dengan memanfaatkan data bangkitan, model **XGBoost** menghasilkan error sebesar **1,7k**.[Notebook hasil pemodelan kasus penghasilan tidak tetap](https://github.com/Atur-RupiahKu/Forecasting-Keuangan/blob/main/Notebook%20Penghasilan%20Tidak%20Tetap.ipynb) 
- **Kasus Penghasilan Tetap:** Dengan model yang sama, error prediksi untuk mahasiswa yang mendapatkan penghasilan bulanan dari orang tua mencapai **69k**.[Notebook hasil pemodelan kasus penghasilan tetap](https://github.com/Atur-RupiahKu/Forecasting-Keuangan/blob/main/Notebook%20Penghasilan%20Tetap.ipynb)
Fitur ini bertujuan untuk membantu pengguna dalam merencanakan keuangan dengan lebih baik, menghindari defisit, dan mengoptimalkan penggunaan pendapatan mereka. 

Repo: [Explore repo untuk fitur ini](https://github.com/Atur-RupiahKu/Forecasting-Keuangan)

Demo: [Dashboard Untuk Fitur 1](https://dashboard-otpe2yfbbiaam82dvkr2gw.streamlit.app/)

### 2. Loan Risk
Fitur ini menghitung risiko gagal bayar pinjaman berdasarkan beberapa variabel seperti gaji, jumlah pinjaman, dan tingkat bunga. Kami menggunakan model **Light Gradient Boosting Machine (LGBM)** yang terbukti memberikan akurasi terbaik dengan **F1 Test Score sebesar 92%**. Data yang digunakan telah di-scale dan disesuaikan dengan kondisi keuangan di Indonesia.

Fitur ini bertujuan membantu pengguna dalam memahami kemampuan mereka membayar pinjaman, sehingga dapat mengurangi risiko gagal bayar yang dapat berdampak negatif pada stabilitas keuangan pribadi dan nasional.

Dataset: [Link Kaggle Dataset](https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval?select=Loan.csv) 

Repo: [Explore repo untuk fitur ini](https://github.com/Atur-RupiahKu/Rekomendasi-Resiko-Pinjaman)

Demo: [Dashboard Untuk Fitur 2](https://dashboard-eoctwdweskirpnpxvz38cl.streamlit.app/)

### 3. Video Edukasi dan Platform Konsultasi
Fitur ini menyediakan berbagai video edukasi keuangan yang interaktif dan mudah dipahami, serta platform marketplace untuk menyewa konsultan keuangan. Dengan adanya fitur ini, pengguna bisa belajar tentang pengelolaan keuangan secara mandiri, sekaligus mendapatkan bantuan profesional jika diperlukan.

Fitur ini bertujuan untuk meningkatkan literasi keuangan masyarakat Indonesia, sekaligus membuka lapangan pekerjaan baru bagi konsultan keuangan yang ingin bergabung dalam platform kami.


## Dampak dan Kontribusi
Aplikasi **Atur RupiahKu** tidak hanya membantu masyarakat Indonesia dalam mengelola keuangan, tetapi juga mendukung tercapainya target ekonomi **Indonesia Emas 2045** dengan:
- Meningkatkan literasi keuangan masyarakat untuk mengelola pendapatan dan pengeluaran secara lebih bijaksana.
- Membantu memprediksi kemampuan pembayaran pinjaman, sehingga mengurangi risiko gagal bayar.
- Menciptakan lapangan kerja baru melalui fitur marketplace konsultan keuangan.



## UI Tampilan Atur RupiahKu

Berikut adalah tampilan UI dari aplikasi Atur RupiahKu. Anda dapat melihatnya secara lengkap di PDF berikut:

[Tampilan UI](https://github.com/Atur-RupiahKu/.github/blob/main/Mockup%20Atur%20RupiahKu.pdf)
<embed src="https://github.com/Atur-RupiahKu/.github/blob/main/Mockup%20Atur%20RupiahKu.pdf" width="800px" height="600px" />

## Tentang Kami
Tim **Atur RupiahKu** terdiri dari tiga mahasiswa Institut Teknologi Sepuluh Nopember (ITS) Surabaya sebagai berikut.
1. Fadhel Iqbal Hidayatullah - Mahasiswa S1 Sains Data
2. Saeful Fikri - Mahasiswa S1 Statistika
3. Abdillah Ilham - Mahasiswa S1 Statistika

Kami berkomitmen untuk menciptakan solusi berbasis teknologi yang membantu pengguna dalam mencapai kesejahteraan finansial.

Jelajahi repositori kami untuk informasi lebih lanjut:
- [Forecasting Kondisi Keuangan](https://github.com/Atur-RupiahKu/Forecasting-Keuangan)
- [Rekomendasi Risiko Pinjaman](https://github.com/Atur-RupiahKu/Rekomendasi-Resiko-Pinjaman)

## Kontak
Email: fiqbalh12@gmail.com

