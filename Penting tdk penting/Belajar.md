# Anatomi CSS
## Code
```css
P {
Color: red;
}
```
## Penjelasan
- Tag `<p>` adalah selector yang ingin di modifikasi. 
- property adalah color pada komponen textnya
- property values adalah red kita mau modifikasi seperti apa warnanya
## Kesimpulan
warna teks (text color) dari elemen HTML yang memiliki tag` P` akan diubah menjadi merah (red).
# percobaan pertama
## kode css
```css
p {
	color: red;
}
```
## Hasil
### before
![[Pasted image 20240303203552.png]]
### after
![[Pasted image 20240303204434.png]]
## penjelasan
Kode CSS di atas `p { color: red; }` memiliki arti bahwa semua elemen HTML dengan tag `<p>` (paragraf) akan memiliki warna teks merah. Ini berarti setiap teks yang ada di dalam elemen `<p>` akan ditampilkan dengan warna merah.
Jadi, kesimpulan dari kode program tersebut adalah bahwa semua teks di dalam elemen paragraf `<p>` akan ditampilkan dengan warna merah.
# percobaan kedua
## kode css
```css
 button {
      width: 150px;
      height: 50px;
      text-transform: uppercase;
      font-size: 20px;
      padding-left: 20px;
    }
```

## text - transform
### Before

![[Pasted image 20240219120910.png]]

### After
![[Pasted image 20240219121004.png]]



### Penjelasan 
Properti `text-transform: uppercase;` dalam CSS digunakan untuk mengubah semua karakter teks di dalam elemen menjadi huruf kapital besar. Ini berarti bahwa tidak peduli bagaimana teks itu awalnya ditulis, itu akan ditampilkan dalam huruf kapital. Misalnya, jika teks aslinya adalah "klik aku!", dengan menggunakan `text-transform: uppercase;`, teks tersebut akan ditampilkan sebagai "KLIK AKU!".
### kesimpulan
Dengan kode CSS tersebut, semua teks dalam elemen akan ditampilkan dalam huruf kapital,
berguna jika Anda ingin memastikan bahwa teks tertentu ditampilkan dalam huruf kapital, terlepas dari bagaimana teks itu ditulis dalam kode HTML.
## Font -  size
### Before
![[Pasted image 20240219120910.png]]
### After
![[Pasted image 20240219121213.png]]

### Penjelasan
Properti `font-size` dalam CSS digunakan untuk menentukan ukuran font teks dalam elemen yang dipilih. Ini memungkinkan pengaturan ukuran font untuk teks di dalam elemen HTML, dan dapat diatur dalam berbagai unit pengukuran seperti piksel (px), em, atau persen (%), di antara yang lain.
### contoh
font-size: 20px ini adalah ukuran teks yang digunakan dalam desain web atau pengaturan tata letak halaman. Ukuran 20px adalah ukuran yang cukup besar untuk teks, membuatnya mudah dibaca oleh pengguna. Namun, ukuran teks yang tepat untuk digunakan tergantung pada desain keseluruhan situs web atau halaman, serta preferensi pengguna dan kebutuhan konten.
## Padding life
### Before
![[Pasted image 20240219120910.png]]
### After
![[Pasted image 20240219121451.png]]
### Penjelasan
Properti `padding-left` dalam CSS digunakan untuk menentukan jarak atau ruang (padding) yang akan diberikan di sebelah kiri isi dari suatu elemen. Padding adalah ruang tambahan di sekeliling isi elemen, yang membantu mengatur jarak antara isi elemen dan batas atau tepi elemen itu sendiri.
### contoh
penggunaan padding-left: 20px adalah untuk memberikan ruang kosong sebesar 20 piksel di sebelah kiri elemen yang bersangkutan, yang dapat berguna untuk menciptakan tata letak yang lebih rapi dan terorganisir dalam desain halaman web.

