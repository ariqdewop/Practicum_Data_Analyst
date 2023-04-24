# Deskripsi Proyek

Menganalisis data kunjungan pengguna dan pembelian produk di situs website Y.Afisha

# Tujuan

Untuk mengoptimalkan biaya pemasaran produk Y.Afisha

# Hipotesis

- Berapa jumlah uang yang dihasilkan oleh para pengguna yang melakukan pembelian produk Y.Afisha
- Bagaimana data untuk pembelian produk Y.Afisha oleh pengguna selama periode yang sudah ditentukan
- Bagaimana biaya pemasaran akan digunakan setelah melakukan analisis ini

# Deskripsi Data

Adapun file yang digunakan yaitu `visits_log_us.csv` yang memuat kolom:

- *`Uid`* — ID pengguna
- *`Device`* — Perangkat pengguna
- *`Start Ts`* — Tanggal dan waktu dimulainya sesi
- *`End Ts`* — Tanggal dan waktu berakhirnya sesi
- *`Source Id`* — ID sumber iklan, sumber yang digunakan pengguna untuk datang ke situs web

file `orders_log_us.csv` yang memuat kolom:

- *`Uid`* — ID pengguna yang membuat pesanan
- *`Buy Ts`* — Tanggal dan waktu pesanan dibuat
- *`Revenue`* — Pendapatan Y.Afisha dari pesanan tersebut

file `costs_us.csv` yang memuat kolom:

- *`source_id`* — ID sumber iklan
- *`dt`* — Tanggal
- *`costs`* — Pengeluaran untuk sumber iklan pada tanggal tersebut

# Libraries

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Warnings
