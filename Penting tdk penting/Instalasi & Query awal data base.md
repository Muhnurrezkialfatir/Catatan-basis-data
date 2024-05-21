#  Pengenalan Basis Data

## Definisi Basis Data

_Basis_ : Adalah tempat berkumpul, markas, gudang, wadah suatu data

_Data_ : Adalah sekumpulan fakta sebuah objek

_Kesimpulan_ : _Basis data_ adalah kumpulan informasi yg disimpan di dalam komputer secara sistematik

## Peranan Basis Data

Bank: Bank merupakan salah satu organisasi yang sangat tergantung kepada sistem basis data. Data nasabah, transaksi yang dilakukan, dan data keuangan lainnya disimpan di sistem basis data. Sistem ini memungkinkan layanan kepada nasabah bank dapat dilakukan dengan baik.

# Data base

## Contoh tabel database
![300](Asetdatabase/Hirarki.jpg)

## Struktur Tabel Dalam Basis Data
Struktur/Hirarki DataBase adalah struktur organisasi data dalam database yang mengatur hubungan antara entitas atau tabel data.Di dalam hirarki database,data diorganisir dalam bentuk pohon dengan satu entitas induk atau tabel utama yang memiliki beberapa entitas tabel yang terkait.

Database saya anggap seperti Liga Inggris yang dimana Dia Menampung Club" Seperti MU,MC, yg di dalamnya Mempunyai Pemain Yang berbeda beda Sama Seperti Database dimana Dia Menampung File" Yg berbeda beda di dalamnya Contohnya: Ada 4 Club yg saya Ambil 1 saya Uraikan DiMana 4 Club itu ada Manchester United, Manchester city, Tottenham, Aston Villa. Yang saya Uraikan Manchester City dalam bentuk Tabel.
## Struktur database
| No | Nama  | Alamat             | Hobi           |
| -- | ----- | ------------------ | -------------- |
| 1  | Fatir | Jl. Muh jufri4     | Baca komik     |
| 2  | Daud  | Jl. Kalumpang      | Main minecraft |
| 3  | Agis  | Jl. Galangan kapal | Baca komik     |
| 4  | Angga | Jl. Traktor4       | Nonton anim    |
### Tabel
Tabel adalah sebuah struktur dasar yang menyimpan data dalam format terstruktur. Setiap tabel memiliki kolom yang mewakili atribut dan baris yang mewakili catatan. Contoh seperti di bawah berikut

- Baris merupakan deretan horizontal yang terdiri dari kata, angka, data atau objek lainnya, contoh di atas contoh untuk baris seperti. 1, Fatir, jl. Muh jufri4, baca komik, , 2, Daud, jl. Kalumpang, main minecraft, , Dan seterusnya. 
- Kolom merupakan deretan vertikal contoh di atas untuk kolom seperti. 1, 2, 3, 4, Ahmad Fatir, daud, Dan seterusnya. 
- untuk isinya itu merupakan sebuah item data atau karakter yang di masukkan ke dalam tabel.

### Database

Database (basis data) adalah kumpulan data yang terorganisir dengan cara tertentu untuk memudahkan pengelolaan, penyimpanan, dan pengambilan informasi. Dalam sebuah database, data disimpan dalam tabel yang terdiri dari baris dan kolom. Setiap baris dalam tabel mewakili sebuah catatan atau entitas, sedangkan kolom menyimpan. Di database juga memiliki komponen utama seperti.

1. **Tabel:** Struktur dasar yang menyimpan data dalam format terstruktur. Setiap tabel memiliki kolom yang mewakili atribut dan baris yang mewakili catatan.
    
2. **Baris atau Record:** Masing-masing baris dalam tabel berisi data untuk satu entitas atau catatan tertentu.
    
3. **Kolom atau Field:** Masing-masing kolom dalam tabel menyimpan informasi tentang atribut tertentu, seperti nama, alamat, atau nomor telepon.
    
4. Item Data atau Karakter: merupakan isian dari baris dan kolom.
# instalasi mySQL
## menggunakan termux
1. Buka termux
2. Ketik ``termux-setup-storage``
3. Klik izinkan/allow access
4. Lakukan update dan upgrade paket.ketik ``pkg update && upgrade``
5. Jika ada konfirmasi untuk melanjutkan instalasi ketik aja ``Y``
6. Install applikasi mariadb dengan mengetik``pkg install mariadb``
7. Ketika proses nya berhenti dan ada pilihan ketik saja ``Y`` untuk melanjutkan proses penginstalannya. 
8. Ketik ``mysqld_safe`` untuk memberi keamanan
9. Untuk menghentikan proses ``ctrl+z``
10. Masuk ke akun admin ``mysql -u root`` 
11. Buatlah data base dengan ketik ``create database xi_rpl_1;``
12. Kalo mau menampilkan data basenya ketik ``show databases;``
13. Kalo mau menghapus data basenya ketik ``drop database [nama database];
14. Kalo mau menggunakan data basenya ketik ``use [nama database];``

## referensi youtube
https://youtu.be/JojQd-l7fEE?si=OPIB01q45A2FmY1x
# penggunaan awal MySQL
## Query
``<mysql -u root -p>``
## hasil
![250](Asetdatabase/Mysqroot.jpg)
## Analisis kesimpulan
- `<mySQL>` Salah satu aplikasi database server dengan bahasa pemrograman structured query languange `(SQL)` yang berfungsi untuk mengelola data secara terstruktur dan sistematis.
- `<-u root>` Bagian ini mengeset pengguna (user) yang akan digunakan saat terhubung ke server  MYSQL. Dalam contoh ini, pengguna yang digunakan adalah `"root"`. Pengguna `"root"` biasanya memiliki hak akses penuh ke server MYSQL dan dapat melakukan tindakan administratif.
- `<-p>` Opsi ini digunakan untuk meminta kata sandi (password) setelah perintah dijalankan ini adalah langkah keamanan yang umum digunakan untuk memastikan hanya pengguna yang sah yang dapat mengakses server MYSQL. Setelah kita menekan Enter setelah perintah ini, kita akan diminta memasukkan kata sandi untuk pengguna `"root"`.




# data base
Database (basis data) adalah kumpulan terstruktur dari informasi yang disimpan secara elektronik dalam sistem komputer. Database dirancang untuk menyimpan, mengatur, dan mengelola data dengan cara yang efisien dan dapat diakses.
## buat data base
- `CREATE DATABASE` adalah perintah untuk membuat database baru.
- ``[XI_RPL_1]`` adalah nama yang Anda pilih untuk database baru Anda. Tanda kurung siku `<("[]")>` digunakan di sini untuk menghindari kesalahan jika nama database mengandung karakter spesial atau spasi. Namun, perlu dicatat bahwa tidak semua DBMS mengizinkan penggunaan tanda kurung siku dalam nama database, jadi pastikan untuk menyesuaikan sintaksdengan DBMS yang Anda gunakan.
### Query
``create database xi_rpl_1;``

### Hasil:
![300](Asetdatabase/Buatdatabase.jpg)
### Analisis kesimpulan :
- CREATE DATABASE adalah perintah untuk membuat database baru.
- XRPL 1 adalah nama yang Anda pilih untuk database baru Anda. Tanda kurung siku '<("{}")>'digunakan di sini untuk menghindari kesalahan jika nama database mengandung karakter spesial atau spasi. Namun, perlu dicatat bahwa tidak semua DBMS mengizinkan penggunaan tanda kurung siku dalam nama database, jadi pastikan untuk menyesuaikan sintaksdengan DBMS yang Anda gunakan.
## Tampilkan data base
`SHOW DATABASE` digunakan untuk menampilkan daftar database yang ada dalam sistem manejemen basis data (DBMS). Perintah ini dapat digunakan di beberapa DBMS seperti MYSQL, PostgreSQL, dan beberapa DBMS lainnya. Namun, perintahnya dapat sedikit berbeda tergantung
### Query 
``show databases;``

### Hasil:
![250](Asetdatabase/Showdatabase.jpg)
### Analisis kesimpulan :