# Text
## Text align
### penjelasan
`text-align` pada CSS digunakan untuk mengatur posisi horizontal teks di dalam sebuah elemen. Properti ini dapat memiliki beberapa nilai, di antaranya:
- `text-align:left` ; Text akan ditampilkan di sebelah kiri dokumen.
- `text-align:right` ; Text akan ditampilkan di sebelah kanan dokumen.
- `text-align:center `; Text akan ditampilkan di tengah-tengah dokumen.
- `text-align:justify` ; Text akan ditampilkan dengan mengikuti spasi yang ada di antara kata-kata.
### kode program
```css
p {
text-align: center;
}
```
### hasil
#### before
#### after
### kesimpulan 
dari kode program yang diberikan `p { text-align: center; }` adalah bahwa kode ini mengatur properti CSS `text-align` untuk elemen `<p>` (paragraf) dalam sebuah dokumen HTML. Dengan nilai `center`, semua teks dalam elemen `<p>` akan diatur ke tengah dari elemen tersebut.
Jadi, jika Anda menggunakan kode ini dalam dokumen HTML, semua teks dalam elemen `<p>` akan ditampilkan dengan rata tengah. 
## Text decoration
### penjelasan
`text-decoration` adalah properti CSS yang digunakan untuk mengatur dekorasi teks seperti garis melintang, garis bawah, garis atas, dan garis tepi.
Berikut adalah beberapa nilai yang dapat digunakan untuk properti `text-decoration`:
- `none` : menghilangkan dekorasi garis pada teks (pilihan default).
- `underline` : menambahkan garis bawah pada teks.
- `overline` : menambahkan garis atas pada teks.
- `line-through` : menambahkan garis horizontal yang menembus tengah teks, sehingga tampak tercoret.
### kode program
```css
p {
text-decoration: line-through;
}
```
### hasil
#### before
#### after
### kesimpulan
dari kode program tersebut adalah bahwa semua elemen `<p>` (paragraf) dalam dokumen HTML akan ditampilkan dengan dekorasi garis melintang (`line-through`) pada teksnya. Artinya, teks di dalam setiap elemen `<p>` akan memiliki garis melintang di atasnya saat ditampilkan di browser.



## Text transform
### penjelasan
`text-transform` digunakan untuk mengontrol transformasi teks dalam elemen HTML. Properti ini memungkinkan Anda untuk mengubah tampilan teks, seperti membuatnya menjadi huruf kapital, huruf kecil, atau mengubah huruf pertama setiap kata menjadi huruf besar (kapital).
Berikut adalah nilai-nilai yang dapat digunakan untuk properti `text-transform`:
- `none (default)`: Menjaga kapitalisasi teks seperti pada penulisan aslinya.
- `uppercase` : Mengubah semua huruf menjadi huruf besar (uppercase).
- `lowercase`: Mengubah semua huruf menjadi huruf kecil (lowercase).
- `capitalize` : Mengubah huruf pertama setiap kata menjadi huruf besar (capitalize), mirip gaya penulisan judul.
### kode program 
```css
p {
text-transform: uppercase;
}
```
### hasil
#### before
#### after
### kesimpulan
Kode program di atas menunjukkan bahwa teks di dalam elemen dengan tag `<p>` akan ditampilkan dalam huruf kapital (`uppercase`).Jadi, kode program tersebut adalah bahwa semua teks di dalam elemen `<p>` akan ditampilkan dalam huruf kapital atau huruf besar.
## Text indent
### penjelasan
Text indent atau indentasi teks adalah proses membuat jarak antara teks dengan margin atas dari sebuah paragraf. Ini dapat membuat teks terlihat lebih rapi dan terstruktur. Teks dapat diatur dengan menggunakan tanda indentasi seperti tab atau spasi.
### kode program 
```css
p {
text-indent: 100px;
}
```
### hasil
#### before
#### after

### kesimpulan
Kode program di atas menunjukkan bahwa elemen dengan tag `<p>` akan memiliki `indentasi` teks sebesar 100 piksel dari margin kiri. Ini berarti bahwa setiap paragraf dalam elemen `<p>` akan dimulai dengan jarak atau `indentasi` sebesar 100 piksel dari sisi kiri halaman atau elemen yang mengandungnya.
Jadi, kesimpulan dari kode program tersebut adalah bahwa setiap paragraf dalam elemen `<p>` akan dimulai dengan `indentasi` teks sebesar 100 piksel dari margin kiri.
## Letter spacing
### penjelasan
Letter spacing merujuk pada jarak horizontal antara huruf-huruf dalam sebuah teks. kata lain, letter spacing mengontrol seberapa dekat atau berjauhan huruf-huruf tersebut ditempatkan satu sama lain.
### kode program
```css
p {
letter-spacing: 50px;
}
```
### hasil
#### before
#### after

