# Tautan ke Halaman Eksternal dengan Elemen Anchor

Contoh :

elemen, juga dikenal sebagai elemen anchor, digunakan untuk menautkan ke konten di luar halaman saat ini.

Berikut diagram elemen. Dalam hal ini, elemen digunakan di tengah elemen paragraf, yang berarti tautan akan muncul di tengah-tengah kalimat.

Inilah contohnya :

```
<p>Ini adalah <a href="http://freecodecamp.org">tautan ke Free Code Camp </a>untuk Anda ikuti. </p>
```

Buat elemen yang tertaut ke [http://freecatphotoapp.com](http://freecatphotoapp.com) dan memiliki "cat photos" sebagai teks tautannya.

Soal :

1. Elemen Anda harus memiliki teks tautan "cat photos".
2. Anda memerlukan elemen yang tertaut ke [http://freecatphotoapp.com](http://freecatphotoapp.com)
3. Pastikan elemen Anda memiliki tag penutup.

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

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```

Jawaban :

```css

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

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet,<a href="http://freecatphotoapp.com">cat photos</a>
 shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>



```



