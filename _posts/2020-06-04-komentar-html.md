---
date: 2020-06-04 01:53:02
layout: post
title: "Tutorial HTML #10 : Komentar di HTML"
subtitle: Cara menyembunyikan sesuatu di dokumen HTML.
description: Tag Comment berfungsi untuk memasukkan komentar atau catatan pada dokumen HTML. Komentar atau catatan tersebut tidak akan ditampilkan pada browser.
image: /assets/img/uploads/comment-html.png
optimized_image: /assets/img/uploads/comment-html.png
category: html
tags:
  - hidden-comment
  - conditional-comment
  - debugging-comment
author:
paginate: false
---

Pada HTML terdapat sebuah tag yang berfungsi untuk memasukkan komentar atau catatan pada dokumen HTML, tag tersebut adalah tag Comment. Komentar atau catatan tersebut tidak akan ditampilkan pada browser.

1. 
{:toc}

Tag komentar ditandai dengan tag `<!--` lalu diisi dengan teks yang berfungsi sebagai komentar, dan diakhiri dengan tag `-->` . Pada tag awal menggunakan tanda seru, sedangkan di tag akhir tidak menggunakan tanda seru. Dengan tag komentar, kita dapat memberi catatan pada kode HTML yang kita buat.

## Hidden Comment
Seperti sudah dijelaskan sebelumnya, bahwa tag komentar akan membuat catatan/komentar pada HTML yang akan disembunyikan dan tidak ditampilkan pada browser. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <!-- Ini contoh komentar -->
 <p>Ini contoh paragraf. Diatas paragraf ini ada komentar, namun tidak ditampilkan. Begitu juga dengan komentar yang ada dibawah ini, tidak ditampilkan oleh browser juga</p>
 <!-- Komentar atau catatan ini tidak akan ditampilkan di browser -->
</body>
</html>
```

## Conditional Comment
Komentar ini umumnya sebagai catatan untuk menyajikan dokumen pada masa yang akan datang. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <!--[if IE 5]>Ini adalah IE 5<br><![endif]-->
 <!--[if IE 6]>Ini adalah IE 6<br><![endif]-->
 <!--[if IE 7]>Ini adalah IE 7<br><![endif]-->
 <!--[if IE 8]>Ini adalah IE 8<br><![endif]-->
 <!--[if IE 9]>Ini adalah IE 9<br><![endif]-->
</body>
</html>
```

## Debugging Comment
Debugging Comment ini bisa dimanfaatkan untuk menyembunyikan sebagian isi dari halaman web. Hal ini bisa jadi karena belum ada kepastian dari isi dokumen yang akan ditampilkan atau perlu adanya approval sebelum bisa ditampilkan atau adanya hal lain. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <!-- Jangan tanmpilkan ini sekarang
 <img border="0" src="https://berbagit.com/assets/img/blog-image.png" alt="Logo Berbagit">
 -->
</body>
</html>
```

## Kesimpulan
Intinya komentar itu tidak akan ditampilkan pada browser. Fungsi dari komentar ini selain untuk menyembunyikan catatan, juga bisa untuk conditional comment dan untuk keperluan debugging.

Hasil dari koding pembahasan ini dapat dilihat di [link ini](/demo/html-comment.html). Jangan lupa berlatih menggunakan tanda-tanda komentar diatas, buat sesuai kreasi Anda masing-masing. Setelah selesai latihan, Anda dapat mempelajari materi selanjutnya.

Demikian penjelasan mengenai Komentar pada HTML. Jika ada pertanyaan, silakan ditinggalkan di kolom kementar, dan jangan lupa untuk mengshare artikel ini kembali melalui menu share di bawah. Terima kasih.
