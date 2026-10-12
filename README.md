# Lab4Web

## Laporan Praktikum 4: CSS Layout

### 1. Persiapan Dokumen HTML & CSS Box Element
* **Penjelasan:** Langkah awal dimulai dengan membuat struktur dokumen dasar HTML pada file `lab4_box.html`. Langkah ini menambahkan tag semantic `<header>` berisi judul halaman dan tag `<section>` sebagai kontainer utama untuk pengujian box element.
* **Screenshot:**
![Langkah 1 - Persiapan Dokumen HTML](img/langkah1.png)

---

### 2. Membuat Box Element dan Mengatur Float Property
* **Penjelasan:** Menambahkan tiga buah elemen `<div>` dengan nama class `div1`, `div2`, dan `div3` di dalam tag `<section>`. Kemudian menerapkan properti CSS `float: left;` serta warna latar belakang berbeda pada tiap elemen untuk memposisikan ketiga box berjajar ke samping secara horizontal.
* **Screenshot:**
![Langkah 2 - Box Element Float](img/langkah2.png)

---

### 3. Mengatur Clearfix Element
* **Penjelasan:** Menambahkan elemen `div4` di bawah elemen float dan menerapkan properti CSS `clear: left;` serta `float: none;`. Pengaturan ini berfungsi untuk menetralkan (*clearing*) efek float dari elemen-elemen sebelumnya agar `div4` berada di baris baru secara normal.
* **Screenshot:**
![Langkah 3 - Clearfix Element](img/langkah3.png)

---

### 4. Membuat Kerangka Layout Sederhana (HTML5 Semantics)
* **Penjelasan:** Membuat struktur direktori baru bernama `lab4_layout/` yang berisi file `home.html` dan `style.css`. Kerangka web disusun menggunakan elemen semantik HTML5 seperti `<header>`, `<nav>`, `<section id="hero">`, `<section id="wrapper">`, `<section id="main">`, `<aside id="sidebar">`, dan `<footer>`.
* **Screenshot:**
![Langkah 4 - Kerangka Layout](img/langkah4.png)

---

### 5. Menerapkan Styling Header & Navigation Menu
* **Penjelasan:** Menambahkan aturan CSS Reset untuk menghilangkan margin/padding default browser, mengatur font utama menggunakan Google Fonts (Open Sans), serta merancang tata letak navigasi horizontal dengan latar warna biru, status tautan aktif (`.active`), dan efek `:hover`.
* **Screenshot:**
![Langkah 5 - Header & Navigasi](img/langkah5.png)

---

### 6. Membuat Hero Panel
* **Penjelasan:** Menambahkan bagian Hero Panel di bawah navigasi sebagai area sambutan utama (jumbotron). Komponen ini diberi latar belakang abu-abu terang, judul header, paragraf deskripsi, serta tombol Call-to-Action (CTA).
* **Screenshot:**
![Langkah 6 - Hero Panel](img/langkah6.png)

---

### 7. Mengatur Layout Main Content & Sidebar Widget
* **Penjelasan:** Membagi area layout menjadi dua kolom berdampingan menggunakan `float: left;`. Konten utama (`#main`) diberi lebar 640px, sedangkan area samping (`#sidebar`) diberi lebar 260px. Area sidebar diisi dengan widget tautan dan widget teks deskripsi.
* **Screenshot:**
![Langkah 7 - Main Content & Sidebar](img/langkah7.png)

---

### 8. Menambahkan Elemen Kartu (Grid/Box) & Artikel
* **Penjelasan:** Menambahkan tiga kolom kartu grid dengan gambar berbentuk lingkaran (`.image-circle`) beserta teks deskripsi di area main content. Selain itu, disusun artikel blog menggunakan tag `<article>` yang dilengkapi dengan gambar rata kiri dan rata kanan menggunakan CSS float.
* **Screenshot:**
![Langkah 8 - Grid Box & Artikel](img/langkah8.png)

---

### 9. Mengatur Styling Footer
* **Penjelasan:** Menerapkan style pada bagian `<footer>` di bagian paling bawah halaman web. Footer diberi warna latar belakang gelap (`#1d1d1d`), warna teks terang, serta properti `clear: both;` agar posisinya tetap konsisten berada di bawah seluruh elemen float.
* **Screenshot:**
![Langkah 9 - Styling Footer](img/langkah9.png)

---

## Pertanyaan & Tugas Praktikum

### 1. Membuat Halaman About (`about.html`)
* **Penjelasan:** Menambahkan halaman baru `about.html` dengan tata letak single-layout (satu kolom penuh) yang menyajikan deskripsi profil diri, portofolio, serta daftar keahlian/skill yang dimiliki.
* **Screenshot:**
![Tugas 1 - Halaman About](img/tugas1_about.png)

---

### 2. Membuat Halaman Contact (`kontak.html`)
* **Penjelasan:** Membuat halaman `kontak.html` yang dilengkapi dengan formulir isian interaktif, terdiri dari input nama, email, subjek, pesan (*textarea*), serta tombol kirim pesan.
* **Screenshot:**
![Tugas 2 - Halaman Contact](img/tugas2_contact.png)
