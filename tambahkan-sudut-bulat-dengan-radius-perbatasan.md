# Tambahkan Sudut Bulat dengan Radius Perbatasan

Contoh :

Foto kucing Anda saat ini memiliki sudut yang tajam. Kita bisa melengkapi sudut-sudut itu dengan properti CSS yang disebut border-radius.

Anda dapat menentukan radius batas dengan piksel. Berikan foto kucing Anda batas-radius 10px.

Catatan: titik jalan ini memungkinkan untuk beberapa kemungkinan solusi. Misalnya, Anda dapat menambahkan border-radius ke kelas .thick-green-border atau kelas .smaller-image.

Soal :

1. Elemen gambar Anda harus memiliki kelas "tebal-hijau-perbatasan". 
2. Gambar Anda harus memiliki radius pembatas 10px

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

Jawaban :

```
*
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
  }

  .smaller-image {
    width: 100px;
  }
  
  .thick-green-border{
    border-radius: 10px;
  }
  
</style>

<h2 class="red-text">CatPhotoApp</h2>

<img class="smaller-image thick-green-border thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>

```



