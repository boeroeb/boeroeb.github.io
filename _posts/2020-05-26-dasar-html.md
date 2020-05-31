---
date: 2020-05-29 07:41:17
layout: post
title: "Tutorial HTML #3 : HTML Dasar"
subtitle: Apa itu HTML ? HTML adalah kepanjangan dari Hyper Text Markup Language
description: Dasar - dasar HTML yaitu mempelajari susunan dokumen html, heading, paragraf, link, image, button dan list. Setelah itu membuat dokumen html sederhana
image: /assets/img/uploads/html-dasar.png
optimized_image: /assets/img/uploads/html-dasar.png
category: html
tags:
  - doctype
  - heading
  - paragraf
  - link
  - image
  - button
  - list
  - br
author:
paginate: false
---

Apa itu HTML ? HTML adalah kepanjangan dari Hyper Text Markup Language. Dokumen HTML adalah file teks murni yang dapat dibuat dengen text editor apapun. Dokumen HTML inilah yang kita akses sehari-hari melalui web browser seperti Google Chrome, Mozilla Firefox dan lainnya kemudian akan menampilkan informasi sesuai dengan isi dokumen HTML nya.

1. 
{:toc}

Untuk membuat dokumen HTML kita membutuhkan [text editor](/text-editor), bisa menggunakan notepad bawaan Windows maupun text editor lainnya seperti Notepad++, Sublime Text dan lainnya. Pada contoh di website ini saya menggunakan Sublime Text. Sama seperti halnya notepad, Sublime Text adalah salah satu software text editor yang dapat digunakan untuk menulis kode-kode pemrograman namun memiliki beberapa fitur yang lebih banyak, sehingga memudahkan kita untuk menulis blok-blok kode yang akan kita kerjakan.

Untuk belajar HTML dan membuat halaman web yang menarik, kita harus mengetahui dahulu konsep dasar HTML. Berikut ini dasar - dasar HTML yang perlu dipelajari terlebih dahulu :

## Document HTML
Semua dokumen HTML selalu dideklarasikan diawal dengan `<!DOCTYPE html>`. Ini menandakan bahwa dokumen ini bertipe HTML. Dokumen HTML itu terdiri dari elemen-elemen atau tag-tag yang disatukan sehingga menjadi halaman yang utuh. Setelah dokumen HTML dideklarasikan, lalu dimulai dengan elemen atau tag `<html>` dan diakhiri dengan `</html>` yang merupakan root/akar dari dokumen HTML. Isi dari dokumen HTML yang akan tampil atau terlihat di halaman website berada diantara tag `<body>` dan `</body>`. Dengan elemen atau tag yang sudah disebutkan itu, maka dokumen HTML sudah bisa dilihat di browser. Namun untuk mempercantik, kita dapat menambahkan judul pada browser. Jika ingin menambah judul pada browser maka kita perlu menambahkan tag `<head>` dan `</head>`. Lalu di tag head ditambahkan tag `<title>` dan `</title>`. Tag head merupakan tag yang berisi meta description yaitu penjelasan singkat mengenai isi dari sebuah halaman web. Sehingga tampilan kode secara keseluruhan seperti ini :

```html
<!DOCTYPE html>
<html>
<head>
    <title>Ini contoh Judul</title>
</head>
<body>
    <h1>Ini contoh Heading</h1>
    <p>Ini contoh Paragraf.</p>
</body>
</html>
```

Jika kode tersebut disimpan misal dengan nama contoh.html, lalu dibuka di browser maka akan muncul tulisan seperti ini :
Ini contoh Heading (akan tampil dengan ukuran huruf yang lebih besar)
Ini contoh Paragraf (akan tampil dengan ukuran huruf normal)

Untuk memudahkan dalam membaca kode program, maka penulisan tag yang berada didalam tag ditulis menjorok kedalam dengan menekan tombol TAB pada keyboard.

## Heading pada HTML
Teks dalam dokumen seperti dalam majalah, koran atau apapun umumnya mempunyai judul. Pada dokumen HTML, judul itu disebut dengan Heading. Heading pada HTML akan menampilkan huruf yang lebih besar dari yang lainnya atau seperti huruf ditebalkan. Sehingga akan terlihat lebih tebal dan besar dari huruf normal.

Ada 6 tingkat Heading dalam HTML, dinomori dari nomor 1 sampai 6. Nomor 1 merupakan Heading terbesar (judul utama), dan nomor 6 adalah Heading terkecil (sub judul). Untuk Heading 1 ditandai dengan tag `<h1>` dan diakhir dengan `</h1>` dan seterusnya sampai Heading 6 `<h6>` dan diakhir dengan `</h6>`. Contoh lengkapnya seperti ini :

```html
<!DOCTYPE html>
<html>
<body>
    <h1>Ini contoh Heading 1</h1>
    <h2>Ini contoh Heading 2</h2>
    <h3>Ini contoh Heading 3</h3>
    <h4>Ini contoh Heading 4</h4>
    <h5>Ini contoh Heading 5</h5>
    <h6>Ini contoh Heading 6</h6>
</body>
</html>
```

## Paragraf pada HTML
Semua pasti sudah mengetahui apa itu paragraf. Dalam pelajaran bahasa Indonesia, paragraf adalah sekumpulan kalimat yang saling berkaitan antara kalimat yang satu dengan kalimat yang lain. Informasi yang disajikan dalam sebuah tulisan harus mengikuti kaidah-kaidah dalam penulisan. Misalnya kita sering mendengar sewaktu sekolah bahwa pikiran utama disimpan dalam satu paragraf. Dalam HTML, paragraf ditandai dengan tag `<p>` dan diakhir dengan `</p>`. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
    <p>Ini contoh paragraf.</p>
    <p>Ini contoh paragraf lainnya.</p>
