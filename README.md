# Deskripsi Proyek

Mempelajari dan menganalisis perilaku klien dari dua jenis paket pra-bayar, yaitu paket Surf dan pake Ultimate yang ditawarkan operator telekomunikasi Megaline dan mengetahui paket pra-bayar mana yang memberikan pendapatan perushaan lebih banyak. 

# Tujuan

Mencari perilaku klien diantara dua jenis paket pra-bayar, yaitu paket Surf dan pake Ultimate dan mengetahui paket pra-bayar mana yang memberikan pendapatan perushaan lebih banyak dengan tujuan untuk menyesuaikan anggaran iklan.

# Hipotesis

- Bagaimana perilaku klien untuk masing-masing paket pra-bayar Surf dan Ultimate
- Paket pra-bayar manakah yang mendatangkan pendaptan yang lebih banyak untuk perusahaan

# Deskripsi Data

Adapun file yang digunakan terdiri dari 5 file, yaitu `megaline_users.csv` yang memuat kolom:

- *`user_id `* — ID pengguna
- *`first_name`* — nama depan pengguna
- *`last_name`* — nama belakang pengguna
- *`age`* — usia pengguna (tahun)
- *`reg_date`* — tanggal mulai berlangganan (dd, mm, yy)
- *`churn_date`* — tanggal pengguna berhenti menggunakan layanan (jika nilainya hilang atau tidak ada, berarti paket layanan sedang digunakan saat data ini dibuat)
- *`city`* — kota tempat tinggal pengguna
- *`plan`* — nama paket telepon

file `megaline_calls.csv` yang memuat kolom:

- *`id`* — ID sesi web unik
- *`call_date`* — tanggal panggilan
- *`duration`* — durasi panggilan (dalam menit)
- *`user_id`* — ID pengguna yang melakukan panggilan

file `megaline_internet.csv` yang memuat kolom:

- *`id`* — ID sesi web unik
- *`mb_used`* — volume data yang dihabiskan selama sesi (dalam megabita)
- *`session_date`* — tanggal sesi web
- *`user_id`* — ID pengguna

file `megaline_messages.csv` yang memuat kolom:

- *`id`* — ID SMS unik
- *`message_date`* — tanggal SMS dikirim
- *`user_id`* — ID pengguna yang mengirim SMS

file `megaline_plans.csv` yang memuat kolom:

- *`plan_name`* — nama paket telepon
- *`usd_monthly_fee`* — biaya bulanan dalam dolar AS
- *`minutes_included`* — alokasi menit panggilan bulanan
- *`messages_included`* — alokasi SMS bulanan
- *`mb_per_month_included`* — alokasi volume data bulanan (dalam megabita)
- *`usd_per_minute`* — harga per menit jika telah melebihi batas alokasi paket (misalnya, jika paket memiliki alokasi 100 menit, maka penggunaan mulai dari menit ke-101 akan dikenakan biaya)
- *`usd_per_message`* — harga per SMS jika telah melebihi batas alokasi paket
- *`usd_per_gb`* — harga per ekstra gigabita data jika telah melebihi batas alokasi paket (1 GB = 1024 megabita)


# Libraries

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