`SHOW DATABASE` digunakan untuk menampilkan daftar database yang ada dalam sistem manejemen basis data (DBMS). Perintah ini dapat digunakan di beberapa DBMS seperti MYSQL, PostgreSQL, dan beberapa DBMS lainnya. Namun, perintahnya dapat sedikit berbeda tergantung
## hapus database
``<DROP DATABASE [nama_database]>`` digunakan dalam sistem manajemen basis data (DBMS) untuk menghapus sebuah database beserta semua objek yang terkait dengan database tersebut, seperti tabel, indeks, tampilan, prosedur tersimpan, dan lain-lain.
### Query
``drop database xi_rpl_1``
### Hasil:
![300](Asetdatabase/Dropdata.jpg)
### Analisis kesimpulan
`DROP DATABASE` nama database digunakan dalam sistem manajemen basis data (DBMS) untuk menghapus sebuah database beserta semua objek yang terkait dengan database tersebut, seperti tabel, indeks, tampilan, prosedur tersimpan, dan lain-lain.
## gunakan data base
``USE [nama_database]`` digunakan dalam sistem manajemen basis data (DBMS) untuk beralih atau memilih database yang akan digunakan. Ketika Anda menggunakan perintah ``<USE>`` diikuti dengan nama database, DBMS akan mengarahkan semua perintah dan operasi selanjutnya pada database yang ditentukan.
### Query
`` use xi_rpl_1; ``
### Hasil:
![300](Asetdatabase/Usedata.jpg)
### Analisis kesimpulan :
`Use [nams database]` digunakan dalam sistem manajemen basis data (DBMS) untuk beralih atau memilih database yang akan digunakan. Ketika Anda menggunakan perintah uses diikuti dengan nama database, DBMS akan mengarahkan semua perintah dan operasi selanjutnya pada database yang ditentukan.
# tipe data
## angka
- Int (integer) tipe data ini digunakan untuk merepresentasikan bilangan bulat tanpa bagian desimal.Contoh: 0, 42, -10
- **DECIMAL**: Digunakan untuk menyimpan nilai desimal presisi tinggi, cocok untuk perhitungan finansial atau keuangan.
- **FLOAT dan DOUBLE**: Digunakan untuk menyimpan nilai desimal dengan presisi floating-point. DOUBLE memiliki presisi lebih tinggi dibandingkan FLOAT.
- **TINYINT , SMALLINT , MEDIUMINT , dan BIGINT**: Tipe data ini menyimpan bilangan bulat dengan ukuran yang berbeda-beda.

## teks
-  **CHAR(N)**: Menyimpan string karakter tetap dengan panjang N. Contoh: CHAR(10) akan menyimpan stringdengan panjang tepat 10 karakter.

- **VARCHAR(N)**: Menyimpan string karakter dengan panjang variabel maksimal N. Misalnya,VARCHAR(255) dapat menyimpan string hingga 255 karakter, tetapi sebenarnya hanya menyimpan panjang yang diperlukan plus  beberapa overhead.

- **TEXT**: Digunakan untuk menyimpan teks dengan panjang variabel, tanpa batasan panjang tertentu. Cocok untukdata teks yang panjangnya tidak terduga.

- **ENUM**: Memungkinkan Anda mendefinisikan set nilai yang mungkin dan membatasi kolom hanya dapat mengambil salah satu dari nilai tersebut.

- **SET**: Mirip dengan ENUM, namun dapat menyimpan satu atau lebih nilai dari himpunan yang telah ditentukan.
## tanggal
- `Date` digunakan untuk menyimpan informasi tentang tanggal, biasanya terdiri dari hari, bulan, dan tahun seperti 30 Januari 2024
- `Time` digunakan untuk menyimpan informasi tentang waktu dalam sehari, biasanya terdiri dari jam, menit, detik, dan milidetik seperti 14:30:45.500
- `DateTime` menggabungkan informasi tanggal dan waktu dalam satu objek, biasanya terdiri dari hari, bulan, tahun, jam, menit, detik, dan milidetik seperti 30 Januari 2024 14:30:45.500
- **TimeStamp**: Sama seperti DATETIME, tetapi dengan kelebihan diatur secara otomatis saat data dimasukkan atau diubah.
## boolean

- **BOOL / BOOLEAN / TINYINT**: Digunakan untuk menyimpan nilai boolean, yang dapat mewakili kebenaran (true) atau kesalahan (flase). 

## TIPE DATA PILIHAN
### ENUM
Menyimpan satu nilai dari daftar nilai yang ditentukan.

### SET 
Menyimpan beberapa nilai dari daftar nilai yang ditentukan 
# Table
## Buat Table

Analisis Kesimpulan
Perintah `"CREATE TABLE"` digunakan dalam SQL untuk membuat sebuah tabel baru dalam basis data. Berikut adalah penjelasan mengenai sintaks dan bagaimana menggunakan perintah `"CREATE TABLE"`.

### **Struktur Query**:
```sql
CREATE TABLE [nama_table] ( 
nama_kolom1 tipe_data(ukuran) [tipe_constraint] 
nama_kolom2 tipe_data(ukuran) [tipe_constraint] 
nama_kolom3 tipe_data(ukuran) [tipe_constraint] );
```

### Contoh Query
```sql
CREATE TABLE Pelanggan (
id_pelanggan int(4) PRIMARY KEY NOT NULL,
nama_depan varchar(25) NOT NULL,
nama_belakang varchar(25) NOT NULL,
no_telp char(12) UNIQUE );
```

### Hasil
![400](Asetdatabase/Struktur.jpg)
### Analisis:
1. **CREATE TABLE Pelanggan:**
    
    - Ini adalah perintah SQL untuk membuat sebuah tabel baru dengan nama "Pelanggan".
    
2. **id_pelanggan int(4) PRIMARY KEY NOT NULL:**
    
    - Kolom "id_pelanggan" dibuat sebagai tipe data integer dengan panjang maksimal 4 digit.
    - PRIMARY KEY menandakan bahwa kolom ini adalah kunci utama (primary key) yang unik dan tidak boleh kosong (NOT NULL).
    - Ini menunjukkan bahwa setiap baris dalam tabel akan diidentifikasi oleh nilai unik dalam kolom "id_pelanggan".
    
3. **nama_depan varchar(25) NOT NULL:**
    
    - Kolom "nama_depan" dibuat sebagai tipe data string (varchar) dengan panjang maksimal 25 karakter.
    - NOT NULL menunjukkan bahwa kolom ini tidak boleh kosong.
    
4. **nama_belakang varchar(25) NOT NULL:**
    
    - Kolom "nama_belakang" dibuat sebagai tipe data string (varchar) dengan panjang maksimal 25 karakter.
    - NOT NULL menunjukkan bahwa kolom ini tidak boleh kosong.
    
5. **no_telp char(12) UNIQUE:**
    
    - Kolom "no_telp" dibuat sebagai tipe data karakter (char) dengan panjang tepat 12 karakter.
    - UNIQUE menandakan bahwa setiap nilai dalam kolom ini harus unik, tidak boleh ada duplikat.

### Kesimpulan :
tabel "Pelanggan" memiliki struktur yang terorganisir dengan baik. Setiap entri dalam tabel akan memiliki id_pelanggan sebagai identitas unik, serta informasi nama depan, nama belakang, dan nomor telepon pelanggan. Nomor telepon harus unik dalam tabel ini. Dengan struktur yang jelas seperti ini, database akan dapat menyimpan informasi pelanggan secara efisien dan memastikan integritas data yang baik.

## Tampilkan Struktur Tabel
### **Struktur Query**:
```sql
desc [nama_table];`

```
### **Contoh Query**:

```sql
desc Pelanggan;

```

### Hasil
![300](Asetdatabase/Struktur.jpg)

### Analisis
`desc pelanggan;`:dapat melihat secara detail karakteristik dari setiap kolom dalam tabel tersebut, termasuk nama kolom, tipe data, panjang maksimum (jika berlaku), dan konstrain khusus seperti PRIMARY KEY, UNIQUE, atau NOT NULL yang diterapkan pada setiap kolom.
### Kesimpulan
perintah tersebut memberikan gambaran tentang bagaimana tabel "Pelanggan" telah didefinisikan dalam basis data.

## Menampilkan Daftar Tabel
**Struktur Query**:
```sql
show tables;
```

**Contoh** Query: 
```sql
show tables;
``````

### Hasil
![300](Asetdatabase/Showtable.jpg)

### **Analisis**:
`show tables;`:untuk menampilkan semua tabel yang ada dalam database yang sedang aktif.

### **Kesimpulan**:
memiliki peran penting dalam memberikan visibilitas awal terhadap struktur database, yang menjadi dasar untuk pekerjaan lebih lanjut dalam pengelolaan dan penggunaan data.
## QnA
>[! Faq] Mengapa hanya kolom id_pelanggan yang menggunakan constraint PRIMARY KEY?
> > Untuk membedakan id Pelanggan  yang sama, mencegah duplikasi, dan mempermudah pencarian data.


> [! Faq] Mengapa pada kolom no_telp yang menggunakan tipe data chat bukan varchar?
> > Tipe data char menyimpan data dalam karakter panjang lebih efisien. pencarian pada kolom tipe data `CHAR` dapat lebih cepat


> [! Faq] Mengapa hanya kolom no_telp yang menggunakan constraint UNIQUE?
> > Karna no_telp tidak ada yang sama semua pasti berbeda dan nilainya unik maka menggunakan constrains unique artinya data dalam tabel id_telpon berbeda tidak ada yang sama. 


> [! Faq] Mengapa kolom no_telp tidak memakai constraint NOT NULL, sementara kolom lainnya menggunakan constraint tersebut?
> > Nomor telpon dianggap opsional. nomor telepon hanya menjadi wajib saat pengguna melakukan langkah-langkah tertentu, Anda mungkin tidak ingin mengharuskan pengguna mengisinya pada tahap awal.


