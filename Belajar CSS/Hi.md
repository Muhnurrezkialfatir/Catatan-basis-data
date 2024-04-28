# Anatomi CSS

## Kode Program 
```CSS
p{
color:red;
}
```

# Hasil
![1000](aset/cssss6.png)

## Penjelasan
1. `p` merupakan selector yang dimana selector adalah sebuah penanda yang digunakan untuk memberikan tanda terhadap tag html yang ingin di modifikasi
2. `color` merupakan property yang di mana property digunakan untuk menambahkan atau mengatur ukuran teks, jenis font, warna teks, warna background, dan sebagainya
3. `red` adalah nilai dari property 


# Percobaan I
# Kode Program
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Belajar CSS 1</title>
        <style>
            p {
                color: red;
            }
        </style>
    </head>
    <body>
        <p>Welcome CSS</p>
    </body>
</html>
```

# Hasil
![](aset/cssss5.png)


# Penjelasan
1. `<!DOCTYPE html>`: Mendefinisikan jenis dokumen HTML yang digunakan, dalam hal ini HTML5.
2. `<html>`: Elemen utama yang memuat seluruh konten dokumen.
3. `<head>`: Bagian yang berisi informasi tambahan tentang dokumen, seperti judul dan link ke stylesheet eksternal.
4. `<title>`: Menentukan judul halaman web yang akan ditampilkan di tab browser.
5. `<style>`: Bagian di mana Anda dapat menambahkan aturan CSS untuk mengubah tampilan elemen HTML di halaman.
6. `p { color: red; }`: Aturan CSS yang mengubah warna teks pada semua elemen `<p>` menjadi merah.
7. `<body>`: Bagian yang berisi konten aktual halaman web, seperti teks, gambar, atau elemen lainnya.
8. `<p>Welcome CSS</p>`: Elemen paragraf dengan teks "Welcome CSS", yang akan ditampilkan dengan warna merah karena aturan CSS yang telah ditentukan sebelumnya.


# Percobaan II
## Kode Program
```css
button{
                width: 150px;
                height: 50px;
                color: white;
                font-size: 20px;
                text-align: right;
            }
```

## Color

### Before

![](aset/cssss1.png)

  

### After

![](aset/cssss3.png)

  

> [!Penjelasan] Penjelasan
> Gambar before merupakan gambar yang menunjukkan bahwa tag button nya belum di modifikasi sedangkan pada gambar after merupakan gabar yang menunjukkan bahwa tag button nya sudah di modifikasi dengan menggunakan property color   
  
## Font-size
### Before

![](aset/cssss1.png)
    
### After

![](aset/cssss2.png)

> [!NOTE] Penjelasan
> Jadi gambar before yang diatas merupakan gambar yang dimana tag button belum di modifikasi sedangkan gambar after merupakan gambar yang dimana tag button sudah di modifikasi dengan menggunakan property Font-size    
  

## Text-align

### Before

![](aset/cssss1.png)
### After

![](aset/cssss4.png)

> [!NOTE] Penjelasan
> Jadi gambar before merupakan gambar yang dimana tag button nya belum di modifikasi sedangkan gambar after merupakan gambar yang dimana tag button nya telah di modifikasi dengan menggunakan property Text-align
# Cara Pemanggilan CSS
Cara untuk memanggil css ke html ada 3 cara yaitu inline, internal, dan external.

## Inline
jadi Inline merupakan salah satu cara untuk memanggil css yaitu dengan cara memanggilnya kedalam baris yang sama dengan tag yang ingin di modifikasi contoh

### Kode Program
```HTML
<p style="color: red;">Welcome CSS</p>
```

### Hasil
![](aset/cssss5.png)

> [!NOTE] Penjelasan
> **Inline CSS**: Dalam metode ini, CSS ditulis langsung di dalam tag HTML menggunakan atribut `style`. Ini berguna ketika Anda ingin menerapkan gaya yang spesifik hanya untuk satu elemen.



## Internal

### Kode Program
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Belajar CSS 1</title>
        <style>
            p {
                color: red;
            }
        </style>
    </head>
    <body>
        <p>Welcome CSS</p>
    </body>
</html>
```


### Hasil
![](aset/cssss5.png)



