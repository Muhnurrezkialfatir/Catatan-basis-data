# CONCAT,CONCAT_WA,AS
## Menggabungkan kolom tanpa pemisah
### Struktur 
### Contoh
```sql
SELECT CONCAT(pemilik,warna) FROM mobil;
```
### Hasil
![a](Asett/Concat1.png)
### Analisis
### Kesimpulan
## Menggabungkan kolom dengan pemisah
### Struktur 
### Contoh
```sql
SELECT CONCAT_WS("-",no_plat,no_mesin,id_mobil) FROM mobil;

```
### Hasil
![a](Asett/Concat2.png)
### Analisis
### Kesimpulan
## Memberi nama kolom alias
### Struktur 
### Contoh
```sql
SELECT CONCAT_WS("+",pemilik,peminjam) AS COLLAB FROM mobil;
```
### Hasil
![a](Asett/Concat3.png)
### Analisis
### Kesimpulan
# VIEW
## Membuat tabel virtual
### Struktur 
### Contoh
```sql
CREATE VIEW info_no_plat AS
SELECT id_mobil, no_plat, pemilik, peminjam
FROM mobil
WHERE pemilik = "Ibrahim";
```
### Hasil
![a](Asett/View1.png)
### Analisis
### Kesimpulan
## Menampilkan tabel virtual
### Struktur 
### Contoh
```sql
SELECT * FROM info_no_plat;
```
### Hasil
![a](Asett/View2.png)
### Analisis
### Kesimpulan
## Menghapus tabel virtual
### Struktur 
### Contoh
```sql
DROP VIEW info_no_plat;
```
### Hasil
![a](Asett/View3.png)
### Analisis
### Kesimpulan