> [! Faq] Perbedaan PK & UNIQUE
> > PRIMERY KEY untuk membedakan data yang sama dan hanya boleh 1 dan tidak boleh tidak ada. 
Kalau UNiQUE sebuah kolom yang memiliki data yang berbeda atau tidak sama unique boleh 1,2,3 Dan seterusnya dan boleh tidak ada.



# insert
## insert 1 data

### struktur
```SQL
Insert into pelanggan
Values(1,fatir,tir,0821772842)
```
### Contoh
```MySQL
MariaDB [rental_fatir]> insert into PELANGGAN
    -> VALUES(813,"FATIR","REZKI","082163626");
```

### Hasil
![300](Asetdatabase/Insert1data.jpg)
### analisis
- `insert into Pelanggan`: Ini adalah perintah untuk memasukkan baris data ke dalam tabel "Pelanggan".
- `values (1,"muhammad","agis","08500000")`: Ini adalah nilai yang akan dimasukkan ke dalam tabel "Pelanggan". Urutannya sesuai dengan kolom-kolom pada tabel tersebut.
### Kesimpulan 
mencoba untuk memasukkan data baru ke dalam tabel "Pelanggan".
## Insert >1 Data
### Struktur
```sql
Insert into [nama_table]
Values (nilai1, nilai2, nilai3, nilai4)
       (nilai1, nilai2, nilai3, nilai4)
       (nilai1, nilai2, nilai3, nilai4)
```
### Contoh
```sql
Insert into pelanggan
Values (2, "muh", "agis", "0890000"), (3,"muh", "daud", "0870000" ), (4, "ahmad", "anugrah", "08100000");
```
### Hasil
![300](Asetdatabase/Insertlebihdarisatu.jpg)
### Analisis
- `insert into Pelanggan`: Ini adalah perintah untuk memasukkan baris data ke dalam tabel "Pelanggan".
- `Values (2, "muh", "agis", "0890000"), (3,"muh", "daud", "0870000" ), (4, "ahmad", "anugrah", "08100000");`:Ini adalah nilai yang akan dimasukkan ke dalam tabel "Pelanggan". Urutannya sesuai dengan kolom-kolom pada tabel tersebut.

### Kesimpulan
data telah dimasukkan ke dalam tabel Pelanggan dengan masing-masing nilai kolom sesuai dengan urutan yang diberikan

## Menyebut kolom
### struktur
```Mysql
Insert into pelanggan
(Nama_depan, id)value
("Stuwja",6);
```

### Contoh
```sql
insert into Pelanggan
(id_pelanggan,nama_depan,nama_belakang)
values (813,"FATIR","REZKI");
```
### Hasil
![300](Asetdatabase/Select.jpg)
### Analisis
- `insert into Pelanggan`: Ini adalah perintah untuk memasukkan baris data ke dalam tabel "Pelanggan".
- `(id_pelanggan,nama_depan,nama_belakang)`:yang diberikan nilai, sedangkan kolom lainnya akan diisi dengan nilai default jika diperbolehkan atau NULL jika tidak diizinkan.
- `values (813,"FATIR","REZKI")`:Ini adalah nilai yang akan dimasukkan ke dalam tabel "Pelanggan". Urutannya sesuai dengan kolom-kolom pada tabel tersebut.
### Kesimpulan
sebuah entri baru telah dimasukkan ke dalam `tabel Pelanggan`,Tidak ada kolom lain yang diberikan nilai dalam perintah INSERT, sehingga kolom-kolom yang tidak disebutkan akan menggunakan nilai default atau NULL.
# select
## seluruh data
### Struktur
```sql
select * from [nama_table];
```
### Contoh
```sql
Select * from pelanggan;
```
### Hasil
![300](Asetdatabase/Select.jpg)
### Analis 
- `Select` merupakan query yang digunakan untuk menampilkan hasil `insert` 
- `*` artinya semua kolom yang ada di table akan di tampilkan 
- `from` query yang digunakan untuk memberikan penanda bahwa table mana yang akan di tampilkan
- `pelanggan` merupakan nama table yang isi nya akan di tampilkan
### Kesimpulan
program akan mengambil dan menampilkan semua data yang tersimpan dalam tabel Pelanggan, termasuk setiap kolom dan setiap baris yang ada dalam tabel tersebut.
## Data kolom tertentu
### Struktur
```Mysql
Select [nama_kolom1], [nama_kolom2], [nama_kolom_n]
From[nama_tabel];
```
### contoh
```sql
Select nama_depan From pelanggan;
```
### Hasil
![300](Asetdatabase/Klom.jpg)
### Analisis
- `Select` merupakan query yang digunakan untuk menampilkan hasil `insert` 
- `nama_depan` nama kolom dalam tabel database yang mungkin menyimpan informasi tentang nama depan dari pelanggan.
- `from` query yang digunakan untuk memberikan penanda bahwa table mana yang akan di tampilkan
- `pelanggan` merupakan nama table yang isi nya akan di tampilkan
### Kesimpulan 
Hasilnya akan berupa daftar `nama_depan` dari semua pelanggan yang terdaftar dalam tabel tersebut.
## kalusa WHERE
### Struktur
```sql
Select [nama_kolom] From [nama_tabel] Where[kondisi];
```
### Contoh
```sql
Select nama_depan From pelanggan
Where id=813;
```
### Hasil
![300](Asetdatabase/Where1.jpg)

### Analisis
- `Select` merupakan query yang digunakan untuk menampilkan hasil `insert` 
- `id_pelanggan,nama_depan` nama kolom dalam tabel database yang mungkin menyimpan informasi tentang nama depan dari pelanggan.
- `from` query yang digunakan untuk memberikan penanda bahwa table mana yang akan di tampilkan
- `pelanggan` merupakan nama table yang isi nya akan di tampilkan
- `where` untuk menyaring baris data berdasarkan kondisi tertentu.
- `id_pelanggan=1` hanya baris-baris data di mana nilai kolom 
### Kesimpulan 
hasilnya akan berisi ID dan nama depan pelanggan yang memiliki ID tertentu
# update
## struktur
```sql
Update nama_table set nama_kolom where kondisi;
```
## contoh
```sql
Update Pelanggan set no_telp="085326690" where id_pelanggan="813";
```

## hasil
![300](Asetdatabase/Update.jpg)
## Analisis
- `UPDATE pelanggan`: Ini adalah klausa yang menentukan tabel mana yang akan diperbarui. Dalam kasus ini, tabel yang diperbarui adalah "pelanggan".
- `SET no_telp="085358639358"`: Ini adalah klausa yang menentukan kolom mana yang akan diperbarui dan nilai baru yang akan diberikan. Dalam hal ini, kolom yang diperbarui adalah "no_telp" dan nilainya diubah menjadi "085358639358".
- `WHERE id_pelanggan="1"`: Ini adalah klausa opsional yang digunakan untuk membatasi baris mana yang akan diperbarui. Dalam hal ini, perubahan hanya akan diterapkan pada baris dengan nilai "id_pelanggan" yang sama dengan "1".
## Kesimpulan
nomor telepon (no_telp) dari pelanggan dengan ID "1" akan diubah menjadi "085358639358". Perintah tersebut mengupdate data pada tabel "pelanggan" dan mengaplikasikan perubahan hanya pada baris dengan nilai "id_pelanggan" yang sama dengan "1".
# Delete
## struktur
```sql
Delete from nama_table where kondisi;
```
## contoh
```sql
delete from Pelanggan where id_pelanggan="6";
```
## hasil
![300](Asetdatabase/Delete.jpg)
## Analisis
- `DELETE FROM pelanggan`: Ini adalah klausa yang menentukan tabel mana yang akan dihapus datanya. Dalam kasus ini, data akan dihapus dari tabel "pelanggan".
- `WHERE id_pelanggan="2"`: Ini adalah klausa opsional yang digunakan untuk membatasi baris mana yang akan dihapus. Dalam hal ini, baris dengan nilai "id_pelanggan" yang sama dengan "2" akan dihapus.

## kesimpulan
menghapus baris table kalian bisa menggunakan query delete dengan struktur yaitu delete from nama_table where kondisi;

