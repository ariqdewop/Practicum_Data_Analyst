# Deskripsi Proyek

Mengalisis Database Buku Untuk Mengembangkan Aplikasi Di Perusahaan Startup Industri Buku.

# Tujuan

Membuat penawaran harga untuk sebuah produk baru.

# Hipotesis

- Berapa jumlah buku yang dirilis setelah tanggal 1 Januari 2000
- Berapa jumlah ulasan pengguna dan rating rata-rata untuk setiap buku
- Berapa jumlah penerbit yang telah menerbitkan jumlah buku terbanyak dengan jumlah halaman lebih dari 50
- Berapa jumlah penulis dengan rating rata-rata buku tertinggi: temukan buku dengan rating minimal 50
- Berapa jumlah rata-rata teks ulasan di antara pengguna yang memberi rating terhadap lebih dari 50 buku

# Deskripsi Data

Adapun tabel-tabel yang digunakan yaitu:

- *`books`*
- *`authors`*
- *`publishers`*
- *`publishers`*
- *`reviews`*

Tabel *`books`* yang memuat kolom:

- *`book_id`* — ID buku
- *`author_id`* — ID penulis
- *`title`* — Judul buku
- *`title`* — Jumlah halaman
- *`publication_date`* — Tanggal penerbitan
- *`publisher_id`* — ID penerbit

Tabel *`authors`* yang memuat kolom:

- *`author_id`* — ID penulis
- *`author`* — Nama penulis

Tabel *`publishers`* yang memuat kolom:

- *`publisher_id`* — ID penerbit
- *`publisher`* — Nama penerbit

Tabel *`ratings:`* yang memuat kolom:

- *`rating_id`* — ID rating
- *`book_id`* — ID buku
- *`username`* — Nama pengguna yang memberi rating buku
- *`rating`* — Rating

Tabel *`reviews`* yang memuat kolom:

- *`review_id`* — ID ulasan
- *`book_id`* — ID buku
- *`username`* — Nama pengguna yang mengulas buku
- *`text`* — Teks ulasan

# Libraries

- Pandas
- Sqlalchemy