### kesimpulan
Kode program di atas menunjukkan bahwa elemen dengan tag `<p>` akan memiliki jarak antar huruf sebesar 50 piksel (`letter-spacing: 50px;`). Ini berarti teks di dalam elemen tersebut akan ditampilkan dengan jarak yang lebih lebar antar hurufnya.
Jadi, kesimpulan dari kode program tersebut adalah bahwa semua teks di dalam elemen `<p>` akan ditampilkan dengan jarak antar huruf sebesar 50 piksel.
## Line height
### penjelasan
Line height adalah properti dalam CSS yang menentukan *jarak vertikal* antara baris teks dalam sebuah elemen, biasanya elemen paragraf (`<p>`).
### kode program
```css
p {
line-height: 150px;
}
```
### hasil
#### before
#### after
### kesimpulan
Kode program di atas menunjukkan bahwa semua elemen dengan tag `<p>` akan memiliki tinggi baris (`line-height`) sebesar 150 piksel. Ini berarti jarak antara garis teks di dalam elemen `<p>` akan diperbesar menjadi 150 piksel.f
Dengan demikian, kesimpulan dari kode program tersebut adalah bahwa semua teks di dalam elemen `<p>` akan memiliki jarak antarbaris sebesar 150 piksel. Hal ini dapat mempengaruhi tata letak dan penampilan teks di dalam elemen tersebut. Semakin besar nilai `line-height`, semakin besar pula jarak antarbarisnya.


## Word spacing
### penjelasan
Word spacing merujuk pada pengaturan jarak antara kata dalam teks.
### kode program
```css
p {
word-spacing: 150px;
}
```
### hasil
#### before
#### after
### kesimpulan
Kode program tersebut, `p { word-spacing: 150px; }`, akan memberikan spasi antara kata-kata di dalam elemen `<p>` sebesar 150 piksel.
Jadi, kesimpulan dari kode program tersebut adalah bahwa semua kata di dalam elemen `<p>` akan memiliki jarak antar kata sebesar 150 piksel. Ini berarti bahwa setiap kata akan terpisah dengan jarak yang cukup besar, membuatnya terlihat lebih terpisah dalam tampilan teks tersebut.

# Backgaround
## Background color
### penejelasan
`background-color` adalah sebuah properti CSS yang digunakan untuk menentukan warna latar belakang dari suatu elemen HTML. Properti ini dapat digunakan untuk mengubah warna latar belakang dari berbagai elemen, seperti halaman web, bagian dari halaman web (seperti div atau paragraf), tombol, kotak, dan lain sebagainya.
###  kode program
```Css
body {
	background-color: purple;
} 
```
### hasil
### kesimpulan
Kode program di atas menunjukkan bahwa tombol (elemen dengan tag `<button>`) akan memiliki latar belakang berwarna ungu (`purple`). Dengan demikian, kode program tersebut adalah bahwa semua tombol di halaman web akan memiliki latar belakang berwarna ungu.
## Background-image
### penjelasan
Background image adalah gambar yang digunakan sebagai latar belakang di halaman web, aplikasi, atau dokumen digital lainnya.
### kode program
```css
body {
background-image: url("3.jpg");
}
```
### hasil
#### before
#### after
### kesimpulan
Kode program di atas menunjukkan bahwa latar belakang (`background`) dari elemen `<body>` akan menggunakan gambar dengan nama file "3.jpg" sebagai background image.
kesimpulan dari kode program tersebut adalah bahwa latar belakang dari halaman web atau dokumen HTML akan ditampilkan dengan gambar "3.jpg" sebagai background image.
## Background-repeat
### penjelasan
Background-repeat digunakan untuk mengatur bagaimana sebuah gambar background akan diulang atau tidak diulang.
### kode program
```css
body {
background-repeat: no-repeat;
}
```
### hasil
#### before
#### after
### kesimpulan
Kode program di atas menunjukkan bahwa gambar latar belakang pada halaman HTML tidak akan diulang atau diulang (`background-repeat: no-repeat`). Ini berarti gambar latar belakang akan ditampilkan sekali saja di dalam area halaman, dan tidak akan diulang baik secara horizontal maupun vertikal.
Jadi, kesimpulan dari kode program tersebut adalah bahwa gambar latar belakang pada halaman HTML akan ditampilkan sekali saja, tanpa diulang baik secara horizontal maupun vertikal.
## Background-attachment
### penjelasan
Background-attachment digunakan untuk mengatur bagaimana sebuah gambar background akan bergerak atau tidak bergerak dalam halaman.
### kode program
```css
body { 
background-attachment: fixed; 
}
```
### hasil
#### before
#### after
### kesimpulan
Kode CSS di atas, `body { background-attachment: fixed; }`, menetapkan bahwa gambar latar belakang pada halaman HTML akan memiliki sifat tetap (`fixed`). Ini berarti gambar latar belakang akan tetap pada posisinya relatif terhadap jendela browser, dan tidak akan bergerak saat halaman digulir.
Jadi, kesimpulan dari kode tersebut adalah bahwa gambar latar belakang pada halaman HTML akan memiliki sifat tetap dan tidak akan bergerak saat halaman digulir.
## Background-size
### penjelasan
`background-size` adalah properti dalam CSS yang digunakan untuk mengontrol ukuran dari gambar latar belakang pada suatu elemen. Properti ini memungkinkan Anda untuk menentukan seberapa besar gambar latar belakang akan ditampilkan di dalam elemen tersebut.
### kode program
```css
body {
background-size: 200px 300px;
}
```
### hasil
#### before
#### after
### kesimpulan
Kode CSS di atas menunjukkan bahwa gambar latar belakang pada halaman HTML akan ditampilkan dengan ukuran 200 piksel lebar dan 300 piksel tinggi (`background-size: 200px 300px;`).
Jadi, kesimpulan dari kode program tersebut adalah bahwa gambar latar belakang pada halaman HTML akan diberikan ukuran 200 piksel lebar dan 300 piksel tinggi.

