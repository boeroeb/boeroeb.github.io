---
date: 2020-05-19 05:03:09
layout: post
title: Cara Menghitung Karakter dan Kata
subtitle: Cara Gampang Menghitung Karakter dan Kata
description: Cara gampang menghitung karakter dan kata yaitu dengan menggunakan javascript yang ada pada halaman ini. Agar SEO Friendly usahakan lebih dari 300 kata. 
image: /assets/img/uploads/menghitung-karakter-kata.png
optimized_image: /assets/img/uploads/menghitung-karakter-kata.png
category: blog
tags:
  - javascript
  - css
  - html
  - seo
author: heru
paginate: false
---
Terkadang kita kepo ingin megetahui berapa sih jumlah kata atau karakter yang ada pada postingan atau artikel yang kita buat dengan maksud agar lebih SEO Friendly gitu. Apakah kamu termasuk orang seperti itu ? Jika iya simak caranya dibawah ini.

1. 
{:toc}

## Masalah Utama
Seperti sudah disebutkan diatas permasalahan utama dari pembahasan ini adalah bagaimana cara kita mengetahui banyak nya karakter dan kata pada postingan yang kita buat. Kalau kita hitung satu-satu capet banget kan ):. Biasanya bagi para blogger yang sedang mengincar google adsense sering bertanya-tanya berapa sih minimal tulisan dalam 1 buah artikel. Meskipun tidak ada jawaban pasti, namun dari beberapa pakar blogger berpendapat bahwa tulisan dalam 1 buah artikel minimal yaitu 300 kata. Semakin panjang lebih dari 300 kata semakin baik. 

## Solusi
Solusinya yaitu menggunakan javascript. Dengan menggunakan javascript kita bisa membuat fungsi untuk menghitung banyaknya kata atau karakter. Dengan bantuan HTML dan CSS maka tampilannya pun semakin menarik.

## Source Code
Berikut ini source code untuk menghitung banyaknya kata atau karakter :
```html
 <script type="text/javascript">  
      function words(content){  
           var i=0;  
           var numberofwords=1;  
           while(i<=content.length){  
                if (content.substring(i,i+1) == " "){  
                     numberofwords++;  
                     i++;  
                }  
                if (content.substring(i,i+1) == "\n"){  
                     numberofwords++;  
                     i++;  
                }  
                i++;  
           }  
           return numberofwords;  
      }  
 </script>  
   
 <style type="text/css">  
      input.berbagi{color:#ff8e1f;font:14px verdana,sans-serif;font-weight:bold;background-color:#feffbf;border:1px dashed #c9c8c8;height:20px}  
      textarea.berbagit{width:450px;height:100px;color:#24006b;font:12px arial;background:#e6febf;border:1px dotted #289728}  
 </style>  
   
 <center>  
 <form>  
      <textarea class="berbagit" cols="50" rows="5" onchange="this.form.char.value=this.value.length;this.form.word.value=words(this.value)"></textarea>  
      <br>  
      <input class="berbagi" name="char" size="4"> <b>Karakter</b>  
      <input class="berbagi" name="word" size="4"> <b>Kata</b>  
 </form>  
 </center>  
```

## Hasil Akhir Fungsi Menghitung Karakter dan Kata
Dibawah ini adalah tool untuk menghitung karakter dan kata :

 <script type="text/javascript">  
      function words(content){  
           var i=0;  
           var numberofwords=1;  
           while(i<=content.length){  
                if (content.substring(i,i+1) == " "){  
                     numberofwords++;  
                     i++;  
                }  
                if (content.substring(i,i+1) == "\n"){  
                     numberofwords++;  
                     i++;  
                }  
                i++;  
           }  
           return numberofwords;  
      }  
 </script>  
   
 <style type="text/css">  
      input.berbagi{color:#ff8e1f;font:14px verdana,sans-serif;font-weight:bold;background-color:#feffbf;border:1px dashed #c9c8c8;height:20px}  
      textarea.berbagit{width:450px;height:100px;color:#24006b;font:12px arial;background:#e6febf;border:1px dotted #289728}  
 </style>  
   
 <center>  
 <form>  
      <textarea class="berbagit" cols="50" rows="5" onchange="this.form.char.value=this.value.length;this.form.word.value=words(this.value)"></textarea>  
      <br>  
      <input class="berbagi" name="char" size="4"> <b>Karakter</b>  
      <input class="berbagi" name="word" size="4"> <b>Kata</b>  
 </form>  
 </center>  

Penggunaan tool ini yaitu dengan mengisi kolom diatas dengan teks yang ingin kita hitung, lalu tinggal klik di kolom karakter maka otomatis akan menghitung sendiri banyaknya karakter dan kata dari teks tersebut.

## Kesimpulan
Gimana mudah bukan? Sekarang kamu sudah bisa menghitung jumlah kata atau karakter dalam suatu artikel. Bagi yang ingin mendaftar Google Adsense, tool ini dapat digunakan untuk menghitung banyaknya kata dalam artikel / postingan yang kita buat agar artikel kita bisa ter-index dengan baik oleh google. Selain panjang, tentu kualiatas tulisan pun harus ditingkatkan. Karena salah satu ciri-ciri konten yang berkualitas adalah pembahasannya yang mendalam dan disampaikan secara detail. Konten seperti itu tentunya akan lebih panjang daripada konten biasa, dan menjadikannya konten berkualitas. Jika kontennya sudah berkualitas maka akan meningkatkan potensi direferensikan oleh banyak orang. Dan tentunya bukan tidak mungkin mendapatkan banyak backlink secara natural. Dan jangan lupa buatlah tulisan untuk manusia, karena yang membaca adalah manusia serta gunakan tema yang bisa membuat nyaman pembaca. Tentu masih banyak faktor agar tulisan kita bisa menjadi nomor 1 dihalaman pencarian google. Ok sekian dulu tutorial kali ini. Silakan dishare dan semoga bermanfaat.