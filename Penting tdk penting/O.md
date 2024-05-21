# Operator logika dan Pembanding
## AND 
### Struktur
```sql
select * from nama_table where kolom1="nilai_kolom1" AND kolom2="nama_kolom2";
```
### Contoh
```sql
select * from mobil where warna="Hitam" AND pemilik="Ibrahim";
```
### Hasil
![a](asett/and.png)
### Analisis
- `SELECT *`: Bagian kueri ini menentukan bahwa Anda ingin mengambil semua kolom dari tabel.
- `FROM mobil`: Ini menunjukkan bahwa Anda menanyakan tabel "mobil".
- `WHERE warna="Hitam" AND pemilik="Ibrahim"`: Ini adalah kondisi untuk memfilter baris. Ini menetapkan bahwa Anda hanya menginginkan baris yang kolom "warna" sama dengan "Hitam" dan kolom "pemilik" sama dengan "Ibrahim".
### Kesimpulan
`"SELECT * FROM mobil WHERE warna='Hitam' AND pemilik='Ibrahim'"` adalah bahwa perintah tersebut akan mengambil semua data dari tabel "mobil" yang memiliki nilai kolom `"warna"` sama dengan `"Hitam"` dan nilai kolom `"pemilik"` sama dengan `"Ibrahim"`, perintah ini akan mengembalikan semua baris dari tabel `"mobil"` yang memenuhi kedua kriteria tersebut. 
## OR
### Struktur 
```sql
select * from nama_table where kolom1="nilai_kolom1" OR kolom2="nilai_kolom2";
```
### Contoh 
```sql
select * from mobil where warna="Hitam" OR pemilik="Ibrahim";
```
### Hasil
![a](asett/or.png)
### Analisis
- Kolom `"warna"` memiliki nilai `"Hitam"`.
- Kolom `"pemilik"` memiliki nilai `"Ibrahim"`.
Dalam hal ini, perintah `SELECT *`digunakan untuk mengambil semua kolom (semua atribut) dari tabel "mobil". `FROM mobil`menunjukkan bahwa tabel yang dimaksud adalah “mobil”. Kondisi `WHERE`digunakan untuk memfilter baris-baris dalam tabel "mobil". Operator `OR` menunjukkan bahwa setidaknya salah satu kondisi harus dipenuhi agar baris tersebut diambil. Jadi, baris akan diambil jika warna mobil adalah "Hitam" atau jika pemilik mobil adalah "Ibrahim".
### Kesimpulan 
Kesimpulan `"SELECT * FROM mobil WHERE warna='Hitam' OR pemilik='Ibrahim';` adalah bahwa Anda sedang mencari semua data dari tabel "mobil" di mana nilai kolom "warna" sama dengan "Hitam" atau nilai kolom "pemilik" sama dengan "Ibrahim".
## Between
### Struktur
```sql
select * from nama_table where nama_kolom between nilai1 AND nilai2;
```
### Contoh
```sql
select * from mobil where harga_rental between 100000 AND 150000;
```
### Hasil
![a](asett/between.png)
### Analisis
- `SELECT` : Ini merupakan bagian dari perintah SELECT yang digunakan untuk menentukan kolom mana yang ingin Anda ambil dari tabel. Dalam hal ini, tanda _""_ digunakan untuk mengambil semua kolom yang ada di tabel "mobil".
- `FROM mobil` : Ini menentukan bahwa data akan diambil dari tabel bernama "mobil".
- `WHERE harga_rental BETWEEN 100000 AND 150000` : Ini adalah klausul WHERE yang digunakan untuk memfilter baris yang akan diambil berdasarkan kondisi tertentu. Dalam hal ini, kondisi yang digunakan adalah `"harga_rental BETWEEN 100000 AND 150000"`.
- Operator `BETWEEN` digunakan untuk memeriksa apakah nilai kolom "harga_rental" berada di antara dua angka yang diberikan, yaitu 100.000 dan 150.000.
### Kesimpulan
Kesimpulan `"SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 150000;"` adalah bahwa perintah tersebut digunakan untuk mengambil semua data dari tabel "mobil" yang memenuhi kondisi harga_rental berada di antara 100.000 dan 150.000. 
## Not Between
### Struktur
```sql
select * from nama_table where nama_kolom Not between nilai1 AND nilai2;
```
### Contoh
```sql
select * from mobil where harga_rental not between 100000 AND 150000;
```
### Hasil
![a](asett/nbetween.png)
### Analisis
- `SELECT `: Bagian ini menentukan bahwa Anda ingin mengambil semua kolom dari tabel yang ditentukan.
- `FROM mobil`: Ini menunjukkan bahwa Anda menanyakan tabel bernama mobil.
- `WHERE harga_rental NOT BETWEEN 100000 AND 150000`: Ini adalah kondisi yang memfilter baris. Ini hanya memilih baris yang nilai kolomnya `harga_rental`tidak berada dalam kisaran 100.000 dan 150.000.
### Kesimpulan
Kesimpulan `"SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 150000;"` adalah bahwa perintah tersebut digunakan untuk mengambil semua data dari tabel "mobil" di mana harga_rental tidak berada di antara 100.000 dan 150.000. 
## <=
### Struktur
```sql
SELECT * FROM nama_table WHERE nama_kolom <= nilai;
```
### Contoh
```sql
SELECT * FROM mobil WHERE harga_rental <= 50000;
```
### Hasil
![a](asett/kecil.png)
### Analisis 
- `SELECT *`: Bagian kueri ini digunakan untuk menentukan kolom yang ingin Anda ambil. Tanda bintang `(*)`adalah karakter wildcard yang mewakili semua kolom dalam tabel "mobil".
- `FROM mobil`: Menentukan tabel tempat Anda ingin mengambil data, dalam hal ini, tabel "mobil".
- `WHERE harga_rental <= 50000`: Ini adalah kondisi yang memfilter baris berdasarkan kriteria tertentu. Dalam hal ini, ia hanya memilih baris yang nilai di kolom "harga_rental" kurang dari atau sama dengan 50000.
### Kesimpulan
Kesimpulan `"SELECT * FROM mobil WHERE harga_rental <= 50000;"` adalah bahwa Anda mencari semua data dari tabel "mobil" di mana nilai kolom "harga_rental" kurang dari atau sama dengan 50000.
## >=
### Struktur
```sql
SELECT * FROM nama_table WHERE nama_kolom >= nilai;
```
### Contoh
```sql
SELECT * FROM mobil WHERE harga_rental >= 50000;
```
### Hasil
![a](asett/besar.png)
### Analisis
- `SELECT` digunakan untuk memilih kolom atau data yang ingin ditampilkan dalam hasil query.
- Tanda bintang `('*')`  setelah kata kunci SELECT menunjukkan bahwa semua kolom dalam tabel "mobil" akan ditampilkan dalam hasil query.
- `FROM` digunakan untuk menentukan tabel yang akan digunakan dalam query. Dalam kasus ini, tabel yang digunakan adalah "mobil".
- `WHERE` digunakan untuk melakukan filter atau seleksi pada baris-baris data yang memenuhi kondisi tertentu.
- `Kondisi harga_rental >= 50000` menunjukkan bahwa hanya baris-baris data yang memiliki nilai harga_rental yang lebih besar atau sama dengan 50000 yang akan ditampilkan.
### Kesimpulan
Perintah SQL `SELECT * FROM mobil WHERE harga_rental >= 50000;` digunakan untuk mengambil semua data (semua kolom) dari tabel "mobil" di mana nilai pada kolom "harga_rental" lebih besar atau sama dengan 50000.
## <> atau !=
### Struktur
```sql
select * from nama_table where nama_kolom <> 50000;
```
### Contoh
```sql
select * from mobil where harga_rental <> 50000;
```
### Hasil
![a](asett/kecil_besar.png)
### Analisis 
- `SELECT` : Ini menentukan bahwa Anda ingin memilih semua kolom dari tabel.
- `FROM mobil` : Ini menentukan nama tabel "mobil" dari mana Anda ingin mengambil datanya.
- `WHERE harga_rental <> 50000` : Ini adalah kondisi yang memfilter baris. Ini hanya memilih baris dimana nilai di kolom "harga_rental" tidak sama dengan 50000.
### Kesimpulan
Kesimpulan dari  `"SELECT * FROM mobil WHERE harga_rental <> 50000;"` adalah bahwa pernyataan tersebut akan mengembalikan semua baris dari tabel "mobil" di mana nilai kolom "harga_rental" tidak sama dengan 50000.
## Tantangan 
### Struktur
```sql
select nama_kolom from nama_table where nama_kolom="nilai_kolom";
```
### Contoh
```sql
select pemilik from mobil where no_plat="DD 2650 XY";
```
### Hasil
![a](asett/tantangan.png)
### Analisis
- `SELECT pemilik`: Bagian query ini menunjukkan bahwa Anda ingin mengambil nilai dari kolom bernama "pemilik" di tabel yang ditentukan.
- `FROM mobil`: Ini menentukan tabel tempat ingin mengambil data, dalam hal ini, tabel bernama "mobil."
- `WHERE no_plat="DD 2650 XY";`: Menunjukkan bahwa hanya ingin mengambil baris yang nilai di kolom "no_plat" sama dengan "DD 2650 XY".
### Kesimpulan 
Kesimpulan dari `SELECT` yang berikan yaitu mencari informasi pemilik mobil dengan nomor plat "DD 2650 XY" dari tabel mobil.
## IN
### Struktur
```sql
select * from nama_table where nama_kolom in ("nilai_kolom1","nilai_kolom2");
```
### Contoh
```sql
select * from mobil where warna in ("silver","merah");
```
### Hasil
![a](Asett/In.png)
### Analisis
-  `SELECT * FROM mobil` : Pernyataan ini  memilih semua kolom dari tabel "mobil".
-  `WHERE warna IN ('Silver', 'Merah')` : WHERE digunakan untuk menerapkan kondisi pada hasil query. kondisi yang diterapkan adalah "warna IN ('Silver', 'Merah')", yang berarti hanya baris dengan nilai kolom "warna" yang sama dengan 'Silver' atau 'Merah' yang akan diambil.
### Kesimpulan
Query ini akan mengambil semua baris dari tabel "mobil" di mana nilai kolom "warna" adalah 'Silver' atau 'Merah'. query ini akan mengembalikan semua informasi tentang mobil-mobil yang memiliki warna 'Silver' atau 'Merah'. Hasilnya akan berupa kumpulan baris yang mewakili mobil-mobil dengan warna yang sesuai dengan kriteria tersebut.
## IN+AND
### Struktur
```sql
select * from nama_table
where nama_kolom1 in ("nilai_kolom1","nilai_kolom2")
and nama_kolom2=nilai_kolom;
```
### Contoh
```sql
select * from mobil
where warna in ("Hitam","Silver")
and harga_rental=50000;
```
### Hasil
![a](Asett/Inand.png)
### Analisis
-  `SELECT * FROM mobil` : memilih semua kolom `(*)` dari tabel "mobil".
-  `WHERE warna in('Hitam','Silver') AND harga_rental = 50000` : Pernyataan WHERE digunakan untuk menerapkan kondisi pada hasil query. terdapat dua kondisi yang diterapkan :
- Kondisi pertama adalah `"warna IN ('Hitam', 'Silver')"`, yang berarti hanya baris dengan nilai kolom "warna" yang sama dengan 'Hitam' atau 'Silver' yang akan diambil.
- Kondisi kedua adalah `"harga_rental = 50000"` , yang berarti hanya baris dengan nilai kolom "harga_rental" yang sama dengan 50000 yang akan diambil.
### Kesimpulan
Kesimpulan dari SQL tersebut adalah mencari semua entri (baris) dalam tabel "mobil" di mana nilai kolom "warna" adalah 'Hitam' atau 'Silver', dan nilai kolom "harga_rental" adalah 50000. query tersebut akan mengembalikan semua data mobil yang memiliki warna 'Hitam' atau 'Silver' dan memiliki harga rental sebesar 50000.
## IN+OR
### Struktur
```sql
select * from nama_table
where nama_kolom1 in ("nilai_kolom1","nilai_kolom2")
or nama_kolom2=nilai_kolom;
```
### Contoh
```sql
select * from mobil
where warna in ("Hitam","Silver")
or harga_rental=50000;
```
### Hasil
![a](Asett/Inor.png)
### Analisis
### Kesimpulan
## IN+AND+OPERATOR

