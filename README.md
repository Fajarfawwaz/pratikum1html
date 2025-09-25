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

html
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

📸 <img width="3466" height="2154" alt="code1" src="https://github.com/user-attachments/assets/5a9f427b-af77-4ac4-ac3f-0f9da544dd9f" />



#### 2. Membuat Paragraf

Menambahkan tag <p> untuk membuat paragraf.

html
    <p alig="center">
        Nama saya ZAENAL MAULANA RIZKI dengan <b> NIM 312410332 </b> dari <b> KELAS T.24.A.4</b> Sekarang saya sedang belajar HTML dasar </b> pada matakuliah <i>Pemrograman Web</i> 
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


📸 <img width="1919" height="176" alt="image" src="https://github.com/user-attachments/assets/cbec2846-ac75-4f9c-83ac-46c51c13420e" />


---

#### 3. Menambahkan Judul (Heading)

Menambahkan heading <h1> dan <h2> sebelum paragraf.

html
    <!-- Judul Utama -->
    <h1>Belajar Dasar HTML</h1>

    <!-- Paragraf Pertama -->
    <!-- Ini adalah paragraf pertama -->
    <p alig="center">
        Nama saya ZAENAL MAULANA RIZKI dengan <b> NIM 312410332 </b> dari <b> KELAS T.24.A.4</b> Sekarang saya sedang belajar HTML dasar </b> pada matakuliah <i>Pemrograman Web</i> 
        di Prodi <mark> Teknik Informatika Universitas Pelita Bangsa. </mark>
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML
    </p>

    <!-- Judul Paragraf Kedua -->
    <h2>Paragraf pada HTML</h2>


📸 <img width="3034" height="824" alt="code2" src="https://github.com/user-attachments/assets/b60d47ca-8950-425e-9eac-f173bdfba89f" />


---

#### 4. Memformat Teks

Menggunakan tag <b>, <i>, <sub>, <sup> untuk memformat teks.

html
<!-- Judul Utama -->
    <h1>Belajar Dasar HTML</h1>

    <!-- Paragraf Pertama -->
    <!-- Ini adalah paragraf pertama -->
    <p alig="center">
        Nama saya ZAENAL MAULANA RIZKI dengan <b> NIM 312410332 </b> dari <b> KELAS T.24.A.4</b> Sekarang saya sedang belajar HTML dasar </b> pada matakuliah <i>Pemrograman Web</i> 
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


📸 <img width="1919" height="240" alt="image" src="https://github.com/user-attachments/assets/e8ca1033-c41a-4248-9893-d23e88c9ecd2" />


---

#### 5. Menyisipkan Gambar

Menggunakan tag <img> dengan atribut src, title, dan alt.

html
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