</body>
</html>
```

## Link pada HTML
Link atau Hyperlink merupakan kelebihan utama dari dokumen HTML. Dengan memberikan link pada text atau gambar, kita dapat menuju dokumen atau bagian lainnya dalam suatu dokumen yang kita inginkan. Hampir setiap dokumen HTML memiliki link. Pada HTML, link ditandai dengan tag `<a>` dan diakhir dengan `</a>`. Biasanya link selalu diikuti dengan [atribut](/atribut-html) `href`. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
    <h2>Link Pada HTML</h2>
    <p>Pada HTML, link ditandai dengan tag a :</p>
    <a href="https://berbagit.com/">Ini adalah contoh link</a>
</body>
</html>
```

href merupakan kepanjangn dari Hypertext REFerence, yaitu suatu link yang akan kita tuju. 

## Image pada HTML
Umumnya website dilengkapi dengan gambar-gambar untuk membuat orang tertarik agar melihat dan membaca isi yang ada dalam suatu website. Oleh sebab itu gambar merupakan daya tarik penting bagi pengunjung yang berkunjung pada suatu halaman website. Pada HTML, gambar ditandai dengan tag `<img>` dan biasanya selalu diikuti dengan atribut `src, alt, width dan height`. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
    <h2>Gambar Pada HTML</h2>
    <p>Gambar Pada HTML ditandai dengan tag img.</p>
    <img src="https://berbagit.com/assets/img/blog-image.png" alt="Logo Berbagit" width="300" height="157">
</body>
</html>
```

src merupakan tempat file berada (source file) atau alamat file gambar disimpan. alt merupakan alternative text jika file gambar salah atau tidak tersedia, sehingga yang ditampilkan bukan gambar melainkan text alternatif. Sedangkan width merupakan lebar gambar dan height adalah tinggi gambarnya.

## Button pada HTML
Pada HTML tombol button biasanya digunakan untuk mengirim form/formulir dengan bantuan JavaScript atau PHP. Bisa juga digunakan untuk keperluan lain seperti menampilkan pesan ketika button diklik. Pada HTML, button ditandai dengan tag `<button>` dan diakhiri dengan `</button>`. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
    <h2>Button Pada HTML</h2>
    <p>Button Pada HTML ditandai dengan tag button</p>
    <button>Klik Button</button>
</body>
</html>
```

## List pada HTML
List biasanya digunakan untuk menguraikan daftar sesuatu. Misalnya untuk menguraikan jenis-jenis kendaraan, ada mobil, motor, sepeda, becak, pesawat dan lain-lain. Pada HTML, terdapat 2 macam list yaitu :

### Ordered List
Ordered list adalah list yang setiap elemennya diberi nomor, oleh karena itu disebut juga numbered list. Ordered list ditandai dengan tag `<ol>` dan diakhiri dengan `</ol>`. Kemudian untuk perincian listnya menggunakan tag `<li>` dan diakhiri dengan `</li>`.

### Unordered List
Unordered list adalah list yang setiap elemennya tidak diberi nomor tetapi ditandai dengan tanda bulat, oleh karena itu disebut juga bullet list. Ordered list ditandai dengan tag `<ul>` dan diakhiri dengan `</ul>`. Kemudian untuk perincian listnya menggunakan tag `<li>` dan diakhiri dengan `</li>`.

Contoh list pada HTML :

```html
<!DOCTYPE html>
<html>
<body>
    <h2>Contoh Ordered List. Jenis-jenis minuman :</h2>
    <ol>
      <li>Coffee</li>
      <li>Tea</li>
      <li>Milk</li>
    </ol>
    <h2>Contoh Unordered List. Jenis-jenis minuman :</h2>
    <ul>
      <li>Coffee</li>
      <li>Tea</li>
      <li>Milk</li>
    </ul>
</body>
</html>
```

Selain elemen atau tag diatas, ada juga tag `<br>`, ini untuk membuat break line yaitu mirip seperti paragraf. Tag br tidak memiliki tag penutup sehingga bisa ditulis `<br>` saja atau `<br />` saja. Yang perlu diingat adalah bahwa hampir semua tag memiliki tag penutup, jadi jangan lupa untuk memberikan tag penutup, kecuali tag br. Meskipun terkadang tanpa tag penutup pun bisa berhasil, tapi hal seperti ini tidak disarankan. Dan perlu diingat, bahwa tag HTML tidak bersifat case sensitif, sehingga bisa ditulis dengan huruf besar maupun huruf kecil, namun disarankan ditulis dengan huruf kecil.

## Kesimpulan
Dengan dasar-dasar HTML diatas, kita sudah bisa membuat halaman website yang sederhana. Setelah mengetahui dasar-dasar HTML, coba sekarang Anda latihan praktek membuat dokumen html sederhana dengan mengkombinasikan satu atau beberapa dari tag-tag diatas. Karena mengerti teori tanpa diikuti praktek hasil yang didapat kurang sempurna. Jika sudah selesai latihan, Anda dapat lanjut ke materi selanjutnya yaitu mengenai [Atribut pada HTML](/atribut-html). Semoga materi ini bisa bermanfaat untuk kita semua. Jika ada pertanyaan, silakan sampaikan di kolom komentar. Terima kasih.