### >
#### Struktur
```sql
select * from nama_table
where nama_kolom1 in ("nilai_kolom1","nilai_kolom2")
and nama_kolom2 > nilai_kolom;
```
#### Contoh
```sql
select * from mobil
where warna in ("Hitam","Silver")
and harga_rental > 50000;
```
#### Hasil
![a](Asett/Inbesar.png)
#### Analisis
#### Kesimpulan
### <
#### Struktur
```sql
select * from nama_table
where nama_kolom1 in ("nilai_kolom1","nilai_kolom2")
and nama_kolom2 < nilai_kolom;
```
#### Contoh
```sql
select * from mobil
where warna in ("Hitam","Silver")
and harga_rental < 100000;
```
#### Hasil
![a](Asett/Inkecil.png)
#### Analisis
#### Kesimpulan
# LIKE
## Mencari Awalan
### Struktur
### Contoh
```sql
select * from mobil
where pemilik like "ib%";
```
### Hasil
![a](Asett/Awal.png)
### Analisis
### Kesimpulan
## Mencari Akhiran
### Struktur
### Contoh
```sql
select * from mobil
where pemilik like "%m";
```
### Hasil
![a](Asett/Akhir.png)
### Analisis
### Kesimpulan
## Mencari Awalan & Akhiran 
### Struktur
### Contoh
```sql
select * from mobil
where pemilik like "b%m";
```
### Hasil
![a](Asett/A&a.png)
### Analisis
### Kesimpulan
## Mencari berdasarkan total karakter
### Struktur
### Contoh
```sql
select * from mobil
where pemilik like "i__";

select * from mobil
where pemilik like "___";
```
### Hasil
![a](Asett/Tk1.png)
![a](Asett/Tk2.png)
### Analisis
### Kesimpulan
## Kombinasi 
### Struktur
### Contoh
```sql
select * from mobil
where pemilik like "__r%";

select * from mobil
where pemilik like "_b%";
```
### Hasil
![a](Asett/K1.png)
![a](Asett/K2.png)
### Analisis
### Kesimpulan
## Not Like
### Struktur
### Contoh
```sql
select * from mobil where peminjam not like "a%";
```
### Hasil
![a](Asett/Nl.png)
### Analisis
### Kesimpulan
# Null & Not Null
## Mencari data kosong 
### Struktur 
```sql
select * from nama_table where nama_kolom is NULL;
```
### Contoh
```sql
select * from mobil where peminjam is NULL;
```
### Hasil
![a](Asett/Nn.png)
### Analisis
### Kesimpulan 
## Mencari data yang tidak kosong
### Struktur 
```sql
select * from nama_table where nama_kolom is NOT NULL;
```
### Contoh
```sql
select * from mobil where peminjam is NOT NULL;
```
### Hasil
![a](Asett/Nnl.png)
### Analisis
### Kesimpulan 
# Order By
## Mengurutkan data dari data terkecil
### Struktur
```sql
select * from nama_table ORDER BY nama_kolom ASC;
```
### Contoh
```sql
select * from mobil ORDER BY pemilik ASC;
```
### Hasil
![a](Asett/Ob1.png)
### Analisis
### Kesimpulan 
## Mengurutkan data dari data terbesar
### Struktur
```sql
select * from nama_table ORDER BY nama_kolom desc;
```
### Contoh
```sql
select * from mobil ORDER BY peminjam  desc;
```
### Hasil
![a](Asett/Ob2.png)
### Analisis
### Kesimpulan 
# DISTINCT
## DISTINCT
### Struktur 
```sql
select DISTINCT(nama_kolom) from nama_table;
```
### Contoh
```sql
select DISTINCT(pemilik) from mobil;
```
### Hasil
![a](Asett/D1.png)
### Analisis
### Kesimpulan 
## DISTINCT+ORDER BY
### Struktur 
```sql
select DISTINCT(nama_kolom) from nama_table ORDER BY nama_kolom desc;
```
### Contoh
```sql
select DISTINCT(harga_rental) from mobil ORDER BY harga_rental desc;
```
### Hasil
![a](Asett/D2.png)
### Analisis
### Kesimpulan