# select
# Operator Logika & Pembanding
## AND
### Struktur
```mysql
SELECT FROM nama_table WHERE nama_kolom1="nilai_kolom" AND nama_kolom2="nilai_kolom"
```
### Contoh
```mysql
select * from mobil where warna="Hitam" AND pemilik="Ibrahim";
```
### Hasil
![300](Asetdatabase/1.jpg)
### Analisis
- `SELECT *`: Bagian kueri ini menentukan bahwa Anda ingin mengambil semua kolom dari tabel.
- `FROM mobil`: Ini menunjukkan bahwa Anda menanyakan tabel "mobil".
- `WHERE warna="Hitam" AND pemilik="Ibrahim"`: Ini adalah kondisi untuk memfilter baris. Ini menetapkan bahwa Anda hanya menginginkan baris yang kolom "warna" sama dengan "Hitam" dan kolom "pemilik" sama dengan "Ibrahim".
### Kesimpulan
`"SELECT * FROM mobil WHERE warna='Hitam' AND pemilik='Ibrahim'"` adalah bahwa perintah tersebut akan mengambil semua data dari tabel "mobil" yang memiliki nilai kolom `"warna"` sama dengan `"Hitam"` dan nilai kolom `"pemilik"` sama dengan `"Ibrahim"`, perintah ini akan mengembalikan semua baris dari tabel `"mobil"` yang memenuhi kedua kriteria tersebut. 
## OR
### Struktur
```mysql
SELECT FROM nama_table WHERE nama_kolom1="nilai_kolom" OR nama_kolom2="nilai_kolom"
```
### Contoh
```mysql
 select * from mobil where warna="Hitam" OR pemilik="Ibrahim";
```
### Hasil
![300](asetdatabase/2.jpg)
### Analisis
- Kolom `"warna"` memiliki nilai `"Hitam"`.
- Kolom `"pemilik"` memiliki nilai `"Ibrahim"`.
Dalam hal ini, perintah `SELECT *`digunakan untuk mengambil semua kolom (semua atribut) dari tabel "mobil". `FROM mobil`menunjukkan bahwa tabel yang dimaksud adalah “mobil”. Kondisi `WHERE`digunakan untuk memfilter baris-baris dalam tabel "mobil". Operator `OR` menunjukkan bahwa setidaknya salah satu kondisi harus dipenuhi agar baris tersebut diambil. Jadi, baris akan diambil jika warna mobil adalah "Hitam" atau jika pemilik mobil adalah "Ibrahim".
### Kesimpulan
Kesimpulan `"SELECT * FROM mobil WHERE warna='Hitam' OR pemilik='Ibrahim';` adalah bahwa Anda sedang mencari semua data dari tabel "mobil" di mana nilai kolom "warna" sama dengan "Hitam" atau nilai kolom "pemilik" sama dengan "Ibrahim".
## BETWEEN
### Struktur
```mysql
SELECT * FROM nama_table WHERE nama_kolom BETWEEN nilai_kolom AND nilai_kolom ;
```
### Contoh
```mysql
 select * from mobil WHERE harga_rental BETWEEN 100000 AND 150000;
```
### Hasil
![300](asetdatabase/3.jpg)
### Analisis
- `SELECT` : Ini merupakan bagian dari perintah SELECT yang digunakan untuk menentukan kolom mana yang ingin Anda ambil dari tabel. Dalam hal ini, tanda _""_ digunakan untuk mengambil semua kolom yang ada di tabel "mobil".
- `FROM mobil` : Ini menentukan bahwa data akan diambil dari tabel bernama "mobil".
- `WHERE harga_rental BETWEEN 100000 AND 150000` : Ini adalah klausul WHERE yang digunakan untuk memfilter baris yang akan diambil berdasarkan kondisi tertentu. Dalam hal ini, kondisi yang digunakan adalah `"harga_rental BETWEEN 100000 AND 150000"`.
- Operator `BETWEEN` digunakan untuk memeriksa apakah nilai kolom "harga_rental" berada di antara dua angka yang diberikan, yaitu 100.000 dan 150.000.
### Kesimpulan
Kesimpulan `"SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 150000;"` adalah bahwa perintah tersebut digunakan untuk mengambil semua data dari tabel "mobil" yang memenuhi kondisi harga_rental berada di antara 100.000 dan 150.000. 
## NOT BETWEEN
### Struktur
```mysql
SELECT * FROM nama_table WHERE nama_kolom NOT BETWEEN nilai_kolom AND nilai_kolom ;
```
### Contoh
```mysql
select * from mobil WHERE harga_rental NOT BETWEEN 100000 AND 150000;
```
### Hasil
![300](Asetdatabase/4.jpG)
### Analisis
- `SELECT `: Bagian ini menentukan bahwa Anda ingin mengambil semua kolom dari tabel yang ditentukan.
- `FROM mobil`: Ini menunjukkan bahwa Anda menanyakan tabel bernama mobil.
- `WHERE harga_rental NOT BETWEEN 100000 AND 150000`: Ini adalah kondisi yang memfilter baris. Ini hanya memilih baris yang nilai kolomnya `harga_rental`tidak berada dalam kisaran 100.000 dan 150.000.
### Kesimpulan
Kesimpulan `"SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 150000;"` adalah bahwa perintah tersebut digunakan untuk mengambil semua data dari tabel "mobil" di mana harga_rental tidak berada di antara 100.000 dan 150.000. 
## <=
### Struktur
```mysql
SELECT * FROM mobil WHERE harga_rental <= 50000;
```
### Contoh
```mysql
SELECT * from mobil WHERE harga_rental <= 50000;
```
### Hasil
![300](asetdatabase/5.jpg)
### Analisis
- `SELECT *`: Bagian kueri ini digunakan untuk menentukan kolom yang ingin Anda ambil. Tanda bintang `(*)`adalah karakter wildcard yang mewakili semua kolom dalam tabel "mobil".
- `FROM mobil`: Menentukan tabel tempat Anda ingin mengambil data, dalam hal ini, tabel "mobil".
- `WHERE harga_rental <= 50000`: Ini adalah kondisi yang memfilter baris berdasarkan kriteria tertentu. Dalam hal ini, ia hanya memilih baris yang nilai di kolom "harga_rental" kurang dari atau sama dengan 50000.
### Kesimpulan
Kesimpulan `"SELECT * FROM mobil WHERE harga_rental <= 50000;"` adalah bahwa Anda mencari semua data dari tabel "mobil" di mana nilai kolom "harga_rental" kurang dari atau sama dengan 50000.
## >=
### Struktur
```mysql
SELECT * FROM mobil WHERE harga_rental >= 50000;
```
### Contoh
```mysql
SELECT * FROM mobil WHERE harga_rental >= 50000;
```
### Hasil
![300](Asetdatabase/6.jpG)
### Analisis
 - `SELECT` digunakan untuk memilih kolom atau data yang ingin ditampilkan dalam hasil query.
