---
date: 2020-06-03 13:50:26
layout: post
title: "Tutorial HTML #9 : Quotation dan Citation di HTML"
subtitle: Belajar kutipan pada HTML.
description: Quotation dan Citation pada HTML bisa berupa tag short quote / q, blockquote, abbreviation / abbr, address, cite dan Bi-Directional Override atau bdo.
image: /assets/img/uploads/quote-html.png
optimized_image: /assets/img/uploads/quote-html.png
category: html
tags:
  - quote
  - abbr
  - address
  - cite
  - bdo
author: berbagit
paginate: false
---

Apa itu Quotation ? Pada sebuah dokumen HTML, terkadang kita menemukan Quotation yaitu kutipan pendek atau kutipan panjang. Nah kali ini kita akan mempelajari jenis-jenis Quotation tersebut. Mari sama-sama kita simak penjelasan di bawah ini.

1. 
{:toc}

## Short Quote Tag
Untuk menandai kutipan pendek, kita dapat menggunakan tag `<q>` dan diakhiri dengan tag `</q>`. Tag Short Quote akan memberikan tanda kutip dua pada teks yang kita berikan tag ini. Tag q ini tidak melakukan sesuatu yang khusus, tetapi dengan kita telah mendifinisikan sebagai kutipan, maka kita dapat mengaturnya nanti dengan menggunakan CSS. Contoh kutipan dengan tag q :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Tag q akan memberikan tanda kutup dua, pada teks yang kita berikan tag. Contoh :</p>
 <p>Tujuan kita belajar HTML adalah: <q>Agar kita dapat mengetahui tag dan atribut HTML serta dapat membuat website sesuai dengan ketentuan yang berlaku.</q></p>
</body>
</html>
```

## Blockquote Tag
Tag Blockquote ditandai dengan tag `<blockquote>` dan diakhiri dengan tag `</blockquote>`. Tag Blockquote biasanya akan membuat tulisan maju kedepan / indent. Dengan tag Blockquote, maka sebagian teks yang dikutip akan menjadi suatu blok tesendiri. Contoh kutipan panjang dengan blockquote :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Dengan tag Blockquote, sebagian teks yang dikutip akan menjadi suatu blok tesendiri. Contoh :</p>
 <blockquote cite="https://www.alodokter.com/virus-corona">
 Virus Corona atau severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) adalah virus yang menyerang sistem pernapasan. Penyakit karena infeksi virus ini disebut COVID-19. Virus Corona bisa menyebabkan gangguan pada sistem pernapasan, pneumonia akut, sampai kematian.
 </blockquote>
</body>
</html>
```

Atribut `cite` berfungsi untuk mendefinisikan sumber dari quote yang kita ambil. Nilai pada atribut cite tidak akan muncul di brower, tetapi itu dapat berguna untuk search engine untuk mendapatkan informasi lebih mengenai quote tersebut.

## Abbreviation Tag
Tag Abbreviation ditandai dengan tag `<abbr>` dan diakhiri dengan tag `</abbr>`. Pada sebuah dokumen HTML terkadang kita menuliskan suatu istilah yang kita gunakan dan dinyatakan dengan singkatan/akronim saja. Tag abbr ini dapat digunakan untuk menyimpan data kepanjangan dari singkatan yang ditampilkan dalam dokumen tersebut dengan menggunkan bantuan atribut `title`. Dengan menggunkan tag abbr, maka pada saat mouse pointer kita berada di atas singkatan tersebut, kepanjangan dari singkatan tersebut akan ditampilkan mengambang diatasnya. Tag ini akan sangat berguna karena dapat memberi informasi tambahan pada browser dan search engine. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Tag abbreviations akan memberikan informasi tambahan pada browser dan search engine. Contoh :</p>
 <p>Negara <abbr title="Republik Indonesia">RI</abbr> merdeka pada tahun 1945.</p>
</body>
</html>
```

## Address Tag
Tag Address ditandai dengan tag `<address>` dan diakhiri dengan tag `</address>`. Tag address biasa digunakan untuk memberikan kontak informasi berupa alamat, misalnya alamat perusahaan atau lainnya. Hal ini merupakan hal yang umum dalam dokumen HTML, terutama website yang berupa profil perusahaan. Dengan adanya tag address, maka penulisan alamat dapat distandarkan. Tag address biasanya akan menampilkan alamat dalam format italic/miring, dan terdapat baris kosong sebelum dan sesudah alamat. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Contoh tag address :</p>
 <address>
 KOMINFO<br>
 Jl. Medan Merdeka Barat no. 9, Jakarta 10110<br>
 Telp. (021) 3452841<br>
 Email : humas@mail.kominfo.go.id
 </address>
</body>
</html>
```

## Cite Tag
Tag cite dimulai dengan tag `<cite>` dan diakhiri dengan tag `</cite>`. Tag cite digunakan untuk memberikan title pada suatu pekerjaan misalnya sebuah buku, lagu, film, lukisan atau lainnya. Teks yang ditampilkan biasanya berformat italic/miring. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Contoh tag cite :</p>
 <img src="https://berbagit.com/demo/sayap-sayap-patah.png" width="199" height="320" alt="Sayap Sayap Patah">
 <p><cite>Sayap Sayap Patah</cite> Karya Kahlil Gibran. Terbitan pertama tahun 1912. Penerjemah Indonesia oleh Sapardi Djoko Damono</p>
</body>
</html>
```

## Bi-Directional Override Tag
Tag Bi-Directional Override ditandai dengan tag `<bdo>` dan diakhiri dengan tag `</bdo>`. Tag bdo berfungsi untuk membalik arah penulisan teks yang semula dari kiri ke kanan menjadi dari kanan ke kiri (right to left / rtl ). Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Contoh bdo tag :</p>
 <bdo dir="rtl">Saat ini, dunia sedang di gegerkan oleh virus corona.</bdo>
</body>
</html>
```

Atribut `dir` berfungsi untuk memberi tahu ke arah mana tulisan akan dibalik, yaitu dari kanan ke kiri.

## Kesimpulan
Demikian penjelasan mengenai Quotation dan Citation pada HTML. Sekarang sudah jelas kan bagaimana membuat kutipan di halaman HTML.

Hasil dari koding pembahasan ini dapat dilihat di [link ini](/demo/html-quote.html). Jangan lupa berlatih menggunakan tanda-tanda quote diatas, buat sesuai kreasi Anda masing-masing. Setelah selesai latihan, Anda dapat mempelajari materi selanjutnya yaitu mengenai [Komentar pada HTML](/komentar-html).

Semoga tulisan ini bisa bermanfaat untuk kita semua. Jangan lupa untuk dishare kembali dan jika ada pertannyaan, silakan tinggalkan di kolom komentar. Terima kasih.