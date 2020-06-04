---
date: 2020-06-02 15:47:03
layout: post
title: "Tutorial HTML #8 : Text Formating di HTML"
subtitle: Ingin memformat tampilan text, ikuti cara berikut ini.
description: Text Formatting pada HTML berfungsi untuk memformat teks atau mengatur teks tetapi bukan menggunakan style melainkan dengan tag atau elemen spesial.
image: /assets/img/uploads/text-formating-html.png
optimized_image: /assets/img/uploads/text-formating-html.png
category: html
tags:
  - bold
  - strong
  - italic
  - emphasized
  - small
  - mark
  - delete
  - insert
  - subscript
  - superscript
author: berbagit
paginate: false
---

Pada pembahasan sebelumnya, kita telah belajar tentang [style pada elemen HTML](/style-html). Kali ini kita akan belajar tentang memformat teks atau mengatur teks tetapi bukan menggunakan style. Kita akan mengatur teks dengan tag atau elemen spesial. Elemen tersebut diantaranya untuk menebalkan teks, membuat miring teks, dan lain-lain. Ok langsung saja kita pelajari satu-persatu elemen tersebut di bawah ini.

1. 
{:toc}

## Bold dan Strong Elemen
Tag Bold ditandai dengan tag `<b>` dan diakhiri dengan tag `</b>`, sedangkan tag Strong ditandai dengan tag `<strong>` dan diakhiri dengan tag `</strong>`. Tag Bold dan Strong secara kasat mata mempunyai fungsi yang sama, yaitu untuk menebalkan huruf. Namun di sisi mesin pencari, tag tersebut mempunyai fungsi yang berbeda. Di mata mesin pencari, tag Bold berfungsi hanya untuk menebalkan huruf saja, sedangkan tag Strong selain untuk menebalkan huruf juga sebagai penanda bahwa tulisan itu penting, sehingga dapat diketahui oleh mesin pencari dan diperkirakan dapat meningkatkan artikel tersebut di mata mesin pencari. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Ini teks normal.</p>
 <p><b>Ini teks dengan Bold elemen.</b></p>
 <p><strong>Ini teks dengan Strong elemen.</strong></p>
</body>
</html>
```

## Italic dan Emphasized Elemen
Tag Italic ditandai dengan tag `<i>` dan diakhiri dengan tag `</i>`, sedangkan tag Emphasized ditandai dengan tag `<em>` dan diakhiri dengan tag `</em>`. Tag Italic dan Emphasized secara kasat mata mempunyai fungsi yang sama, yaitu untuk memiringkan huruf. Namun di sisi mesin pencari, tag tersebut mempunyai fungsi yang berbeda. Di mata mesin pencari, tag Italic berfungsi hanya untuk memiringkan huruf saja, sedangkan tag Emphasized selain untuk memiringkan huruf juga sebagai penanda bahwa tulisan itu penting, sehingga dapat diketahui oleh mesin pencari dan diperkirakan dapat meningkatkan artikel tersebut di mata mesin pencari, sama seperti tag strong. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Ini teks normal.</p>
 <p><i>Ini teks dengan Italic elemen.</i></p>
 <p><em>Ini teks dengan Emphasized elemen.</em></p>
</body>
</html>
```

## Small Elemen
Tag Small ditandai dengan tag `<small>` dan diakhiri dengan tag `</small>`. Fungsi dari tag Small yaitu untuk mengecilkan huruf. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2>Ini contoh HTML <small>Small</small> Elemen</h2>
</body>
</html>
```

## Mark Elemen
Tag Mark ditandai dengan tag `<mark>` dan diakhiri dengan tag `</mark>`. Fungsi dari tag Mark yaitu untuk memberikan tanda highlight pada sebuah teks. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <h2>Ini contoh HTML <mark>Mark</mark> Elemen</h2>
</body>
</html>
```

## Delete Elemen
Tag Delete ditandai dengan tag `<del>` dan diakhiri dengan tag `</del>`. Fungsi dari tag Delete adalah untuk memberikan tanda coret pada sebuah teks. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Warna favorit saya adalah <del>merah</del> biru.</p>
</body>
</html>
```

## Insert Elemen
Tag Insert ditandai dengan tag `<ins>` dan diakhiri dengan tag `</ins>`. Fungsi dari tag Insert adalah untuk memasukkan sebuah teks dengan tanda garis bawah. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Warna favorit <ins>saya</ins> adalah biru.</p>
</body>
</html>
```

## Subscript Elemen
Tag Subscript ditandai dengan tag `<sub>` dan diakhiri dengan tag `</sub>`. Fungsi dari tag Subscript adalah untuk mengecilkan huruf ke bawah. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Ini adalah contoh <sub>subscript</sub> teks.</p>
</body>
</html>
```

## Superscript Elemen
Tag Superscript ditandai dengan tag `<sup>` dan diakhiri dengan tag `</sup>`. Fungsi dari tag Superscript adalah untuk mengecilkan huruf ke atas. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Ini adalah contoh <sup>superscript</sup> teks.</p>
</body>
</html>
```

## Kesimpulan
Demikianlah pembahasan mengenai memformat teks pada HTML. Semoga dengan tutorial ini Anda dapat memformat teks yang ada pada dokumen html Anda.

Hasil dari koding pembahasan ini dapat dilihat di [link ini](/demo/html-formating.html). Jangan lupa berlatih menggunakan elemen-elemen formating diatas, kreasikan hasil latihan Anda sebelumnya dengan menggunakan formating teks ini sehingga menjadi lebih enak dilihat. Setelah selesai latihan, Anda dapat mempelajari materi selanjutnya yaitu mengenai [Quotation dan Citation pada HTML](/quotation-citation-html).

Semoga bisa bermanfaat untuk kita semua, dan jangan lupa dishare supaya tambah bermanfaat. Jika ada pertanyaan, silakan tinggalkan di kolom komentar. Terima kasih.