- Tanda bintang `('*')`  setelah kata kunci SELECT menunjukkan bahwa semua kolom dalam tabel "mobil" akan ditampilkan dalam hasil query.
- `FROM` digunakan untuk menentukan tabel yang akan digunakan dalam query. Dalam kasus ini, tabel yang digunakan adalah "mobil".
- `WHERE` digunakan untuk melakukan filter atau seleksi pada baris-baris data yang memenuhi kondisi tertentu.
- `Kondisi harga_rental >= 50000` menunjukkan bahwa hanya baris-baris data yang memiliki nilai harga_rental yang lebih besar atau sama dengan 50000 yang akan ditampilkan.
### Kesimpulan
Perintah SQL `SELECT * FROM mobil WHERE harga_rental >= 50000;` digunakan untuk mengambil semua data (semua kolom) dari tabel "mobil" di mana nilai pada kolom "harga_rental" lebih besar atau sama dengan 50000.
## < > atau !=
### Struktur
```mysql
SELECT * FROM mobil WHERE harga_rental <> 50000
```
### Contoh
```mysql
 SELECT * FROM mobil WHERE harga_rental <> 50000;
```
### Hasil
![300](Asetdatabase/7.jpG)
### Analisis
- `SELECT` : Ini menentukan bahwa Anda ingin memilih semua kolom dari tabel.
- `FROM mobil` : Ini menentukan nama tabel "mobil" dari mana Anda ingin mengambil datanya.
- `WHERE harga_rental <> 50000` : Ini adalah kondisi yang memfilter baris. Ini hanya memilih baris dimana nilai di kolom "harga_rental" tidak sama dengan 50000.
### Kesimpulan
Kesimpulan dari  `"SELECT * FROM mobil WHERE harga_rental <> 50000;"` adalah bahwa pernyataan tersebut akan mengembalikan semua baris dari tabel "mobil" di mana nilai kolom "harga_rental" tidak sama dengan 50000.
## Tantangan
### Struktur
```mysql
SELECT * FROM akun;
```
### Contoh
```mysql
SELECT pemilik FROM mobil WHERE no_plat="DD 2440 AX";
```
### Hasil
![](Asetdatabase/33.jpg)
### Analisis
- `SELECT pemilik`: Bagian query ini menunjukkan bahwa Anda ingin mengambil nilai dari kolom bernama "pemilik" di tabel yang ditentukan.
- `FROM mobil`: Ini menentukan tabel tempat ingin mengambil data, dalam hal ini, tabel bernama "mobil."
- `WHERE no_plat="DD 2440 AX";`: Menunjukkan bahwa hanya ingin mengambil baris yang nilai di kolom "no_plat" sama dengan "DD 2440 AX."
### Kesimpulan
Kesimpulan dari `SELECT` yang berikan yaitu mencari informasi pemilik mobil dengan nomor plat "DD 2440 AX" dari tabel mobil.
## IN
### Struktur
```mysql
select * from nama_tabel where kolom in('nilai1','nilai2');
```
### Contoh
```mysql
SELECT * FROM mobil WHERE warna in('Silver','Merah');
```
### Hasil
![300](Asetdatabase/8.jpG)
### Analisis
1. `SELECT * FROM mobil` : Pernyataan ini memilih semua kolom dari tabel "mobil".
2. `WHERE warna IN ('Silver', 'Merah')` : WHERE digunakan untuk menerapkan kondisi pada hasil query. kondisi yang diterapkan adalah "warna IN ('Silver', 'Merah')", yang berarti hanya baris dengan nilai kolom "warna" yang sama dengan 'Silver' atau 'Merah' yang akan diambil.
### Kesimpulan
Query ini akan mengambil semua baris dari tabel "mobil" di mana nilai kolom "warna" adalah 'Silver' atau 'Merah'. query ini akan mengembalikan semua informasi tentang mobil-mobil yang memiliki warna 'Silver' atau 'Merah'. Hasilnya akan berupa kumpulan baris yang mewakili mobil-mobil dengan warna yang sesuai dengan kriteria tersebut.
## IN + AND
### Struktur
```mysql
select * from nama_tabel
-> where nama_kolom in ('nilai1','nilai2')
-> AND nama_kolom = nilai3
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE warna in('Hitam','Silver')
-> AND harga_rental = 50000;
```
### Hasil
![300](Asetdatabase/9.jpG)
### Analisis
1. `SELECT * FROM mobil` : memilih semua kolom `(*)` dari tabel "mobil".
2. `WHERE warna in('Hitam','Silver') AND harga_rental = 50000` : Pernyataan WHERE digunakan untuk menerapkan kondisi pada hasil query. terdapat dua kondisi yang diterapkan :
- Kondisi pertama adalah `"warna IN ('Hitam', 'Silver')"`, yang berarti hanya baris dengan nilai kolom "warna" yang sama dengan 'Hitam' atau 'Silver' yang akan diambil.
- Kondisi kedua adalah `"harga_rental = 50000"` , yang berarti hanya baris dengan nilai kolom "harga_rental" yang sama dengan 50000 yang akan diambil.
### Kesimpulan
Kesimpulan dari SQL tersebut adalah mencari semua entri (baris) dalam tabel `"mobil"` di mana nilai kolom `"warna" adalah 'Hitam' atau 'Silver', dan nilai kolom "harga_rental"Silver'` `50000.` query tersebut akan mengembalikan semua data mobil yang memiliki warna `'Hitam' atau 'Silver'` dan `memiliki harga rental sebesar 50000.`
## IN + OR
### Struktur
```mysql
select * from nama_tabel
-> where nama_kolom in('nilai1','nilai2')
-> OR nama_kolom = nilai3
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE warna in('Hitam','Silver')
-> OR harga_rental = 50000;
```
### Hasil
![300](asetdatabase/13.jpg)
### Analisis
- `SELECT *` : Ini memilih semua kolom dari tabel.
- `FROM mobil` : Ini menentukan nama tabel sebagai "mobil" dari mana data akan diambil.
- `WHERE warna IN ('Hitam', 'Silver')` : Kondisi ini memfilter baris berdasarkan nilai pada kolom "warna". Ini memilih baris di mana kolom "warna" memiliki nilai 'Hitam' atau 'Silver'.
- `OR harga_rental = 50000` : Kondisi ini memfilter lebih lanjut baris-baris tersebut dengan memilih baris-baris yang kolom "harga_rental"-nya bernilai 50000.
### Kesimpulan
Kesimpulan SQL adalah untuk mengambil semua data dari tabel "mobil" dimana warna mobil adalah 'Hitam' atau 'Silver', atau harga rental mobil adalah 50000. menggabungkan kondisi OR antara warna mobil dan harga rental, hasilnya akan mencakup semua mobil yang memiliki warna 'Hitam' atau 'Silver', dan juga mobil dengan harga rental sebesar 50000, termasuk mobil yang memenuhi salah satu atau kedua kondisi tersebut.
## IN + AND + OPERATOR
### Struktur
```mysql
select * from nama_tabel
-> where nama_kolom in('nilai1','nilai2')
-> AND nama_kolom > nilai3
```

```mysql
select * FROM nama_tabel
-> where nama_kolom in('nilai1','nilai2')
-> AND nama_kolom < nilai3
```
### Contoh
```mysql
 SELECT * FROM mobil
-> WHERE warna in('Hitam','Silver')
-> AND harga_rental > 50000;
```

```mysql
SELECT * FROM mobil
-> WHERE warna in('Hitam','Silver')
-> AND harga_rental < 50000;
```
### Hasil
![300](asetdatabase/10.jpG)

![300](Asetdatabase/12.jpG)
### Analisis
1. `SELECT * FROM mobil` : Ini akan mengambil semua kolom dari tabel `mobil`.
2. `WHERE warna in('Hitam','Silver')` : Ini akan memfilter data hanya untuk mobil dengan warna hitam atau perak.
3. `AND harga_rental > 50000` : Ini akan memfilter data hanya untuk mobil dengan harga sewa lebih dari 50.000.
### Kesimpulan
Query ini akan mengambil data dari tabel `mobil` yang memiliki warna hitam atau perak dan harga sewa lebih dari 50.000. Hasil dari query ini akan menampilkan semua kolom dari tabel `mobil` yang memenuhi kriteria di atas.
# LIKE
## Mencari awalan
### Struktur 
```mysql
SELECT * FROM mobil
-> WHERE pemilik like 'Ib%';
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'Ib%';
```
### Hasil
![300](asetdatabase/14.jpg)
### Analisis
1. `SELECT * FROM mobil` : Ini akan mengambil semua kolom dari tabel `mobil`.
2. `WHERE pemilik LIKE 'Ib%'` : Ini akan memfilter data hanya untuk mobil yang dimiliki oleh pemilik yang nama awalnya adalah 'Ib'. Tanda persen `'%'` digunakan sebagai wildcard untuk mencari nama pemilik yang dimulai dengan 'Ib' dan mengikuti dengan karakter apapun.
### Kesimpulan
Data dari tabel `mobil` yang dimiliki oleh pemilik dengan nama awal 'Ib'. Hasil dari query ini akan menampilkan semua kolom dari tabel `mobil`
## Mencari akhiran
### Struktur
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '%m';
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '%m';
```
### Hasil
![300](Asetdatabase/15.jpG)
### Analisis
1. `SELECT * FROM mobil` : Ini akan mengambil semua kolom dari tabel `mobil`.
2. `WHERE pemilik LIKE '%m'` : Ini akan memfilter data hanya untuk mobil yang dimiliki oleh pemilik yang nama terakhirnya adalah 'm' atau berisi huruf 'm'. Tanda persen `'%'` digunakan sebagai wildcard untuk mencari nama pemilik yang mengakhiri dengan 'm' atau berisi huruf 'm' di mana saja.
### Kesimpulan
Query ini akan mengambil data dari tabel `mobil` yang dimiliki oleh pemilik dengan nama terakhir 'm' atau berisi huruf 'm'. Hasil dari query ini akan menampilkan semua kolom dari tabel `mobil` yang memenuhi
## Mencari awalan & akhiran
### Struktur
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'b%m';
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'b%m';
```
### Hasil
![300](Asetdatabase/16.jpG)
### Analisis
1. `SELECT * FROM mobil` : Ini akan mengambil semua kolom dari tabel `mobil`.
2. `WHERE pemilik LIKE 'b%m'` : Ini akan memfilter data hanya untuk mobil yang dimiliki oleh pemilik yang nama awalnya dimulai dengan huruf 'b' dan nama terakhirnya berakhir dengan huruf 'm'. Tanda persen `'%'` digunakan sebagai wildcard untuk mencari nama pemilik yang dimulai dengan huruf 'b' dan mengikuti dengan karakter apapun, lalu diakhiri dengan huruf 'm'.
### Kesimpulan
tabel `mobil` yang dimiliki oleh pemilik dengan nama awal dimulai dengan huruf 'b' dan nama terakhir berakhir dengan huruf 'm'. Hasil dari query ini akan menampilkan semua kolom dari tabel `mobil`
## Mencari total karakter
### Struktur
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'I__';
```

```mysql
 SELECT * FROM mobil
-> WHERE pemilik LIKE '___';
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE 'I__';
```

```mysql
 SELECT * FROM mobil
-> WHERE pemilik LIKE '___';
```
### Hasil
![300](asetdatabase/17.jpG)

![300](asetdatabase/18.jpG)
### Analisis
### Kesimpulan
## Kombinasi
### Struktur
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '__r%';
```

