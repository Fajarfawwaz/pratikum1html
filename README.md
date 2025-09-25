## — Praktikum 1 HTML Dasar

* Nama : Fajar Fawwaz Atallah
* NIM : 312410357
* Kelas : TI.24.A.4
* Mata Kuliah : 8Pemograman Web 1
* Praktikum 1 : HTML Dasar
* Dosen : Agung Nugroho, S.Kom., M.Kom.

---

## *Tugas nya*
<img width="778" height="244" alt="image" src="https://github.com/user-attachments/assets/12f728fa-8757-4347-a6e9-46c2ce922c17" />


### *Langkah-langkah Praktikum*

#### 1. Membuat Struktur Dasar HTML

Pertama membuat file lab1_tag_dasar.html berisi struktur dasar HTML.


```

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="author" content="Mahasiswa UPB">
    <meta name="keywords" content="HTML, Pemrograman Web, UPB">
    <meta name="description" content="Praktikum HTML Dasar">
    <title>Praktikum 1 - HTML Dasar</title>
</head>
<body>

   <!-- Link Navigasi -->
    <nav>
        <a href="lab1_tag_dasar.html" target="_self">Dasar HTML</a> |
        <a href="lab1_halaman2.html" target="_self">Halaman 2</a> |
        <a href="http://www.google.com" target="_blank">Google</a>
    </nav>
    <hr>

    <!-- Judul Utama -->
    <h1>Belajar Dasar HTML</h1>

    <!-- Paragraf Pertama -->
    <!-- Ini adalah paragraf pertama -->
    <p alig="center">
        Nama saya Fajar Fawwaz Atallah Dengan <b>NIM 312410357</b>, Dari Kelas TI.24.A4, pada matakuliah <i>Pemrograman Web</i> 
        di Prodi <mark> Teknik Informatika Universitas Pelita Bangsa. </mark>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML
    </p>

    <!-- Judul Paragraf Kedua -->
    <h2>Paragraf pada HTML</h2>

    <!-- Paragraf Kedua -->
    <!-- Ini adalah paragraf kedua -->
    <p alig="right">
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat 
        yang saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar HTML.<br>
        Contoh penggunaan <u>line break</u> dengan tag <code>&lt;br&gt;</code>.
    </p>

    <!-- Sub Judul Gambar -->
    <h3>Universitas Pelita Bangsa</h3>
    <img src="https://bloguna.com/wp-content/uploads/2025/08/Logo-Universitas-Pelita-Bangsa-UPB-Format-PNG-CDR-EPS-SVG-PDF-AI-768x584.png" width="200" alt="Logo UPB" title="Logo Universitas Pelita Bangsa">

</body>
</html>

```

<img width="3466" height="2154" alt="HTML 1" src="https://github.com/user-attachments/assets/c4cda131-3d19-4661-9346-b6852a5defea" />




#### 2. Membuat Paragraf

Menambahkan tag
```
 <p>
```
untuk membuat paragraf.


    <p alig="center">
        Nama saya Fajar Fawwaz Atallah Dengan <b>NIM 312410357</b>, Dari Kelas TI.24.A4, pada matakuliah <i>Pemrograman Web</i> 
        di Prodi <mark> Teknik Informatika Universitas Pelita Bangsa. </mark>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML
    </p>

    <!-- Judul Paragraf Kedua -->
    <h2>Paragraf pada HTML</h2>

    <!-- Paragraf Kedua -->
    <!-- Ini adalah paragraf kedua -->
    <p alig="right">
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat 
        yang saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar HTML.<br>
        Contoh penggunaan <u>line break</u> dengan tag <code>&lt;br&gt;</code>.
    </p>


<img width="1490" height="856" alt="Screenshot 2025-09-25 090410" src="https://github.com/user-attachments/assets/f41daeae-267a-4c4a-bcd1-ce8f1fee18e1" />



---

#### 3. Menambahkan Judul (Heading)

Menambahkan heading
```
<h1> dan <h2>
```
sebelum paragraf.


