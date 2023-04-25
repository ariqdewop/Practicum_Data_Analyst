# Deskripsi Proyek

Menganalisis profil para pelanggan tersebut dan mengembangkan strategi retensi pelanggan (customer retention) di warabala pusat kebugaran Model Fitness.

# Tujuan

Mengurangin tingkat *churn* (keluar) untuk pelanggan di warabala pusat kebugaran Model Fitness.

# Hipotesis

- apakah ada fitur yang hilang? analisis nilai rata-rata dan standar deviasinya
- bagaimana nilai fitur rata-ratanya untuk kelompok di kategorikan *churn* dan tidak
- Buat histogram dan distribusi fitur untuk mereka yang keluar (churn) dan mereka yang tinggal
- Bagaimana untuk korelas antar fiturnya
- Bagaimana untuk memprediksi *churn* pengguna gym tersebut pada bulan depan dan buatlah model untuk memprediksinya
- Bagaimana menentukan kluster objectnya (pengguna)
- Bagaimana kesimpulan dan rekomendasi untuk analisis yang sudah dilakukan pada tahap-tahap sebelumnya

# Deskripsi Data

Adapun file yang digunakan yaitu `gym_churn_us.csv` yang memuat kolom:

- *`gender`* — jenis kelamin
- *`Near_Location`* — apakah pengguna tinggal atau bekerja di dekat lokasi pusat kebugaran
- *`Partner`* — apakah pengguna adalah karyawan perusahaan mitra (pusat kebugaran ini memiliki perusahaan mitra dan para karyawannya mendapatkan diskon; dalam hal ini, pusat kebugaran menyimpan informasi tentang perusahaan tempat kerja pelanggan mereka)
- *`Phone`* — apakah pengguna memberikan nomor telepon mereka
- *`Age`* — umur
- *`Lifetime`* — waktu (dalam bulan) sejak kunjungan pertama pelanggan ke pusat kebugaran
- *`Contract_period`* — 1 bulan, 3 bulan, 6 bulan, atau 1 tahun
- *`Month_to_end_contract`* — sisa bulan sebelum kontrak berakhir
- *`Group_visits`* — apakah pengguna mengambil bagian dalam sesi kelompok
- *`Avg_class_frequency_total`* — frekuensi rata-rata kunjungan per minggu selama masa hidup pelanggan
- *`Avg_class_frequency_current_month`* — frekuensi rata-rata kunjungan per minggu selama bulan sebelumnya
- *`Avg_additional_charges_total`* — jumlah total uang yang dikeluarkan untuk membayar layanan lain di pusat kebugaran: kafe, barang atletik, kosmetik, pijat, dll.
- *`Promo_friends`* — apakah pengguna awalnya melakukan pendaftaran melalui penawaran "ajak teman" (mereka menggunakan kode promo teman saat membayar keanggotaan pertama mereka)

# Libraries

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Math
- SKLearn
- Warnings
