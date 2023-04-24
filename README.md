# Deskripsi Proyek

Melakukan penyusunan dan memprioritaskan hipotesis, A/B Testing dan menganalisis hasilnya di sebuah toko daring besar.

# Tujuan

Untuk meningkatkan pendapatan toko daring besar.

# Hipotesis

- Metode seperti apa yang akan digunkana untuk memprioritaskan sebuah hipotesis
- Hipotesis seperti apa akan di prioritaskan ketika sudah dilist
- Variabel apa akan di gunakan untuk untuk A/B testing
- Apakah ada perbedaan diantara kelompok setelah melakukan A/B testing
- Keputusan seperti apa yang akan dilakukan setelah melakukan A/B testing

# Deskripsi Data

Adapun file yang digunakan yaitu `hypotheses_us.csv` yang memuat kolom:

- *`Hypotheses`* — Deskripsi singkat tentang hipotesis
- *`Hypotheses`* — Jangkauan pengguna, dalam skala satu hingga sepuluh
- *`Impact`* — Dampak terhadap pengguna, dalam skala satu hingga sepuluh
- *`Confidence`* — Keyakinan pada hipotesis, dalam skala satu sampai sepuluh
- *`Effort`* — Sumber daya yang diperlukan untuk menguji hipotesis, dalam skala satu sampai sepuluh. Semakin tinggi nilai *Effort*, semakin intensif sumber daya pengujiannya.

file `orders_us.csv` yang memuat kolom:

- *`transactionId`* — ID pesanan
- *`visitorId`* — ID pengguna yang membuat pesanan
- *`date`* — Tanggal dibuatnya pesanan
- *`revenue`* — Pendapatan dari pesanan
- *`group`* — Kelompok uji (test group) A/B tempat pengguna berada

file `visits_us.csv` yang memuat kolom:

- *`date`* — tanggal
- *`group`* — kelompok uji (test group) A/B
- *`visits`* — jumlah kunjungan pada tanggal yang ditentukan untuk kelompok uji A/B yang ditentukan

# Libraries

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Warnings