## Background-position
### penjelasan
`background-position` adalah properti dalam CSS yang digunakan untuk mengatur posisi dari gambar latar belakang pada sebuah elemen. Properti ini memungkinkan Anda untuk menentukan di mana gambar latar belakang akan ditampilkan di dalam elemen tersebut.
Berikut adalah beberapa nilai yang bisa digunakan untuk properti `background-position`:
1. Nilai dalam persentase (misalnya `50% 25%`): Anda bisa menentukan posisi horizontal dan vertikal gambar latar belakang dengan nilai dalam persentase dari ukuran elemen tersebut. Contoh: `background-position: 50% 25%;` akan menempatkan gambar latar belakang di tengah horizontal dan 25% dari atas.
2. Nilai dalam satuan piksel (misalnya `10px 20px`): Anda juga bisa menentukan posisi gambar latar belakang secara eksplisit dengan nilai dalam satuan piksel. Contoh: `background-position: 10px 20px;` akan menempatkan gambar latar belakang 10 piksel dari kiri dan 20 piksel dari atas.
3. Kata kunci (misalnya `top`, `bottom`, `left`, `right`, `center`): Anda bisa menggunakan kata kunci untuk menentukan posisi gambar latar belakang. Contoh: `background-position: top center;` akan menempatkan gambar latar belakang di bagian atas dan di tengah horizontal.
### kode program 
### hasil
#### before 
#### after
### kesimpulan

# font
## Font-size
### penjelasan
`font-size` adalah properti CSS yang digunakan untuk mengatur ukuran teks pada elemen. Properti ini menentukan ukuran dari huruf atau teks yang akan ditampilkan.
### kode program
```css
p {
  font-size: 65px;
}
```
### hasil
#### before
#### after
![[Pasted image 20240303205904.png]]
### kesimpulan
Kode program di atas menunjukkan bahwa semua teks di dalam elemen `<p>` akan memiliki ukuran font sebesar 65 piksel (`font-size: 65px;`).
Jadi, kesimpulan dari kode program tersebut adalah bahwa semua teks di dalam elemen `<p>` akan ditampilkan dengan ukuran font sebesar 65 piksel.

## Font-style
### penjelasan
`font-style` adalah properti CSS yang digunakan untuk mengubah gaya huruf teks pada elemen HTML. Properti ini dapat digunakan untuk memberikan efek miring (italic) pada teks.
Nilai yang dapat diberikan pada properti `font-style` antara lain:
- `normal`: Menetapkan gaya huruf normal (tidak miring).
- `italic`: Menetapkan gaya huruf miring (italic).
- `oblique`: Mirip dengan `italic`, tetapi cenderung lebih langsung ke depan daripada miring.
### kode program
```css
p {
 font-style: italic;
}
```
### hasil
#### before
#### after
![[Pasted image 20240303210901.png]]
### kesimpulan
Kode program di atas menunjukkan bahwa teks di dalam elemen `<p>` akan memiliki gaya huruf miring (`italic`). Ini berarti teks di dalam elemen `<p>` akan ditampilkan dalam gaya huruf miring.
Jadi, kesimpulan dari kode program tersebut adalah bahwa semua teks di dalam elemen `<p>` akan ditampilkan dalam gaya huruf miring.

