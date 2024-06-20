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