# Hasil Tantangan
## Data Tabel

![](Basis%20data/Asetphpmyadmin/1.png)

## Perubahan Struktur Tabel 

### Before
![](Basis%20data/Asetphpmyadmin/4.png)

### After
![](6.jpeg)

## Perubahan Data Tabel 
### Before pegawai
![](Basis%20data/Asetphpmyadmin/1.png)

### After pegawai
![](Basis%20data/Asetphpmyadmin/3.png)

### Before cabang
![](Basis%20data/Asetphpmyadmin/7.png)

### After cabang 
![](Basis%20data/Asetphpmyadmin/8.png)

## Hasil Relasi 
![](Basis%20data/Asetphpmyadmin/10.jpeg)


## Query Relasi dan Hasil

### Kode Program
```mysql

SELECT s.nama AS Nama_Siswa, n.nilai AS Nilai
FROM nilai AS n
INNER JOIN siswa AS s ON s.id = n.id_siswa
WHERE n.nilai > 75;
```


### Hasil
![](Basis%20data/Asetphpmyadmin/9.png)