## Font-weight
### penjelasan
`font-weight` adalah properti CSS yang digunakan untuk mengatur ketebalan (berat) teks pada elemen. Properti ini mengontrol seberapa tebal atau tipis teks akan ditampilkan. Berikut adalah beberapa nilai umum yang bisa digunakan untuk `font-weight`:
1. `normal`: Menetapkan teks dengan berat normal.
2. `bold`: Menetapkan teks dengan berat tebal.
3. `lighter`: Menetapkan teks dengan berat lebih ringan dari teks normal.
4. `bolder`: Menetapkan teks dengan berat lebih tebal dari teks normal.
### kode program
```css
p {
 font-weight: bold;
}
```
### hasil
#### before
#### after
![[Pasted image 20240303211408.png]]
### kesimpulan
Kode program di atas menunjukkan bahwa teks di dalam elemen `<p>` akan ditampilkan dengan tebal (`font-weight: bold`). Ini berarti teks di dalam elemen `<p>` akan memiliki ketebalan yang lebih besar dari teks biasa.
Jadi, kesimpulan dari kode program tersebut adalah bahwa semua teks di dalam elemen `<p>` akan ditampilkan dengan tebal.
## Font-family
### penjelasan
`font-family` adalah properti CSS yang digunakan untuk menentukan jenis font atau jenis font yang akan digunakan untuk teks di dalam elemen HTML. Properti ini memungkinkan Anda untuk menentukan satu atau beberapa jenis font yang akan digunakan, serta memprioritaskan urutan jika font yang pertama tidak tersedia.
Contoh penggunaan `font-family`:
- `Arial` adalah jenis font yang pertama akan digunakan. Jika font Arial tidak tersedia, maka CSS akan mencari jenis font berikutnya dalam daftar.
- `sans-serif` adalah jenis font cadangan jika Arial tidak tersedia. Jenis font ini merupakan salah satu dari kategori font tanpa serif (tanpa dekoratif) yang lebih mudah dibaca di layar.
### kode program 
```css
p {
  font-family: Arial, sans-serif;
}
```
### hasil
#### before
#### after
![[Pasted image 20240303213318.png]]
### kesimpulan
Kode program di atas menunjukkan bahwa teks di dalam elemen dengan tag `<p>` akan ditampilkan dengan jenis `font Arial`, jika font tersebut tersedia. Jika Arial tidak tersedia, maka jenis `font sans-serif` akan digunakan sebagai alternatif.
Jadi, kesimpulan dari kode program tersebut adalah bahwa teks di dalam elemen `<p>` akan ditampilkan dengan jenis `font Arial` jika tersedia, dan jika tidak tersedia, `jenis font sans-serif` akan digunakan sebagai alternatif.
# Latihan Box-Model
### kode program
```css
p {
  font-size: 65px;
  font-style: italic;
  margin-top: 150px;
  margin-left: 200px;
  color: white;
}

img {
  margin-right: 200px;
  margin-top: 50px;
  border: 10px  solid white;
  border-radius: 1500% 1500%;
}

button {
    background-color:purple;
  width: 150px;
  height: 60px;
  border-width: 2px;
  border-style: solid;
  border-color:white ;
  color: orangered;
  margin-bottom: 20px;
  margin-left: 390px;
}
```
### hasil
 ![[Pasted image 20240303175146.png]]