> [!NOTE] Penjelasan
> **Internal CSS**: Dalam metode ini, CSS ditulis di dalam tag `<style>` di dalam elemen `<head>` dokumen HTML. Ini berguna ketika Anda memiliki beberapa halaman yang memerlukan gaya yang sama. Dengan menggunakan internal CSS, Anda dapat menetapkan gaya sekali dan akan berlaku untuk seluruh halaman tersebut


## External
### Kode Program 

Kode Program HTML yang dimana ini adalah tempat css di panggil dengan menggunakan metode external
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Belajar CSS2</title>
        <link rel="stylesheet" href="belajar css1.css">
    </head>
    <body>
        <p>Welcome CSS</p>
    </body>
</html>
```

Kode Program CSS 
```CSS
p{
	color: red;
}
```

### Hasil
![](aset/cssss5.png)

> [!NOTE] Penjelasan
> **External CSS**: Dalam metode ini, CSS ditulis dalam file terpisah dengan ekstensi `.css`, dan kemudian dihubungkan dengan dokumen HTML menggunakan tag `<link>`. Hal ini memisahkan struktur konten (HTML) dari presentasi (CSS), membuatnya lebih mudah untuk memelihara dan memperbarui gaya di seluruh situs web Anda



# Selector
## Kode Program
```CSS
p{
	color: red;
}
```


## Hasil
![1000](aset/cssss6.png)


> [!NOTE] Penjelasan
> Selector adalah aturan yang digunakan untuk memilih elemen HTML yang ingin Anda modifikasi. Selector dapat berupa elemen HTML itu sendiri, kelas, ID, atribut, atau kombinasi dari beberapa hal ini. Ketika browser merender halaman web, ia menggunakan selector CSS untuk menentukan modif yang akan diterapkan pada setiap elemen yang dipilih.



# Materi Text
## Text-align
### Kode Program
```CSS
p{
Text-align: center;
}
```

### Hasil
![1000](aset/cssss7.png)


> [!NOTE] Penjelasan
> Properti `text-align` digunakan untuk mengatur penataan teks di dalam sebuah elemen. Nilai `center` akan membuat teks berada di tengah elemen. Properti ini tidak hanya berlaku untuk teks, tapi juga untuk elemen lain seperti gambar dan tabel yang berada di dalam elemen tersebut.



## Text-decoration
### Kode Program
```CSS
p{
text-decoration: overline;
}
```


### Hasil
![](aset/cssss8.png)


> [!NOTE] Penjelasan
>Properti `text-decoration` digunakan untuk mengatur dekorasi teks seperti garis bawah, garis tengah, garis atas, dan garis tepi. Nilai `underline` digunakan untuk memberikan garis bawah pada teks. Properti ini sering digunakan untuk memberi penekanan pada teks seperti tautan (link).


## Text-transform
### Kode Program
```CSS
p{
text-transform: uppercase;
}
```

### Hasil
![](aset/cssss9.png)

> [!NOTE] Penjelasan
> Properti `text-transform` digunakan untuk mengubah tampilan teks menjadi huruf besar (uppercase), huruf kecil (lowercase), atau huruf kapital di awal setiap kata (capitalize). Dalam contoh ini, nilai `uppercase` digunakan untuk mengubah semua teks dalam elemen menjadi huruf besar.

## Text-indent

### Kode Program
```CSS
p{
text-indent: 10px;
}
```

### Hasil
![](aset/cssss10.png)


> [!NOTE] Penjelasan
Properti `text-indent` digunakan untuk menetapkan jarak (indent) dari awal baris teks ke posisi awal teks. Dalam contoh ini, nilai `50px` menetapkan jarak indent sebesar 50 piksel dari tepi kiri elemen. Jarak indent ini biasanya digunakan untuk membuat paragraf atau blok teks terlihat lebih rapi dan mudah dibaca.
> 


## Latter-spacing
### Kode Program
```CSS
p{
letter-spacing: 100px;
}
```


### Hasil
![](aset/cssss11.png)


> [!NOTE] Penjelasan
> Properti `letter-spacing` digunakan untuk mengatur jarak antara huruf dalam teks. Nilai positif akan meningkatkan jarak antar huruf, sedangkan nilai negatif akan mengurangi jaraknya. Dalam contoh ini, nilai `2px` digunakan untuk menambahkan jarak sebesar 2 piksel antar huruf dalam teks.

## Line-height

### Kode Program
```CSS
p{
line-height: 100ox;
}
```

### Hasil
![](aset/cssss12.png)


> [!NOTE] Penjelasan 
> Properti `line-height` digunakan untuk mengatur tinggi baris teks. Nilai `1.5` berarti tinggi baris adalah 1.5 kali dari tinggi defaultnya. Mengatur tinggi baris dengan nilai yang lebih besar dari 1 akan membuat teks terlihat lebih longgar, sedangkan nilai kurang dari 1 akan membuatnya lebih rapat. Ini dapat digunakan untuk meningkatkan keterbacaan teks.



## Word-spacing

### Kode Program
```CSS
p{
word-spacing: 100px;
}
```


### Hasil 
![](aset/cssss13.png)

> [!NOTE] Penjelasan
> Properti `word-spacing` digunakan untuk mengatur jarak antara kata-kata dalam teks. Nilai positif akan meningkatkan jarak antar kata, sedangkan nilai negatif akan mengurangi jaraknya. Dalam contoh ini, nilai `5px` digunakan untuk menambahkan jarak sebesar 5 piksel antar kata dalam teks.



# Materi Backgraund
## Background-image
### Kode Program
```CSS
p{
background-image: url("aset/Marsha.jpg");
}
```


### Hasil
![](aset/cssss14.png)

> [!NOTE] Penjelasan
> Properti `background-image` digunakan untuk menetapkan gambar sebagai latar belakang elemen. Dalam contoh ini, gambar diambil dari URL yang diberikan dan diatur untuk menutupi seluruh area elemen menggunakan `background-size: cover;`. Anda juga dapat menggunakan gambar lokal dengan memberikan path yang tepat.



## Background-size
### Kode Program
```CSS
body{
background-image: url("aset/marsha.jpg");
background-size: 100px;
}
```


### Hasil
![](aset/cssss14.png)


> [!NOTE] Penjelasan
> Properti `background-size` digunakan untuk mengontrol ukuran latar belakang gambar. Nilai `cover` akan membuat gambar menutupi seluruh area latar belakang elemen, tanpa distorsi proporsi, sehingga gambar bisa memotong sebagian jika perlu. Anda juga dapat menggunakan nilai `contain` untuk memastikan gambar selalu terlihat utuh di dalam area latar belakang.



## Background-reapet
### Kode Program
```CSS
body{
background-image: url("aset/Marsha.jpg");
                background-size: cover;
                background-repeat: no-repeat;
}
```


### Hasil
![](aset/cssss14.png)


> [!NOTE] Penjelasan
> Properti `background-repeat` digunakan untuk mengatur apakah gambar latar belakang akan diulang secara horizontal (`repeat-x`), vertikal (`repeat-y`), keduanya (`repeat`), atau tidak sama sekali (`no-repeat`). Dalam contoh ini, gambar diulang secara horizontal sehingga mengisi seluruh lebar elemen.



## Background-attachment
### Kode Program
```CSS
body{
                background-image: url("aset/Marsha.jpg");
                background-size: cover;
                background-repeat: no-repeat;
                background-attachment: fixed;
            }
```

### Hasil
![](aset/cssss14.png)


> [!NOTE] Penjelasan
> Properti `background-attachment` digunakan untuk mengontrol apakah gambar latar belakang akan tetap diam (`fixed`) atau akan bergulir bersamaan dengan konten (`scroll`) saat pengguna menggulir halaman. Dalam contoh ini, gambar latar belakang tetap diam bahkan saat halaman digulir.


## Background-potition
### Kode Program
```CSS
body{
                background-image: url("aset/Marsha.jpg");
                background-size: cover;
                background-repeat: no-repeat;
                background-attachment: fixed;
                background-position: -50px -50px;
            }
```

### Hasil
![](aset/cssss14.png)




# Materi Font
## Font-size
### Kode Program
```CSS
p{
font-size: 100;
}
```



###





## Font-style
### Kode Program
```CSS
p{
font-style: 
}
```



## Font-family
### Kode Program
```CSS
p{
font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
```



## Font-weight
### Kode Program
```CSS
p{
font-weight
}
```