```
 <!-- Judul Utama -->
    <h1>Belajar Dasar HTML</h1>

    <!-- Paragraf Pertama -->
    <!-- Ini adalah paragraf pertama -->
    <p alig="center">
        Nama saya Fajar Fawwaz Atallah Dengan <b>NIM 312410357</b>, Dari Kelas TI.24.A4, pada matakuliah <i>Pemrograman Web</i> 
        di Prodi <mark> Teknik Informatika Universitas Pelita Bangsa. </mark>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML
    </p>

```

<img width="2264" height="748" alt="HTML 2" src="https://github.com/user-attachments/assets/721085ae-8bb0-4a61-9b62-562842f29568" />



---

#### 4. Memformat Teks

Menggunakan tag
```
<b>, <i>, <sub>, <sup>
```
untuk memformat teks.

```
 <!-- Judul Utama -->
    <h1>Belajar Dasar HTML</h1>

    <!-- Paragraf Pertama -->
    <!-- Ini adalah paragraf pertama -->
    <p alig="center">
        Nama saya Fajar Fawwaz Atallah Dengan <b>NIM 312410357</b>, Dari Kelas TI.24.A4, pada matakuliah <i>Pemrograman Web</i> 
        di Prodi <mark> Teknik Informatika Universitas Pelita Bangsa. </mark>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML
    </p>

    <!-- Judul Paragraf Kedua -->
    <h2>Paragraf pada HTML</h2>

    <!-- Paragraf Kedua -->
    <!-- Ini adalah paragraf kedua -->
    <p alig="right">
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat 
        yang saling mendukung sehingga menjadi satu kesatuan. 
        Paragraf dibuat dengan menggunakan tag dasar HTML.<br>
        Contoh penggunaan <u>line break</u> dengan tag <code>&lt;br&gt;</code>.
    </p>
```

<img width="2264" height="1166" alt="HTML 3" src="https://github.com/user-attachments/assets/db812b0a-41b1-45f6-955b-e0cec33aae7a" />



---

#### 5. Menyisipkan Gambar

Menggunakan tag
```
<img>
```
dengan atribut src, title, dan alt.

<h3>Universitas Pelita Bangsa</h3>
<img src="https://bloguna.com/wp-content/uploads/2025/08/Logo-Universitas-Pelita-Bangsa-UPB-Format-PNG-CDR-EPS-SVG-PDF-AI-768x584.png" width="200" alt="Logo UPB" title="Logo Universitas Pelita Bangsa">


📸 <img width="288" height="224" alt="image" src="https://github.com/user-attachments/assets/2dfa3283-cf3c-47e8-b494-8c92e0a989fa" />


---

#### 6. Menambahkan Hyperlink

Menambahkan navigasi link menggunakan tag <a> dengan berbagai target.

html
<nav>
    <a href="lab1_tag_dasar.html" target="_self">Dasar HTML</a> |
    <a href="lab1_halaman2.html" target="_blank">Halaman 2</a> |
    <a href="http://www.google.com" target="_top">Google</a>
</nav>


📸 <img width="318" height="99" alt="image" src="https://github.com/user-attachments/assets/698d620b-d762-4888-81b6-caa2133257c5" />


---

### *Jawaban Pertanyaan Praktikum*

<img width="760" height="258" alt="image" src="https://github.com/user-attachments/assets/8660574b-7c5d-4913-9843-9ee18fd95c32" />


1. Jika ada salah penulisan tag, HTML tetap ditampilkan tetapi hasilnya bisa berantakan atau tidak sesuai (tidak error fatal).
2. <p> membuat paragraf baru dengan spasi otomatis, sedangkan <br> hanya pindah baris.
3. alt menampilkan teks pengganti gambar (aksesibilitas), title menampilkan tooltip saat kursor diarahkan.
4. Untuk menjaga proporsional, cukup isi salah satu (width atau height), jangan keduanya dengan nilai sembarangan.
5. target="_blank" buka tab baru, _self di halaman sama, _top di jendela penuh, _parent di frame induk.

---

### *Kesimpulan*

Dalam praktikum ini saya belajar:

* Struktur dasar HTML
* Tag heading, paragraf, pemformatan teks
* Penyisipan gambar
* Penggunaan hyperlink dengan atribut target

---
