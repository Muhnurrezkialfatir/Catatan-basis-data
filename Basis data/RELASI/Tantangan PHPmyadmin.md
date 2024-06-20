# Hasil Tantangan
## Data Tabel

![](Asetphpmyadmin/1.png)

## Perubahan Struktur Tabel 

### Before
![](Asetphpmyadmin/4.png)

### After
![](Asetphpmyadmin/6.jpeg)

## Perubahan Data Tabel 
### Before pegawai
![](Asetphpmyadmin/1.png)

### After pegawai
![](Asetphpmyadmin/3.png)

### Before cabang
![](Asetphpmyadmin/7.png)

### After cabang 
![](Asetphpmyadmin/8.png)

## Hasil Relasi 
![](Asetphpmyadmin/10.jpeg)


## Query Relasi dan Hasil

### Kode Program
```mysql

SELECT s.nama AS Nama_Siswa, n.nilai AS Nilai
FROM nilai AS n
INNER JOIN siswa AS s ON s.id = n.id_siswa
WHERE n.nilai > 75;
```


### Hasil
![](Asetphpmyadmin/9.png)

tampilkan jumlah data mobil dan kelompokan berdasarkan warna nya

berdasarkan query tampilkan yang lebih besar dari 3 atau sama dengan 3 pemilik mobilnya

berdasarkan query yang ada pada praktikum 5 bagian 7 tampilkan data pada table mobil dengan mengelompokan berdasarkan pemiliknya.hitung menggunakan sum total pendapatan pemilik berdasarkan harga rental 

berdasarkan praktikum 5 query no 8 tampilkan masukan pemilik berdasarkan harga rental kelompokkan berdasarkan pemiliknya dan seleksi atau harga rentalnya mencapai lebih besar atau sama dengan 300k

berdasarkan praktikum 5 nomor 12 tampilkan rata rata pemasukan pemilik mobil kelompokan berdasarkan pemiliknya 

berdasarkan praktikum 5 no 16 tampilkan pemasukan terbesar dan pemasukan terkecil dari pemilik mobil  dan seleksi data pemilik yang tampil lebih besar dari 