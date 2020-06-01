---
date: 2020-06-01 01:49:58
layout: post
title: "Tutorial HTML #5 : Heading di HTML"
subtitle: Pernahkah anda melihat judul (heading) pada media cetak ?
description: Heading adalah judul. Heading dibagi menjadi 6. Heading 1 adalah Heading yang paling penting, dan Heading 6 adalah Heading yang kurang begitu penting.
image: /assets/img/uploads/heading-html.png
optimized_image: /assets/img/uploads/heading-html.png
category: html
tags:
  - head
  - hr
  - br
  - inspect-element
  - view-source
author:
paginate: false
---

Pada pembahasan kali ini, kita akan fokus membahas tentang Heading di HTML. Apa sih Heading itu ? Ya, dari artinya kita sudah bisa menebak. Head dalam bahasa inggris berarti kepala. Dalam HTML, Heading bisa diartikan sebagai judul. Karena kita bekerja dengan dokumen, Heading itu sangat penting. Kita harus bisa membuat kerangka dokumen yang akan kita buat dengan bantuan Heading. Untuk bagian yang paling penting, dapat dijadikan judul atau Heading 1. Kemudian untuk bagian penting lainnya bisa dijadikan sub judul atau Heading 2 sampai Heading 6 sesuai tingkat kepentingannya. Dengan memberikan Heading maka huruf akan menjadi lebih tebal atau lebih besar dari biasanya.

1. 
{:toc}

## Tag Heading
Heading merupakan salah satu tag dalam HTML. Seperti sudah dijelaskan sebelumnya, bahwa dalam HTML Heading dibagi menjadi 6 tingkatan. Heading 1 merupakan Heading yang paling penting, dan Heading 6 adalah Heading yang paling terakhir yang kurang begitu penting. Pada HTML, heading ditulis dengan tag `<h1>` sampai `<h6>`. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h1>Heading 1</h1>
 <h2>Heading 2</h2>
 <h3>Heading 3</h3>
 <h4>Heading 4</h4>
 <h5>Heading 5</h5>
 <h6>Heading 6</h6>
</body>
</html>
```

## Pentingnya Heading
Dengan Heading, maka browser akan menambahkan spasi di sebelum dan sesudah Heading. Heading ini sangat penting, karena mesin pencari seperti google akan meng-index atau membaca website yang kita buat berdasarkan struktur Heading dan konten yang kita buat. Pembaca website juga biasanya melihat judul-judul nya terlebih dahulu atau heading nya terlebih dahulu. Penggunaan Heading 1 biasanya hanya sekali saja dalam 1 halaman web, sedangkan Heading 2-6 boleh berkali-kali digunakan. Jika kita ingin membuat huruf yang tebal atau besar saja, jangan menggunakan Heading tetapi gunakanlah style atau CSS.

## Heading yang lebih besar
Setiap Heading mempunyai ukuran default masing-masing. Bagaimana kalau kita menginginkan Heading yang lebih besar atau mungkin lebih kecil dari ukuran default. Untuk mengatasi hal itu, kita bisa menggunakan bantuan dari atribut `style` dan properti CSS `font-size`. Contohnya seperti ini :

```html
<!DOCTYPE html>
<html>
<body>
 <h1 style="font-size:60px;">Mengganti ukuran Heading</h1>
 <p>Kamu dapat mengganti ukuran Heading dengan menggunakan atribut style dan properti CSS font-size</p>
</body>
</html>
```

## head Tag
`<head>` tag pada HTML berfungsi untuk menampung metadata. Metadata adalah data yang berhubungan dengan HTML, namun tidak ditampilkan pada browser. Tag `<head>` diletakkan diantara tag `<html>` dan `<body>`. Tag head diawali dengan `<head>` dan diakhir dengan `</head>`. Selain title dan meta data, Javascript dan CSS pun bisa diletakkan di dalam tag head ini. Contoh :

```html
<!DOCTYPE html>
<html>
<head>
 <title>Tag Head</title>
 <meta charset="UTF-8">
</head>
<body>
 <p>Tag head mengandung meta data.</p>
 <p>Meta data adalah data tentang documen HTML.</p>
</body>
</html>
```

Charset atau kepanjangan dari Universal Character Set adalah kumpulan dari beberapa jenis pengkodean karakter, seperti symbol, huruf, angka, dan lain-lain. Saat ini pengkodean UTF-8 telah menjadi standarisasi untuk pengkodean, seperti dalam bahasa pemrograman, API, software, maupun sistem operasi. Dengan memberikan charset UTF-8 pada file HTML, berarti halaman tersebut telah memberi informasi terhadap browser dan search engine untuk melakukan pengkodean karakter sesuai ketentuan UTF-8.

## hr Tag
`<hr>` tag merupakan tag yang tidak mempunyai nilai, sama seperti tag `<br>`. Tag ini akan menghasilkan garis horizontal untuk memisahkan konten pada HTML. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2>Ini heading 2</h2>
 <p>Ini adalah paragraf.</p>
 <hr>
 <h3>Ini heading 3</h3>
 <p>Ini adalah paragraf lainnya.</p>
 <hr>
 <h4>Ini heading 4</h4>
 <p>Ini adalah paragraf lainnya.</p>
</body>
</html>
```

## Melihat source code HTML
Bagaimana cara kita melihat source code HTML dari halaman web yang kita lihat ? Mungkin karena website tersebut sangat bagus sehingga membuat kita menjadi penasaran untuk melihat koding nya atau hanya sekedar mencari informasi dari tampilan koding nya. Ada 2 cara untuk mengetahui source code HTML pada sebuah website, yaitu :

### View Source
Cara pertama yaitu dengan cara mengklik kanan pada halaman website, lalu pilih View Page Source (pada Google Chrome) atau View Source (pada Microsoft Edge) atau sesuatu yang mirip jika pada browser lain, maka nanti akan terlihat source code dari halaman web tersebut.

### Inspect Element
Cara kedua yaitu dengan cara mengklik kanan pada halaman website, lalu pilih Inspect atau Inspect Element, maka nanti akan terlihat elemen apa saja yang menyusun website tersebut dan HTML serta CSS nya pun akan terlihat. Kita juga dapat mengedit HTML dan CSS nya secara langsung disana.

## Kesimpulan
Demikian pembahasan tentang Heading. Dimana heading itu sangat bermanfaat untuk menampilkan struktur konten yang kita buat, baik kepada pembaca maupun kepada mesin mencari.

Hasil dari koding pembahasan ini dapat dilihat di [link ini](/demo/html-heading.html). Jangan lupa berlatih apa yang sudah dipelajari di pembahasan ini, sebagai latihan Anda dapat membuat sebuah artikel bebas dimana di dalam artrikel tersebut terdapat heading minimal heading h1 dan h2, paragraf dan elemen lain yang sudah kalian pelajari di pembahasan sebelumnya. Jika sudah selesai latihan, kalian dapat lanjut ke materi selanjutnya yaitu mengenai [Paragraf pada HTML](/paragraf-html). Semoga bermanfaat dan jangan lupa berbagi kembali dengan cara meng-klik tombol share dibawah ini. Terima kasih.