### penjelasan & kesimpulan
Kode CSS tersebut digunakan untuk mengubah tampilan teks pada elemen `<p>` (paragraf) dalam halaman web. Berikut adalah penjelasan dari setiap properti CSS yang digunakan:
1. `font-size: 65px;`: Properti ini menentukan ukuran font teks pada elemen `<p>` sebesar 65 piksel. 
2. `font-style: italic;`: Properti ini membuat teks pada elemen `<p>` menjadi miring (italic).
3. `margin-top: 150px;`: Properti ini memberikan jarak (margin) sebesar 150 piksel di bagian atas elemen `<p>`, sehingga menjaga jarak antara elemen ini dengan elemen-elemen di atasnya. 
4. `margin-left: 200px;`: Properti ini memberikan jarak (margin) sebesar 200 piksel di sebelah kiri elemen `<p>`, sehingga menjaga jarak antara elemen ini dengan elemen-elemen di sebelah kirinya.
5. `color: white;`: Properti ini menetapkan warna teks pada elemen `<p>` menjadi putih. 
Dengan demikian, hasilnya adalah teks pada elemen `<p>` akan memiliki ukuran 65 piksel, miring (italic), berwarna putih, dan memiliki jarak 150 piksel dari atas serta 200 piksel dari kiri. Hal ini akan mengubah tampilan dan posisi dari teks pada paragraf sesuai dengan pengaturan yang diberikan dalam kode CSS tersebut.

Kode dari CSS tersebut untuk elemen `<img>` adalah sebagai berikut: 
1. `margin-right: 200px;`: Mengatur jarak (margin) dari sisi kanan elemen `<img>` sebesar 200 piksel.
2. `margin-top: 50px;`: Mengatur jarak (margin) dari sisi atas elemen `<img>` sebesar 50 piksel. 
3. `border: 10px solid white;`: Menambahkan border (garis tepi) pada elemen `<img>` dengan ketebalan 10 piksel, jenis solid, dan berwarna putih. 
4. `border-radius: 1500% 1500%;`: Mengatur sudut lengkung (border radius) dari elemen `<img>` menjadi 1500% pada kedua sisi, sehingga elemen akan memiliki sudut yang sangat melengkung dan hampir bulat. 
5Dengan menggunakan CSS di atas, elemen `<img>` akan memiliki margin di sisi kanan sebesar 200 piksel, margin di sisi atas sebesar 50 piksel, border putih dengan ketebalan 10 piksel, dan sudut yang sangat melengkung sehingga hampir bulat. Ini adalah contoh pengaturan gaya (styling) untuk elemen gambar dalam halaman web.

 kode CSS tersebut untuk elemen `button` adalah sebagai berikut :
1. `Button` akan memiliki latar belakang berwarna ungu (purple).
2. `Lebar button` akan memiliki ukuran 150 piksel.
3. `Tinggi button` akan memiliki ukuran 60 piksel.
4. `Button` akan memiliki `lebar border` sebesar 2 piksel.
5. `Border button` akan memiliki gaya solid, yang berarti akan terlihat seperti garis lurus.
6. `Warna border button` akan berwarna putih (white).
7. `Teks pada button` akan memiliki warna oranye (orangered).
8. `Button` akan memiliki `margin bawah` sebesar 20 piksel.
9. `Button` akan memiliki `margin kiri` sebesar 390 piksel.
Dengan demikian, kode CSS tersebut akan menghasilkan sebuah` button`  dengan latar belakang ungu, berukuran 150 piksel lebar dan 60 piksel tinggi, serta memiliki border berukuran 2 piksel dengan gaya garis lurus. Border button akan berwarna putih dan teks pada button akan berwarna oranye. Button juga akan memiliki margin bawah sebesar 20 piksel dan margin kiri sebesar 390 piksel.
# Box-Model
## Border-width
### penjelasan 
`border-width` adalah properti dalam CSS yang digunakan untuk menentukan lebar dari border (garis tepi) sebuah elemen HTML. Properti ini memungkinkan Anda untuk mengatur lebar dari border pada keempat sisi (atas, kanan, bawah, kiri) secara terpisah atau secara bersamaan.
Berikut adalah beberapa cara untuk menggunakan `border-width`:
1. Mengatur lebar border untuk semua sisi secara bersamaan:
`div {   border-width: 2px; }`
Dalam contoh di atas, semua sisi dari elemen `<div>` akan memiliki border dengan lebar 2 piksel.
2. Mengatur lebar border untuk sisi-sisi tertentu secara terpisah:
`div {   border-width: 2px 1px 3px 4px; }`
Dalam contoh di atas, urutan nilai yang diberikan adalah untuk sisi atas, kanan, bawah, dan kiri secara berurutan. Jadi, lebar border untuk sisi atas adalah 2 piksel, kanan 1 piksel, bawah 3 piksel, dan kiri 4 piksel.
3. Mengatur lebar border untuk sisi tertentu saja:
`div {   border-top-width: 2px;   border-bottom-width: 4px; }`