# Menambahkan Kolom
## Struktur Query
```sql
ALTER TABLE [nama_tabel]  ADD [nama_kolom_baru] [type_data] [posisi_dalam_tabel];
```
## Contoh
```sql
ALTER TABLE mobil ADD batas_peminjaman varchar(10) AFTER
```
## Hasil
![](Asetdatabase/44.jpg)

## Analisis
- `ALTER TABLE `digunakan untuk mengubah struktur tabel yang sudah ada.
- `mobil` merupakan nama dari tabel yang ingin di ubah struktur nya.
- `ADD batas_peminjam VARCHAR(10) `query tersebut ingin menambahkan kolom baru dengan nama `batas_peminjam` dan type data `VARCHAR` dengan maksimal nilainya `(10)`.
- `AFTER` peminjam kolom baru yang ditambahkan akan berada disamping kanan kolom `peminjam`.
## Kesimpulan
Perintah tersebut akan menambahkan kolom baru pada tabel mobil dengan nama `batas_peminjam`.


# Mengubah nama kolom
## Struktur
```sql
```
## Contoh
```sql

```
## Hasil
### Before


### After


## Analisis

## Kesimpulan

# Mengubah tipe data kolom
## Struktur

## Contoh
## Hasil
### Before


### After


## Analisis

## Kesimpulan