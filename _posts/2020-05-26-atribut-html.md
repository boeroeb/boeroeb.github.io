---
date: 2020-05-30 07:48:05
layout: post
title: "Tutorial HTML #4 : Atribut HTML"
subtitle: Apa itu atribut pada HTML ?
description: Atribut HTML berfungsi untuk memberikan informasi tambahan mengenai elemen HTML. Contoh atribut HTML title, href, src, width, height, alt, style, lang
image: /assets/img/uploads/atribut-html.png
optimized_image: /assets/img/uploads/atribut-html.png
category: html
tags:
  - title
  - href
  - src
  - width
  - height
  - alt
  - style
  - lang
author: berbagit
paginate: false
---

Apa itu atribut pada HTML ? Sebagai perumpamaan, mari kita anggap HTML itu seorang wanita. Pada seorang wanita, banyak sekali atribut / aksesoris tambahan yang dipakai. Contohnya gelang, anting, makeup, dan lain-lainya. Hal tersebut digunakan untuk mempercantik dirinya, begitu juga dengan HTML. Dengan menambahkan atribut pada elemen HTML akan memberikan informasi tambahan tentang elemen tersebut dan membuatnya semakin cantik. Pada HTML, atribut biasanya diletakkan pada tag awal. Untuk penulisan atribut, biasanya seperti ini `value="name"`. Dimana isi dari name selalu berada didalam tanda kutip dua/quotes.

1. 
{:toc}

Beberapa atribut sudah pernah kita singgung sedikit pada pembahasan [Dasar - dasar HTML](/dasar-html). Atribut yang akan kita bahas antara lain :

## title Atribut
`title` atribut dapat digunakan pada tag heading dan paragraf. Dengan memberikan atribut tittle, maka nilai pada title akan muncul ketika mouse digerakkan ke arah heading atau paragraf, ketika mouse tidak mengarah kesana maka title akan hilang. Atribut title ini juga dapat digunakan untuk memberikan keterangan singkat pada tulisan. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2 title="Ini adalah title">title Atribut</h2>
 <p title="Ini adalah paragraf">
  Arahkan mouse ke arah sini, maka akan keluar titlenya
 </p>
</body>
</html>
```

Jika nilai title hanya terdiri dari 1 kata, tanpa menggunakan kutip dua pun kode tetap akan berjalan, tetapi hal tersebut tidak disarankan. Karena ketika nilai title lebih dari 1 kata, maka output kode nya akan berantakan.

## href Atribut
Di pembahasan [Dasar - dasar HTML](/dasar-html), atribut `href` sudah pernah dibahas. Dimana href adalah atribut yang sering dipakai di tag a. Fungsinya yaitu meletakkan link yang akan dituju. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2>href At</h2>
 <p>Pada HTML, link ditandai dengan tag a. Sedangakn alamat yang dituju ditambahakan pada atribut href.</p>
 <a href="https://berbagit.com/">Contoh Link dan Atribut</a>
</body>
</html>
```

Jika nilai href tidak memakai kutip dua, kode akan tetap berjalan tetapi hal tersebut tidak disarankan.

## src Atribut
`src` atribut digunakan pada gambar. src atribut berfungsi untuk memberikan informasi dimana letak file gambar berada. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2>src Atribut</h2>
 <p>Pada HTML image ditandai dengan tag img, dan letak file gambarnya dengan atribut src</p>
 <img src="https://berbagit.com/assets/img/blog-image.png">
</body>
</html>
```

## width dan height Atribut
Pada HTML, image memiliki beberapa atribut. Salah satunya yaitu atribut untuk mengatur lebar dan tinggi gambar (size gambar). Atribut gambar yang digunakan adalah `width` dan `height`. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2>Size Atribut</h2>
 <p>Pada HTML, gambar mempunyai beberapa atribut, salah satunya yaitu width dan height</p>
 <img src="https://berbagit.com/assets/img/blog-image.png" width="300" height="157">
</body>
</html>
```

Secara default, nilai angka untuk width dan height adalah satuan pixel. Jadi jika lebar nya adalah 300, itu berarti 300 pixel.

## alt Atribut
`alt` atribut biasa digunakan pada gambar. Atribut alt berfungsi untuk menampilkan text jika gambar tidak muncul. Gambar tidak muncul bisa disebabkan karena file mungkin telah dihapus, atau salah dalam penulisan alamat url gambar. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2>alt Atribut</h2>
 <p>alt atribut berfungsi untuk memberikan informasi tambahan berupa text jika gambar tidak muncul.</p>
 <img src="https://berbagit.com/assets/img/abcde.png" alt="Logo">
</body>
</html>
```

## style Atribut
`style` atribut digunakan untuk mengatur tampilan pada sebuah elemen, misalnya warna, size, dan font. Untuk mempelajari style lebih dalam, nanti akan dibahas pada saat kita belajar [CSS](/css). Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2>style Atribut</h2>
 <p>style atribut digunakan untuk merubah tampilan pada sebuah elemen, misalnya warna</p>
 <p style="color:red">Ini paragraf berwarna merah</p>
</body>
</html>
```

## lang Atribut
`lang` atribut digunakan untuk mendeklarasikan bahasa yang digunakan dalam dokumen HTML tersebut sehingga memudahkan mesin pencari untuk membacanya. lang atribut diletakan di dalam tag html. Untuk bahasa indonesia dapat menggunakan lang id atau in. Untuk kode bahasa lainnya, bisa kunjungi [halaman ini](/demo/iso-bahasa.md). Contoh :

```html
<!DOCTYPE html>
<html lang="id">
</head>
<body>
 ...
</body>
</html>
```

## Kesimpulan
Meskipun atribut bisa ditulis dengan huruf besar/kapital, tetapi disarankan untuk menulis dengan huruf kecil semua, misalnya `title` lebih baik dari pada `TITLE`. Dan jangan lupa memakai tanda kutip untuk nilai atribut. Tanda kutip dua lebih baik daripada tanda kutip satu, kecuali ada special case misalnya `<p title='Motor "Amfibi" Milik Warga Jakarta'>` atau bisa dibalik `<p title="Motor 'Amfibi' Milik Warga Jakarta">`.

Hasil dari koding diatas dapat dilihat di [halaman ini](/demo/html-atribut.html). Untuk hasil maksimal, silakan Anda latihan sesuai kreatifitas Anda sendiri, misalnya membuat halaman data diri atau halaman yang lainnya. Jika sudah selesai latihan, Anda bisa lanjut ke materi selanjutnya, yaitu mengenai [Heading pada HTML](/heading-html).

Demikian tutorial tentang HTML Atribut, semoga bisa bermanfaat buat kita semua. Jangan lupa di share ya kakak biar tambah bermanfaat. Jika ada pertanyaan, silakan bertanya di kolom komentar yaaa.