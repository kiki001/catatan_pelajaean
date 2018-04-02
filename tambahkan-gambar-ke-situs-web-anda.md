# Tambahkan Gambar ke Situs Web Anda

Anda dapat menambahkan gambar ke situs web Anda dengan menggunakan elemen img, dan arahkan ke URL gambar tertentu menggunakan atribut src.

Contoh dari ini adalah:

```
<img src = "https://www.your-image-source.com/your-image.jpg">
```

Semua elemen img harus memiliki atribut alt. Teks di dalam atribut alt digunakan untuk pembaca layar untuk meningkatkan aksesibilitas dan ditampilkan jika gambar gagal dimuat.

Semua elemen img harus memiliki atribut alt. Teks di dalam atribut alt digunakan untuk pembaca layar untuk meningkatkan aksesibilitas dan ditampilkan jika gambar gagal dimuat.

Mari tambahkan atribut alt ke contoh img kami di atas:

```
<img src = "https://www.your-image-source.com/your-image.jpg" alt = "Penulis berdiri di pantai dengan dua jempol.">
```

Perhatikan bahwa dalam banyak kasus, elemen img menutup sendiri.

Coba dengan gambar ini:

```
https://bit.ly/fcc-relaxing-cat
```

Soal:

1. Halaman Anda harus memiliki elemen gambar. 
2. Gambar Anda harus memiliki atribut src yang mengarah ke gambar anak kucing.
3. Elemen gambar Anda harus memiliki atribut alt. 

```
<!-- <link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css"> -->
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
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```

Jawaban :

```
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">

<img src="https://bit.ly/fcc-relaxing-cat" alt="Author standing on a beach with two thumbs up. ">
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
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



