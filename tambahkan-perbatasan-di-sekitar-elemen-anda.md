# Tambahkan Perbatasan di Sekitar Elemen Anda

Contoh :

Batas CSS memiliki properti seperti gaya, warna, dan lebar

Misalnya, jika kita ingin membuat merah, 5 piksel perbatasan di sekitar elemen HTML, kita bisa menggunakan kelas ini:

```
<style>
  .thin-red-border {
    border-color: red;
    border-width: 5px;
    border-style: solid;
  }
</style>
```

Buat kelas yang disebut tebal-hijau-perbatasan yang menempatkan perbatasan hijau 10-piksel-lebar dengan gaya padat di sekitar elemen HTML, dan terapkan kelas itu ke foto kucing Anda.

Ingat bahwa Anda dapat menerapkan beberapa kelas ke elemen dengan memisahkan setiap kelas dengan spasi di dalam atribut kelasnya. Sebagai contoh:

```
<img class="class1 class2">
```

Soal :

Elemen img Anda harus memiliki kelas yang lebih smaller-image

Elemen img Anda harus memiliki kelas thick-green-border

Berikan gambar Anda dengan lebar tepi 10px.

Berikan gambar Anda gaya bingkai yang solid.

Perbatasan di sekitar elemen img Anda harus berwarna hijau.

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }

  .smaller-image{
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```

Jawaban :

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }

  .smaller-image {
    width: 100px;
  }

  .thick-green-border{
    border-color: green;
    border-width: 10px;
    border-style: solid;

  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



