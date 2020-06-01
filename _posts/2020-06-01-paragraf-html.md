---
date: 2020-06-01 06:33:18
layout: post
title: "Tutorial HTML #6 : Paragraf di HTML"
subtitle: Tag paragraf akan memberikan spasi/jarak sebelum dan sesudah tag
description: Paragraf ditandai dengan tag atau elemen p. Pada saat tampil di website, maka akan ada spasi atau jarak sebelum dan sesudah tag paragraf.
image: /assets/img/uploads/paragraf-html.png
optimized_image: /assets/img/uploads/paragraf-html.png
category: html
tags:
  - paragraf
  - br
  - pre
author:
paginate: false
---

Semua pasti sudah mengetahui apa itu Paragraf ? Ya, Paragraf adalah sekumpulan kalimat yang saling berkaitan antara kalimat yang satu dengan kalimat yang lain. Misalnya kita sering mendengar sewaktu sekolah bahwa pikiran utama disimpan dalam satu paragraf. Informasi yang disajikan dalam sebuah tulisan harus mengikuti kaidah-kaidah dalam penulisan.

1. 
{:toc}

## Tag Paragraf
Pada HTML, Paragraf ditandai dengan tag `<p>` dan diakhiri dengan tag `</p>`. Pada saat tampil di website, maka akan ada spasi/jarak sebelum dan sesudah tag paragraf seperti jarak ketika ditekan Enter/lompat 1 baris. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
​
 <p>Ini contoh sebuah paragraf.</p>
 <p>Ini contoh paragraf lainnya.</p>
 <p>Kita sedang belajar paragraf.</p>
 ​
</body>
</html>
```

## Tampilan Paragraf
Di dalam tag Paragraf, ketika kita menambahkan banyak spasi atau menambah banyak baris agar terlihat berbeda, namun hasilnya akan tetap sama seperti tidak ditambahkan banyak spasi atau banyak baris karena browser akan menghilangkan spasi atau baris tambahan tersebut. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>
 Paragraf ini
 berisi beberapa baris
 didalam tag paragrafnya,
 tetapi browser
 menghilangkannya.
 </p>
 <p>
 Paragraf ini
 berisi      banyak spasi
 didalam     tag paragrafnya,
 tetapi    browser
 menghilangkannya.
 </p>
 <p>
 Jumlah baris didalam paragraf bergantung pada ukurun lebar browser, bukan pada berapa banyak kita menekan Enter untuk menambah baris. Jika kita mengecilkan ukuran browser, maka jumlah baris paragraf akan bertambah. Jumlah spasi tidak akan mempengaruhi jarak antar kalimat, karena browser akan menghilangkan jumlah spasi yang lebih dari 1.
 </p>
</body>
</html>
```

## br Tag
Untuk menambah baris di dalam Paragraf, maka kita dapat menggunakan tag `<br>`. Tag br berfungsi sebagai elemen pemisah baris dalam HTML. Kita dapat memaksakan ganti baris pada dokumen web, dengan memakai tag br ini. Ganti baris disini maksudnya hanya menyajikan informasi pada baris sendiri, tetapi tidak berganti paragraf. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Ini adalah<br>sebuah paragraf<br>dengan pemisah baris tag br</p>
</body>
</html>
```

## pre Tag
Untuk menampilkan tulisan apa adanya misal ingin banyak spasi atau banyak baris, maka dapat digunakan tag `<pre>`. Tulisan yang berada dalam tag pre maka akan tampil apa adanya, baik baris maupun spasinya dan biasanya jenis huruf nya akan berubah menjadi Courier. Tag pre dikenal juga dengan tag preformatted text. Bisa digunakan untuk menulis, puisi, lirik lagu atau lainnya. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
<p>Tag pre akan menampilkan tulisan apa adanya, baik spasi maupun barisnya.</p>
<pre>
 Begadang jangan begadang
 Kalau tiada artinya
 Begadang boleh saja
 Kalau ada perlunya

 Kalau    terlalu banyak      begadang
 Muka pucat      karena      darah berkurang
 Bila       sering kena    angin malam
 Segala      penyakit akan      mudah datang
 Darilah itu      sayangi badan
 Jangan begadang     setiap malam
</pre>
</body>
</html>
```

## Jangan lupa tag penutup
Hampir semua browser akan menampilkan paragraf dengan benar meskipun tanpa tag penutup. Namun hal seperti ini tidak dianjurkan, karena menyalahi aturan dan ditakutkan akan terjadi error yang tidak diketahui. Contoh :

```html
<!DOCTYPE html>
<html>
<body>
 <p>Ini contoh paragraf tanpa tag penutup.
 <p>Ini juga contoh paragraf tanpa tag penutup.
 <p>Ini juga contoh paragraf tanpa tag penutup lagi.
 <p>Jangan lupa memberikan tag penutup pada paragraf !!!</p>
</body>
</html>
```

## Kesimpulan
Demikian penjelasan mengenai Paragraf pada HTML. Dimana tag paragraf ini akan memberikan spasi atau jarak sebelum dan sesudah tag, sehingga sangat berguna untuk diterapkan pada halaman HTML.

Hasil dari koding pembahasan ini dapat dilihat di [link ini](/demo/html-paragraf.html). Jangan lupa berlatih menggunakan tag paragraf dan tag lainnya yang sudah dipelajari agar ilmu yang didapat dapat diingat lebih lama. Setelah selesai latihan, Anda dapat mempelajari materi selanjutnya yaitu mengenai Style pada HTML.

Semoga bisa bermanfaat untuk semua. Dan jangan lupa klik tombol share nya untuk berbagi ke yang lain supaya tambah bermanfaat. Jika ada pertanyaan, silahkan tinggalkan di kolom komentar. Terima kasih.