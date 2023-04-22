# Deskripsi Proyek

Memahami preferensi penumpang dan dampak faktor eksternal terhadap perjalanan dari perusahaan berbagi tumpangan (Ride-Sharing) yaitu Zuber.

# Tujuan

 Menguji hipotesis terkait pengaruh cuaca terhadap frekuensi perjalanan.

# Hipotesis

- Bagaimana dampak dari faktor eksternal suatu perjalanan dapat mempengaruhi prefrensi penumpang
- Apakah cuaca mempengaruhi frekuensi perjalanan

# Deskripsi Data

Adapun file yang digunakan yaitu `project_sql_result_01.csv` yang memuat kolom:

- *`company_name`* — Nama perusahaan taksi
- *`trips_amount`* — Jumlah perjalanan untuk setiap perusahaan taksi pada tanggal 15-16 November 2017

file `project_sql_result_04.csv` yang memuat kolom:

- *`dropoff_location_name`* — nama wilayah di Chicago tempat perjalanan berakhir
- *`average_trips`* — jumlah rata-rata perjalanan yang berakhir di setiap wilayah pada bulan November 2017

file `project_sql_result_07.csv` yang memuat kolom:

- *`start_ts`* — Tanggal dan waktu penjemputan
- *`weather_conditions`* — kondisi cuaca saat perjalanan dimulai
- *`duration_seconds`* — durasi perjalanan dalam satuan detik

# Libraries

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Warnings