```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '_b%';
```
### Contoh
```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '__r%';
```

```mysql
SELECT * FROM mobil
-> WHERE pemilik LIKE '_b%';
```
### Hasil
![](Asetdatabase/19.jpg)

### Analisis
- Mencari semua data dari tabel `mobil` (`SELECT *`).
- Di mana nilai pada kolom `pemilik` (`WHERE pemilik LIKE '__r%'`):
- **LIKE**: Operator untuk mencari pola dalam string.
- `__r%:` Pola pencarian yang digunakan.
- `__` : Mencocoki dua karakter apapun (wildcard).
- `r` : Mencari huruf "r" secara literal.
- `%` : Mencocoki nol karakter atau lebih karakter apapun.

- Mencari semua data dari tabel `mobil` (`SELECT *`).
- Di mana nilai pada kolom `pemilik` (`WHERE pemilik LIKE '_b%'`):
- **LIKE**: Operator untuk mencari pola dalam string.
- **'_b%'**: Pola pencarian yang digunakan.
- `_` : Mencocoki satu karakter apapun.
- `b` : Mencari huruf "b" secara literal.
- `%` : Mencocoki nol karakter atau lebih karakter apapun.
### Kesimpulan
- `LIKE '__r%' `: Mencari data pada tabel `pemilik` dengan nama minimal 3 karakter di awalnya lalu karakter keempat adalah huruf `i`
- `LIKE '_b%' :` Mencari pemilik yang namanya memiliki huruf "b" di **posisi kedua**. Ini akan mengembalikan pemilik dengan nama minimal 3 karakter.
## NOT LIKE
### Struktur
```mysql
SELECT * FROM mobil WHERE peminjam NOT LIKE 'A%';
```
### Contoh
```mysql
SELECT * FROM mobil WHERE peminjam NOT LIKE 'A%';
```
### Hasil
![](Asetdatabase/20.jpg)
### Analisis
1. `SELECT * FROM mobil` : Ini akan mengambil semua kolom dari tabel `mobil`.
2. `WHERE peminjam NOT LIKE 'A%'` : Ini akan memfilter data hanya untuk mobil yang saat ini tidak dipinjam oleh peminjam yang nama awalnya dimulai dengan huruf 'A'. Tanda persen `'%'` digunakan sebagai wildcard untuk mencari nama peminjam yang dimulai dengan huruf 'A' dan mengikuti dengan karakter apapun. Tanda negasi 'NOT' digunakan untuk mengecualikan peminjam dengan nama awal yang dimulai dengan huruf 'A'.
### Kesimpulan
Kesimpulan `"SELECT * FROM mobil WHERE peminjam NOT LIKE 'A%'"` adalah bahwa query tersebut akan mengembalikan semua data dari tabel "mobil" dimana nilai kolom "peminjam" tidak dimulai dengan huruf 'A'.

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
![](Asetdatabase/21.jpg)
### Analisis
- `SELECT :` Menginstruksikan untuk memilih semua kolom (atribut) dari tabel `mobil`.
- `FROM mobil:` Mendefinisikan tabel tempat data akan diambil, yaitu tabel `mobil`.
- `WHERE peminjam IS NULL:` Ini adalah klausa `WHERE` yang memfilter data berdasarkan kondisi tertentu.
- `peminjam:`Merujuk pada kolom pada tabel `mobil` yang kemungkinan berisi nama peminjam kendaraan.
- `IS NULL:`Operator perbandingan yang mengecek apakah nilai pada kolom `peminjam` adalah `NULL`.
### Kesimpulan
- Perintah ini hanya mengembalikan mobil dengan kolom `peminjam` bernilai **NULL** (tidak ada data peminjam).
- Perintah ini membantu dalam mengidentifikasi mobil yang tersedia untuk dipinjam.
- Hasilnya bergantung pada data yang ada di kolom `peminjam` pada tabel `mobil`.
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
![](Asetdatabase/22.jpg)
### Analisis
- `SELECT *`: Ini adalah klausa SELECT yang digunakan untuk memilih semua kolom dari tabel "mobil". Dengan menggunakan tanda bintang (*), kita memilih semua kolom yang ada dalam tabel.
- `FROM mobil`: Ini adalah klausa FROM yang menentukan tabel yang akan digunakan dalam kueri. Dalam hal ini, tabel yang digunakan adalah "mobil".
- `WHERE peminjam IS NOT NULL`: Ini adalah klausa WHERE yang digunakan untuk menerapkan kondisi pada kueri. Kondisi yang diterapkan di sini adalah "peminjam IS NOT NULL", yang berarti hanya baris-baris di mana kolom "peminjam" tidak kosong atau memiliki nilai yang tidak NULL akan dipilih.
### Kesimpulan
Digunakan untuk mengambil semua baris dari tabel  `"mobil"`  di mana kolom  `"peminjam"`  memiliki nilai yang tidak NULL. Hasilnya akan berisi semua kolom dari baris-baris ini.
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
![](Asetdatabase/23.jpg)
### Analisis
- `SELECT *`: Ini adalah klausa SELECT yang digunakan untuk memilih semua kolom dari tabel "mobil". Dengan menggunakan tanda bintang (*), kita memilih semua kolom yang ada dalam tabel.
- `FROM mobil`: Ini adalah klausa FROM yang menentukan tabel yang akan digunakan dalam kueri. Dalam hal ini, tabel yang digunakan adalah "mobil".
- `ORDER BY pemilik ASC`: Ini adalah klausa ORDER BY yang digunakan untuk mengurutkan hasil berdasarkan kolom "pemilik" secara menaik (ascending). Dengan menggunakan ASC, hasil akan diurutkan dari nilai terkecil hingga terbesar berdasarkan kolom "pemilik".
### Kesimpulan
- `SELECT * FROM mobil` mengambil semua data dari tabel `mobil`.
- `ORDER BY pemilik ASC` mengurutkan data berdasarkan kolom `pemilik` secara ascending (terkecil ke besar).
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
![](Asetdatabase/24.jpg)
### Analisis
- `SELECT` : Perintah ini digunakan untuk mengambil semua kolom atau field dari tabel mobil.
- `FROM mobil:` Ini menunjukkan bahwa tabel yang akan digunakan adalah `mobil`.
- `ORDER BY peminjam DESC:` Ini adalah bagian penting dari perintah yang akuntansi database untuk mengurutkan hasil berdasarkan kolom "peminjam" secara menurun (urutan menurun). Artinya, hasilnya akan diurutkan dari nilai yang paling tinggi ke nilai yang paling rendah pada kolom "peminjam".
### Kesimpulan
- Pernyataan ini digunakan untuk mengambil seluruh data dari tabel "mobil".
- Data akan diurutkan berdasarkan kolom "peminjam" secara menurun (descending order). Artinya, data akan disusun dari nilai peminjam terbesar ke terkecil.
- Kesimpulannya, hasil query akan mengembalikan semua baris dari tabel "mobil" dengan urutan berdasarkan kolom "peminjam" dari nilai terbesar ke terkecil.

## Membatasi data yang tampil
## Struktur

## Contoh
## Hasil
### Before


### After


## Analisis

