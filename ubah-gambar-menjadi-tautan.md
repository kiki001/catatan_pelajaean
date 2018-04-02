# Ubah Gambar menjadi Tautan

Contoh :

Anda dapat membuat elemen menjadi tautan dengan menempatkannya di dalam elemen. Sarang gambar Anda dalam sebuah elemen. Inilah contohnya:

```
<a href="#">
    <img src = "https://bit.ly/fcc-running-cats" alt = "Tiga anak kucing berlari ke arah kamera.">
</a>
```

Ingat untuk menggunakan \# sebagai properti href elemen Anda untuk mengubahnya menjadi tautan mati. Tempatkan elemen gambar yang ada di dalam elemen anchor. Setelah Anda melakukan ini, arahkan kursor ke gambar Anda dengan kursor Anda. Penunjuk normal kursor Anda harus menjadi penunjuk tautan tautan. Foto sekarang adalah tautan.

Soal :

1. Sarang elemen img yang ada di dalam elemen.
2. Elemen Anda harus tautan mati dengan atribut href disetel ke \#.
3. Pastikan masing-masing elemen Anda memiliki tag penutup.

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

<p>Click here for <a href="#">cat photos</a>.</p>

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

<p>Click here for <a href="#">cat photos</a>.</p>

<a href="#">
<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">
</a>
<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>

```



