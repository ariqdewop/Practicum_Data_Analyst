# Deskripsi Proyek

Melakukan eksprimen A/B Testing *recommender_system_test* di sebuah toko daring internasional.

# Tujuan

Menguji perubahan terkait pengenalan sistem rekomendasi (recommender_system_test) yang telah ditingkatkan.

# Hipotesis

- Bagaimana konversi di setiap tahapan corong
- Apakah jumlah peristiwa per pengguna terdistribusi secara merata di seluruh sampel
- Apakah ada pengguna yang berada di kedua sampel
- Bagaimana pendistribusian jumlah peristiwa berdasarkan hari
- Apakah data Anda memiliki ciri-ciri khusus yang harus dipertimbangkan sebelum memulai A/B testing
- Bagaimana hasil dari *Z-Test* dari kedua sampel tersebut

# Deskripsi Data

Ada 4 file yang digunakan, yaitu:

- *`ab_project_marketing_events_us.csv`* — Kalender event pemasaran untuk tahun 2020
- *`final_ab_new_users_upd_us.csv`* — Semua pengguna yang mendaftar di toko daring dari tanggal 7 sampai 21 Desember 2020
- *`final_ab_events_upd_us.csv`* — Semua peristiwa dari pengguna baru sepanjang periode 7 Desember 2020 sampai 1 Januari 2021
- *`final_ab_participants_upd_us.csv`* — Tabel yang berisi daftar peserta eksperimen

Adapun file yang digunakan yaitu `ab_project_marketing_events_us.csv` yang memuat kolom:

- *`name`* — Nama event pemasaran
- *`regions`* — Kawasan tempat kampanye iklan akan berlangsung
- *`start_dt`* — Tanggal awal kampanye
- *`finish_dt`* — Tanggal akhir kampanye

file `final_ab_new_users_upd_us.csv` yang memuat kolom:

- *`user_id`* — User ID
- *`first_date`* — Tanggal pendaftaran (sign up)
- *`region`* — Wilayah/negara
- *`device`* — Perangkat yang digunakan untuk mendaftar

file `final_ab_events_upd_us.csv` yang memuat kolom:

- *`user_id`* — User ID
- *`event_dt`* — Tanggal dan waktu peristiwa
- *`event_name`* — Nama jenis peristiwa
- *`details`* — Data tambahan terkait peristiwa tersebut (misalnya, jumlah total pesanan dalam USD untuk peristiwa `purchase`)

file `final_ab_participants_upd_us.csv` yang memuat kolom:

- *`user_id`* — User ID
- *`ab_test`* — Nama eksperimen
- *`group`* — Kelompok eksperimen pengguna berasal

# Libraries

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Math
- Warnings
