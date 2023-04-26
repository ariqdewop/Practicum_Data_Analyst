# Deskripsi Proyek

Menilai kinerja gerai penjualan jaringan dari retail bahan bangunan Home World.

# Tujuan

Mencari metrik-metrik yang menjadi kunci dalam keberhasilan kinerja suatu gerai dan mencari gerai-gerai yang membutuhkan dukungan dalam rantai besar serta mencari tahu apakah program loyalitas memberi pengaruh untuk metrik-metrik tersebut bekerja pada gerai-gerainya.

# Hipotesis

- Bagaimana untuk mengkategorikan gerai-gerai yang termasuk besar dan termasuk lainnya
- Bagaimana jumlah pelanggan unik, ukuran pembelian rata-rata, jumlah rata-rata barang dalam keranjang, jumlah anggota program loyalitas, dan retensi pelanggan untuk gerai-gerai besar dan gerai-gerai lainnya
- Bagaimana merumuskan metrik untuk kinerja gerai penjualan dan menghitungnya untuk setiap gerainya
- Apakah ukuran pembelian rata-rata untuk anggota program loyalitas lebih tinggi daripada non-anggota

# Deskripsi Data

Adapun file yang digunakan yaitu `retail_dataset_us.csv` yang memuat kolom:

- *`purchaseId`* — kode pembelian
- *`item_ID`* — kode barang
- *`Quantity`* — jumlah kuantitas yang dibeli/dibayar
- *`purchasedate`* - tanggal pembelian
- *`CustomerID`* — kode pelanggan
- *`loyalty_program`* — kode penanda untuk pelanggan menggunakan program loyal (semacam kartu anggota)
- *`ShopID`* — kode penjual/pedagang/toko

file `product_codes_us.csv` yang memuat kolom:

- *`productID`* — kode produk
- *`price_per_one`* — harga produk untuk satu barangnya

# Libraries

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Math
- SKLearn
- Warnings
