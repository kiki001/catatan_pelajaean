# Ukur Gambar Anda

Contoh :

CSS memiliki properti yang disebut lebar yang mengontrol lebar elemen. Sama seperti dengan font, kita akan menggunakan px \(piksel\) untuk menentukan lebar gambar.

Misalnya, jika kami ingin membuat kelas CSS yang disebut gambar besar yang memberi elemen HTML lebar 500 piksel, kami akan menggunakan:

```
<style>
  .larger-image {
    width: 500px;
  }
</style>
```

Soal :

Buat kelas yang disebut smaller-image dan gunakan untuk mengubah ukuran gambar sehingga hanya selebar 100 piksel.

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

  .smaller-image{
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
```