## Kesimpulan
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
![](Asetdatabase/25.jpg)
### Analisis
- `SELECT DISTINCT (harga_rental)` : Ini adalah klausul SELECT yang digunakan untuk memilih kolom "harga_rental". Kata kunci "DISTINCT" digunakan untuk mengambil nilai unik dari kolom tersebut.
- `FROM mobil` : Ini adalah klausul FROM yang menentukan tabel yang digunakan dalam query, yaitu "mobil".
- `ORDER BY harga_rental DESC` : Ini adalah klausul ORDER BY yang digunakan untuk mengurutkan hasil berdasarkan kolom "harga_rental" secara menurun (descending order). Dengan kata lain, hasilnya akan ditampilkan dari harga_rental yang tertinggi ke terendah.
### Kesimpulan
Kesimpulannya, hasil query akan mengembalikan nilai unik dari kolom "harga_rental" dari tabel "mobil", diurutkan dari nilai terbesar ke terkecil. Ini akan memberikan daftar harga rental yang berbeda yang tersedia untuk mobil, tanpa duplikasi, dalam urutan terurut.
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
![](Asetdatabase/26.jpg)
### Analisis
- `SELECT DISTINCT(harga_rental)`: Bagian ini meminta data yang unik dari kolom `harga_rental `dalam tabel `mobil`. Artinya, jika ada nilai yang duplikat, hanya satu nilai yang akan diambil untuk setiap set nilai yang sama. Ini digunakan untuk memastikan bahwa hasil query ini hanya menampilkan nilai-nilai unik.
- `FROM mobil`: Bagian ini menentukan tabel dari mana data diambil. Dalam hal ini, data diambil dari tabel bernama `mobil`.
- `ORDER BY harga_rental DESC`: Bagian ini mengatur urutan hasil query berdasarkan kolom harga_rental dalam urutan menurun (dari yang terbesar ke yang terkecil). Dengan kata lain, hasilnya akan diurutkan sehingga nilai terbesar akan berada di bagian atas.
1. Mengidentifikasi Harga Rental Tertinggi:
- Dengan mengurutkan dalam urutan menurun, kita dapat dengan cepat mengidentifikasi harga rental tertinggi di dalam dataset.
2. Mengidentifikasi Rentang Harga Rental:
- Dengan melihat daftar harga yang unik, kita bisa mengetahui variasi harga rental dan rentang dari tertinggi ke terendah.
3. Analisis Harga Rental Unik:
- Karena menggunakan DISTINCT, query ini bisa membantu menemukan harga rental yang unik tanpa pengulangan, memberikan gambaran tentang berapa banyak variasi harga yang tersedia dalam tabel mobil.
### Kesimpulan
query ini berguna untuk analisis harga rental yang unik dan untuk memahami rentang harga dalam tabel `mobil`, yang dapat digunakan untuk berbagai tujuan, seperti perbandingan harga, analisis pasar, atau pengambilan keputusan bisnis.
# CONCAT,CONCAT_WA,AS
## Menggabungkan kolom tanpa pemisah
### Struktur 
```sql
SELECT CONCAT(nama_kolom1,nama_kolom2) FROM nama_table;
```
### Contoh
```sql
SELECT CONCAT(pemilik,warna) FROM mobil;
```
### Hasil
![](Asetdatabase/27.jpg)
### Analisis
`SELECT DISTINCT(harga_rental)`
untuk mengambil nilai unik dari kolom `harga_rental` dalam `tabel mobil.` `DISTINCT` memastikan bahwa hanya satu dari setiap nilai yang sama ditampilkan dalam hasil. Ini berguna untuk menghindari duplikasi.

### Kesimpulan
mengambil data dari `tabel mobil` dan menggabungkan nilai-nilai dari dua kolom (yaitu `pemilik` dan `Warna`), lalu mengembalikan hasilnya sebagai satu string untuk setiap baris dalam tabel `Mobil`.
## Menggabungkan kolom dengan pemisah
### Struktur 
```sql
SELECT CONCAT_WS("-",no_plat,no_mesin,id_mobil) FROM nama_table;
```
### Contoh
```sql
SELECT CONCAT_WS("-",nama_kolom1,nama_kolom2,nama_kolom3) FROM mobil;

```
### Hasil
![](Asetdatabase/28.jpg)
### Analisis
- `DISTINCT` digunakan untuk memastikan bahwa hanya nilai unik yang diambil. Artinya, jika ada nilai `Harga_Rental` yang sama di beberapa baris, hanya satu yang akan dimasukkan dalam hasil.
- Ini berguna untuk menghilangkan duplikasi dan mendapatkan daftar harga sewa unik.
- `ORDER BY harga_rental desc` menunjukkan bahwa hasil akan diurutkan berdasarkan kolom `harga_rental` dalam urutan menurun (descending).
- Dengan demikian, hasilnya akan menampilkan nilai tertinggi terlebih dahulu, kemudian turun ke yang lebih rendah.
- Hasil akhir adalah daftar nilai unik dari `harga_rental` dalam tabel `mobil`, yang diurutkan dari nilai tertinggi ke terendah.
- Jika `Harga_Rental` memiliki berbagai nilai seperti 500, 400, 300, 500, dan 200, hasilnya akan menjadi 500, 400, 300, dan 200, dengan nilai 500 hanya muncul sekali karena penggunaan `DISTINCT`.
### Kesimpulan
memberikan cara untuk mengambil daftar harga rental unik dari tabel `mobil`, dan mengurutkannya dalam urutan menurun, menampilkan nilai tertinggi di depan.
## Memberi nama kolom alias
### Struktur 
```sql
SELECT CONCAT_WS("+",nama_kolom1,nama_kolom2) AS COLLAB FROM nama_table;
```
### Contoh
```sql
SELECT CONCAT_WS("+",pemilik,peminjam) AS COLLAB FROM mobil;
```
### Hasil
![](Asetdatabase/29.jpg)
### Analisis
- `CONCAT_WS` adalah fungsi yang menggabungkan beberapa string dan memasukkan delimiter (pemisah) di antara mereka.
- Pada pernyataan ini, simbol `+` digunakan sebagai delimiter untuk menggabungkan nilai dari kolom `Pemilik` dan `peminjam`.
- Setelah penggabungan, hasilnya diberi alias dengan nama `COLLAB`.
- Jadi, hasil dari pernyataan ini adalah daftar gabungan nilai dari kolom `pemilik` dan peminjam dengan simbol `+` di antaranya, lalu hasil ini diberi nama `COLLAB`.
- Hasil akan menunjukkan kombinasi unik dari `pemilik` dan `peminjam` dengan simbol `+ `sebagai separator.
- Misalnya, jika `pemilik` adalah "John" dan `peminjam` adalah "Doe", maka hasilnya adalah "John+Doe".
- Jika ada baris dalam tabel `mobil` dengan kombinasi yang berbeda, seperti `pemilik` adalah "Jane" dan `peminjam` adalah "Smith", maka hasilnya akan menjadi "Jane+Smith".
- Pernyataan ini dapat digunakan untuk membuat representasi unik dari hubungan antara pemilik dan peminjam dalam tabel `mobil`.
- Ini berguna untuk mengidentifikasi kolaborasi atau interaksi antara dua entitas dalam tabel tersebut.
- Penggunaan `CONCAT_WS` memudahkan untuk memasukkan pemisah tanpa menambahkan spasi ekstra atau perlu memeriksa apakah ada nilai kosong.
### Kesimpulan
memungkinkan Anda untuk menggabungkan dua kolom (`pemilik` dan `peminjam`) dari tabel `mobil`, dengan simbol `+` sebagai separator, dan memberikan nama alias "`COLLAB`" untuk hasil gabungan tersebut. Hasil akhir adalah daftar kombinasi unik dengan format yang mudah dibaca dan digunakan.
# VIEW
## Membuat tabel virtual
### Struktur 
```sql
CREATE VIEW nama_table AS
SELECT nama_kolom1, nama_kolom2, nama_kolom3, nama_kolom4
FROM nama_table
WHERE nama_kolom5= "Ibrahim";
```
### Contoh
```sql
CREATE VIEW info_no_plat AS
SELECT id_mobil, no_plat, pemilik, peminjam
FROM mobil
WHERE pemilik = "Ibrahim";
```
### Hasil
![](Asetdatabase/30.jpg)
### Analisis
- View yang dibuat diberi nama `info_no_plat.
- Query memilih beberapa kolom dari tabel `mobil: id_mobil, no_plat, pemilik, dan peminjam.`
- Jadi, view ini akan berisi informasi tentang `ID mobil, nomor plat, pemilik, dan peminjam `dari tabel `mobil`.
- Kondisi `WHERE` dalam query memastikan bahwa hanya baris dengan pemilik bernama "Ibrahim" yang akan masuk ke view.
- Dengan kata lain, view ini hanya akan menampilkan data tentang mobil yang dimiliki oleh "Ibrahim".
- View `info_no_plat` mungkin dibuat untuk mendapatkan informasi tentang mobil-mobil yang dimiliki oleh "Ibrahim", termasuk ID mobil, nomor plat, pemilik, dan peminjam.
- Penggunaan view memudahkan untuk mengakses dan mengelola informasi spesifik tanpa harus menulis query ulang setiap kali ingin melihat data mobil milik "Ibrahim".
- View memungkinkan Anda untuk menyederhanakan akses ke data tertentu. Misalnya, ketika Anda perlu memeriksa mobil yang dimiliki oleh "Ibrahim", Anda hanya perlu mengakses view ini.
- Ini juga dapat digunakan untuk membuat antarmuka data yang lebih mudah dikelola atau memberikan akses yang terbatas kepada pengguna tertentu.
### Kesimpulan
ini membuat view bernama `info_no_plat` yang menyaring data dari tabel `mobil` untuk hanya menampilkan mobil yang dimiliki oleh "Ibrahim", beserta beberapa kolom seperti `id_mobil, no_plat, pemilik, dan peminjam`. View ini memberikan cara yang mudah untuk melihat dan mengelola data tersebut.
## Menampilkan tabel virtual
### Struktur 
```sql
SELECT * FROM nama_table;
```
### Contoh
```sql
SELECT * FROM info_no_plat;
```
### Hasil
![](Asetdatabase/31.jpg)
### Analisis

- `SELECT * FROM` : Merupakan query awal untuk menampilkan sebuah tabel virtual yang didalamnya berisikan kolom, di mana kolom tersebut menampung sebuah data.
- `info_no_plat` nama dari tabel virtual.

### kesimpulan

Jika ingin menampilkan tabel virtual cukup dengan perintah SELECT * FROM.
## Menghapus tabel virtual
### Struktur 
```sql
DROP VIEW nama_table;
```
### Contoh
```sql
DROP VIEW info_no_plat;
```
### Hasil
![](Asetdatabase/32.jpg)
### Analisis
- `DROP VIEW` perintah query tersebut akan menghapus tabel virtual.
- `info_no_plat` nama tabel virtual yang akan di hapus.

### kesimpulan

Jika ingin menghapus tabel virtual cukup dengan perintah DROP VIEW.


# Tantangan
## Mobil Tanpa Peminjam
### Kode
```sql
CREATE VIEW mobil_Tanpa_peminjam AS
Select no_plat,peminjam
From mobil
WHERE peminjam IS NULL ;
```
### Hasil
![a](Asetdatabase/41.jpg)
### Analisis
CREATE VIEW mobil_Tanpa_peminjam AS`: adalah perintah untuk membuat sebuah `view` baru dalam basis data dengan nama `mobil_Tanpa_peminjam`.
- `SELECT no_plat, peminjam`: adalah perintah untuk memilih dua kolom, yaitu `no_plat dan peminjam`, dari tabel `mobil`.
- `FROM mobil`: Menunjukkan bahwa data diambil dari tabel bernama `mobil`.
- `WHERE peminjam IS NULL`:  adalah klausa WHERE yang menyaring baris-baris dari tabel mobil dimana nilai `kolom peminjam` adalah `NULL`.

