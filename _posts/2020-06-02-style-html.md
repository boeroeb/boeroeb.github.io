---
date: 2020-06-02 13:20:41
layout: post
title: "Tutorial HTML #7 : Style di HTML"
subtitle: Dengan style atribut, elemen HTML menjadi lebih indah dan berwarna :)
description: Style atribut digunakan untuk memberikan pengaturan pada elemen HTML, misalnya background, warna text, jenis huruf, ukuran huruf, meratakan text, dll
image: /assets/img/uploads/style-html.png
optimized_image: /assets/img/uploads/style-html.png
category: html
tags:
  - style
  - background-color
  - color
  - font-family
  - font-size
  - text-align
author: berbagit
paginate: false
---

Pada pembahasan kali ini, kita akan belajar mengenai Style pada HTML. Apa sih Style pada HTML itu ? Pembahasan kali ini akan semakin menarik, karena kita akan mulai berkreasi dengan dokumen HTML yang kita buat. Setelah kita mengetahui [dasar - dasar HTML](/dasar-html), [belajar atribut](/atribut-html), [belajar heading](/heading-html), [belajar paragraf](/paragraf-html) dan lainnya, maka sekarang kita akan meningkat ke pembahasan yang lebih tinggi yaitu Style.

1. 
{:toc}

Style atribut digunakan untuk memformat atau memberikan pengaturan pada sebuah elemen atau tag HTML. Contohnya jika kita ingin memberi background halaman, memberi warna text, mengganti jenis huruf, mengganti ukuran huruf, meratakan text atau pun memberikan pengaturan lainnya. Hal tesebut dapat dilakukan dengan style atribut. Penuliasan style atribut pada HTML seperti ini : `<tagname style="property:value;">`. Tagname bisa berupa tag apa saja, misalnya tag body, paragraf, heading, atau tag lainnya. Properti adalah sebuah CSS properti, misalnya background-color. Sedangkan value adalah nilai dari properti CSS tersebut, misalnya bernilai red.

## background-color Properti
`background-color` properti digunakan untuk mendifinisikan warna belakang dari sebuah elemen HTML. Contoh background color blue, red, white, black, yellow, aqua, aquamarine dan lain-lain. Contoh :

```html
<!DOCTYPE html>
<html>
<head>
 <title>Style pada HTML</title>
</head>
<body style="background-color:aqua;">
 <h2>Ini contoh heading</h2>
 <p>Ini contoh paragraf.</p>
</body>
</html>
```

## color Properti
`color` properti digunakan untuk memberi warna text pada elemen HTML. Misal nya warna text pada heading atau paragraf. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2 style="color: red;">Ini contoh heading</h2>
 <p style="color: blue;">Ini contoh paragraf.</p>
</body>
</html>
```

## font-family Properti
`font-family` properti digunakan untuk merubah model atau jenis font pada sebuah elemen HTML. Misal nya jenis font pada heading atau paragraf. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h1 style="font-family:verdana;">Ini contoh heading</h1>
 <p style="font-family:arial;">Ini contoh paragraf.</p>
</body>
</html>
```

## font-size Properti
`font-size` properti digunakan untuk merubah ukuran huruf pada sebuah elemen HTML. Misalnya ukuran font pada heading atau paragraf. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h1 style="font-size:300%;">Ini contoh heading</h1>
 <p style="font-size:150%;">Ini contoh paragraf.</p>
</body>
</html>
```

## text-align Properti
`text-align` properti digunakan untuk mengatur perataan teks pada sebuah element HTML. Misalnya perataan pada heading atau paragraf. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h1 style="text-align:center;">Ini contoh heading</h1>
 <p style="text-align:right;">Ini contoh paragraf.</p>
</body>
</html>
```

Jika atribut style memiliki lebih dari 1 properti dan nilai, maka gunakan lah tanda `;` sebagai pemisahnya. Contoh :

```html
<!DOCTYPE html>
<html>
<head>
 <title>Style pada HTML</title>
</head>
<body style="background-color:aqua;">
 <h2 style="color: red; font-family:verdana; font-size:300%; text-align:center;">Ini contoh heading</h2>
 <p style="color: blue; font-family:arial; font-size:150%; text-align:right;">Ini contoh paragraf.</p>
</body>
</html>
```

## Kesimpulan
Dengan menggunakan style atribut, maka elemen HTML menjadi lebih berwarna dan indah :). Pembahasan lengkap Style ini akan dibahas lebih mendalam nanti di pembelajaran [CSS](/css).

Hasil dari koding pembahasan ini dapat dilihat di [link ini](/demo/html-style.html). Jangan lupa berlatih menggunakan style atribut ini, kreasikan hasil latihan Anda sebelumnya dengan menggunakan atribut style ini sehingga menjadi lebih indah dan berwarna :). Setelah selesai latihan, Anda dapat mempelajari materi selanjutnya yaitu mengenai [Text Formating pada HTML](/text-formating-html).

Semoga artikel ini bisa bermanfaat untuk kita semua. Jangan lupa klik tombol share untuk berbagi ke yang lain biar tambah bermanfaat. Jika ada yang ingin ditanyakan, silakan tinggalkan pertanyaan di kolom komentar di bawah. Terima kasih.