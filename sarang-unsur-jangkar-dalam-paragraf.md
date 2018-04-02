# Sarang Unsur Jangkar dalam Paragraf

Sekali lagi, inilah diagram elemen untuk referensi Anda:

nilah contohnya:

```
<p>Ini adalah <a href="https://freecodecamp.org">tautan ke Free Code Camp </a>untuk Anda ikuti. </p>
```

Bersarang hanya berarti menempatkan satu elemen di dalam elemen lain.

Sekarang tempatkan elemen yang ada dalam elemen p baru \(tepat setelah elemen h2 yang ada\) sehingga paragraf sekitarnya mengatakan "Lihat lebih banyak foto kucing", tetapi hanya "foto kucing" adalah tautan, dan teks sisanya adalah teks biasa.

soal :

1. Anda memerlukan elemen yang tertaut ke "[http://www.freecatphotoapp.com](http://www.freecatphotoapp.com)".
2. Elemen Anda harus memiliki teks tautan "foto kucing"
3. Buat elemen p baru di sekitar elemen Anda.
4. Elemen Anda harus bersarang di dalam elemen p baru Anda.
5. Elemen p Anda harus memiliki teks "Lihat lebih banyak" \(dengan spasi setelahnya\).
6. Elemen Anda seharusnya tidak memiliki teks "Lihat lebih banyak".
7. Pastikan masing-masing elemen p Anda memiliki tag penutup.
8. Pastikan masing-masing elemen Anda memiliki tag penutup.

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
<a href="http://www.freecatphotoapp.com">cat photos</a>

<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>

<p>View more cat photos
<a href="http://www.freecatphotoapp.com">cat photos</a>
</p>


```



