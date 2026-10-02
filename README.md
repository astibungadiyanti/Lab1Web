# Praktikum 1 - HTML Dasar

## Deskripsi

Praktikum ini mempelajari dasar-dasar HTML untuk membuat halaman web sederhana, mulai dari struktur HTML, heading, paragraf, format teks, gambar, hyperlink, list, hingga komentar.

## Tujuan

1. Memahami struktur dasar HTML.
2. Memahami penggunaan tag dan atribut HTML.
3. Membuat halaman web sederhana menggunakan HTML.

## Tools

* Visual Studio Code
* Web Browser
* GitHub

## Screenshot Hasil Praktikum

Screenshot hasil praktikum:

![Screenshot Praktikum](Screenshot/hasil.jpg.png)

## Struktur Folder

```text
Lab1Web/
├── index.html
├── halaman2.html
├── images/
│   └── profil.jpg
└── README.md
```

## Langkah Praktikum

### 1. Struktur Dasar HTML

Membuat file `index.html` dengan struktur dasar:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Halaman Web</title>
</head>
<body>

</body>
</html>
```

### 2. Heading dan Paragraf

Menggunakan tag heading `<h1>` sampai `<h6>` dan paragraf `<p>`.

```html
<h1>Judul Utama</h1>
<p>Ini adalah paragraf.</p>
```

### 3. Format Teks

Menggunakan beberapa tag format teks seperti `<b>`, `<strong>`, `<i>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, dan `<sup>`.

### 4. Gambar

Menambahkan gambar menggunakan tag `<img>`.

```html
<img src="images/profil.jpg" alt="Foto Profil">
```

### 5. Ukuran Gambar

Mengatur ukuran gambar menggunakan atribut `width` dan `height`.

```html
<img src="images/profil.jpg" width="300" height="200" alt="Foto Profil">
```

### 6. Hyperlink

Membuat link ke halaman lain dan website eksternal.

```html
<a href="halaman2.html">Halaman 2</a>
<a href="https://www.google.com">Google</a>
```

### 7. List

Membuat unordered list menggunakan `<ul>` dan ordered list menggunakan `<ol>`.

```html
<ul>
    <li>Informatika</li>
    <li>Sistem Informasi</li>
</ul>

<ol>
    <li>Belajar HTML</li>
    <li>Belajar CSS</li>
</ol>
```

### 8. Komentar

Membuat komentar pada kode HTML menggunakan:

```html
<!-- Ini adalah komentar -->
```

### 9. Menggabungkan Elemen

Menggabungkan seluruh elemen HTML menjadi sebuah halaman profil mahasiswa yang berisi heading, paragraf, gambar, hyperlink, list, dan komentar.

## Validasi

Kode HTML dapat divalidasi menggunakan **W3C Markup Validation Service**.

## Tugas

Repository dibuat dengan nama:
Lab1Web


Setelah seluruh praktikum selesai, lakukan commit ke GitHub dan kumpulkan URL repository.

## Kesimpulan

Praktikum ini mempelajari dasar-dasar HTML dan penggunaannya untuk membuat halaman web sederhana.


10 Soal
1. Apa fungsi deklarasi !DOCTYPE html pada dokumen HTML?
2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?
3. Apa perbedaan p dengan br? Jelaskan penggunaannya.
4. Apa fungsi atribut href pada tag a?
5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?
6. Apa fungsi atribut src dan alt pada tag img?
7. Apa perbedaan penggunaan ul dan ol?
8. Apa yang terjadi jika path gambar pada atribut src salah?
9. Mengapa struktur heading h1 sampai h6 perlu digunakan secara terstruktur?
10. Apa fungsi komentar !-- ... -- dalam kode HTML?
    
Jawaban
1. <!DOCTYPE html> berfungsi untuk memberi tahu browser bahwa dokumen menggunakan HTML5.
2. Tag adalah penanda HTML, elemen adalah keseluruhan bagian HTML, sedangkan atribut adalah informasi tambahan pada sebuah tag.
3. <br> digunakan untuk membuat baris baru, sedangkan <p> digunakan untuk membuat paragraf.
4. Atribut href berfungsi menentukan alamat atau tujuan dari hyperlink.
5. Hyperlink internal mengarah ke halaman dalam website yang sama, sedangkan hyperlink eksternal mengarah ke website yang berbeda.
6. src berfungsi menentukan lokasi gambar, sedangkan alt berfungsi memberikan teks alternatif jika gambar tidak dapat ditampilkan.
7. <ul> digunakan untuk membuat daftar tidak berurutan (bullet), sedangkan <ol> digunakan untuk membuat daftar berurutan (angka).
8. Jika path gambar pada src salah, gambar tidak akan ditampilkan karena browser tidak menemukan file tersebut.
9. Heading <h1> sampai <h6> perlu digunakan secara terstruktur agar hierarki dan susunan informasi pada halaman web menjadi jelas dan mudah dipahami.
10. Komentar <!-- ... --> berfungsi memberikan catatan atau penjelasan pada kode HTML dan tidak ditampilkan di halaman web.