- `SELECT *`: adalah perintah untuk memilih semua kolom dari `view atau tabel`.
- `FROM mobil_Tanpa_peminjam`: Menunjukkan bahwa data diambil dari view yang disebut `mobil_Tanpa_peminjam`, yang telah dibuat sebelumnya.
### Kesimpulan 
`CREATE VIEW mobil_Tanpa_peminjam AS Select no_plat, peminjam From mobil WHERE peminjam IS NULL;` digunakan untuk membuat sebuah `view` baru bernama `mobil_Tanpa_peminjam`. `Viewnya` berisi dua kolom, yaitu `no_plat` dan `peminjam`, yang diambil dari tabel `mobil` Hanya baris-baris yang memiliki nilai `NULL` pada kolom `peminjam` yang dimasukkan ke dalam `view`. 

`SELECT * FROM mobil_Tanpa_peminjam;` digunakan untuk menampilkan semua data dari `view mobil_Tanpa_peminjam`, yang telah dibuat sebelumnya dengan kriteria yang bernilai `NULL`.
## Update Mobil
### Kode
```sql
UPDATE mobil
SET peminjam = NULL
where peminjam =  'Elia' ;
```
### Hasil
![](Asetdatabase/42.jpg)
### Analisis
- `UPDATE mobil`: adalah perintah untuk memperbarui data dalam tabel yang disebut `mobil`.
- `SET peminjam= NULL`: menetapkan nilai kolom peminjam menjadi `NULL`.
- `WHERE peminjam= 'Elia'`: adalah klausa WHERE yang membatasi update hanya pada baris-baris dimana nilai kolom peminjam adalah `'Elia'`. Maksudnya perubahan hanya akan berlaku untuk baris-baris yang memiliki peminjam dengan nama `'Elia'`.

- `SELECT *`: adalah perintah untuk memilih semua kolom dari view atau tabel.
- `FROM mobil_Tanpa_peminjam`: Menunjukkan bahwa data diambil dari view yang disebut "mobil_Tanpa_peminjam", yang telah dibuat sebelumnya.
### Kesimpulan
`UPDATE mobil SET peminjam = NULL WHERE peminjam = 'Elia';`nilai pada kolom `peminjam` pada tabel `mobil`yang memiliki nilai `'Elia'` akan diubah menjadi `NULL`.
Kesimpulannya, perintah digunakan untuk menghapus atau mengubah nilai `peminjam` menjadi `NULL` untuk semua entri di tabel `mobil` dimana `peminjam`memiliki nilai `'Elia'`.

`SELECT * FROM mobil_Tanpa_peminjam;` digunakan untuk menampilkan semua data dari `view mobil_Tanpa_peminjam`, yang telah dibuat sebelumnya dengan mengubah atau menghapus nilai `peminjam` menjadi `NULL` untuk tabel `mobil` dimana peminjam memiliki nilai `Elia`.
## Kesimpulan 
Berikan Kesimpulan mengapa tabel Virtual 1,2 ini dibuat?
View dapat digunakan untuk menyaring data yang sesuai dengan kriteria tertentu, seperti menampilkan entri yang memiliki nilai NULL pada kolom tertentu atau mengubah salah satu data peminjam menjadi NULL. memberikan pandangan yang jelas tentang mobil yang tersedia untuk disewakan atau yang belum dipinjam.
Dengan membuat view dapat membatasi akses ke data sensitif atau kolom tertentu dari tabel yang mungkin tidak perlu diakses oleh semua pengguna.
Dengan membuat view untuk kueri yang sering digunakan, Anda dapat menghindari pengulangan kode SQL yang sama di beberapa tempat dalam aplikasi atau prosedur penyimpanan.


# Agreasi
## Sum
### Struktur 
```sql
select SUM(nama_kolom) AS total
From nama_table
Where kondisi_opsional;
```
### Contoh 
```sql
select SUM(harga_rental) from mobil;
```
### Hasil 
![](Asetdatabase/34.jpg)
### Analisis
- `SELECT`: Digunakan untuk mengambil data dari database.
- `SUM(): `Fungsi agregat dalam SQL yang digunakan untuk menghitung jumlah nilai dalam kolom.
- `harga_rental`: Ini adalah nama kolom yang ingin Anda hitung jumlahnya.
- `FROM mobil:` Menentukan tabel dari mana Anda ingin mengambil datanya, dalam hal ini, tabel bernama `mobil`.
### Kesimpulan
Kesimpulan dari pernyataan `SQL SELECT ``SUM(harga_rental)`` FROM mobil;` adalah bahwa Anda ingin menghitung jumlah total `harga_rental` dari semua mobil yang ada dalam tabel mobil.

## Count
### Struktur 
```sql
select Count(*) AS jumlah
From nama_table
Where kondisi_opsional;
```
### Contoh 
```sql
select Count(Peminjam) from mobil;
```
```sql
select Count(pemilik) from mobil;
```
### Hasil 
![](Asetdatabase/35.jpg)
### Analisis
#### pemilik

- `select :`Kata kunci ini digunakan untuk mengambil data dari database.
- `COUNT() :` Ini adalah fungsi agregat yang menghitung jumlah baris yang dikembalikan oleh kueri. Dalam hal ini, ia akan menghitung jumlah nilai bukan nol pada kolom `pemilik`.
- `pemilik` : Ini nama kolomnya. Fungsi ini `COUNT()`akan menghitung jumlah nilai bukan nol di kolom ini.
- `FROM mobil : `Ini menentukan tabel dari mana data akan diambil. Dalam hal ini, itu adalah tabel `mobil`. peminjam
- `SELECT`: Kata kunci ini digunakan untuk mengambil data dari database.
- `COUNT(peminjam)`: Fungsi ini menghitung jumlah nilai bukan nol pada kolom yang ditentukan, dalam hal ini, `peminjam`.
- `FROM mobil`: Ini menentukan tabel untuk mengambil data, dalam hal ini, tabel bernama `mobil`.
### Kesimpulan
pemilik Kesimpulan dari `SELECT COUNT(pemilik) FROM mobil;` adalah bahwa Anda ingin menghitung jumlah entri unik dalam kolom `pemilik` dari tabel `mobil`.

peminjam Kesimpulan dari `SELECT COUNT(peminjam) FROM mobil; `adalah bahwa Anda ingin menghitung jumlah entri unik dalam kolom `peminjam` dari tabel `mobil`. Hasilnya akan memberikan jumlah `peminjam` `mobil` yang terdaftar dalam tabel.

## Min
### Struktur 
```sql
select Min(nama_kolom) AS nilai_minimum
From nama_table
Where kondisi_opsional;
```
### Contoh 
```sql
select Min(harga_rental) AS minimal from mobil;
```
### Hasil 
![](Asetdatabase/38.jpg)

### Analisis

### Kesimpulan

## Max
### Struktur 
```sql
select Max(nama_kolom) AS nilai_maksimal
From nama_table
Where kondisi_opsional;
```
### Contoh 
```sql
select Max(harga_rental) AS maximal from mobil;
```
### Hasil 
![](Asetdatabase/39.jpg)
### Analisis

### Kesimpulan

## Avg
### Struktur 
```sql
select avg(nama_kolom) AS nilai_rata-rata
From nama_table
Where kondisi_opsional;
```
### Contoh 
```sql
select AVG(harga_rental) AS RATA_RATA from mobil;
```
### Hasil 
![](Asetdatabase/40.jpg)
### Analisis

### Kesimpulan




## Analisis

## Kesimpulan

