# Buat Daftar Tidak Terurut Bulleted

Contoh :

HTML memiliki elemen khusus untuk membuat daftar tidak berurutan, atau daftar gaya titik-koma. Daftar tidak berurutan dimulai dengan elemen

&lt;ul&gt;. Kemudian mereka mengandung beberapa elemen &lt;li&gt;

```css
<ul>
  <li> susu </ li>
  <li> keju </ li>
</ ul>
```

akan membuat daftar gaya poin-poin dari "susu" dan "keju".

Hapus dua elemen p terakhir dan buat daftar tiga hal yang tidak disukai yang disukai kucing di bagian bawah halaman.

Soal :

1. Buat elemen ul. 
2. Anda harus memiliki tiga elemen li dalam elemen ul Anda. 
3. Pastikan elemen ul Anda memiliki tag penutup. Pastikan elemen li Anda memiliki tag penutup.

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

<p>Click here for <a href="#">cat photos</a>.</p>

<a href="#">
<img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. ">
</a>
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

<a href="#"><img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. "></a>

<ul>
  <li>milk</li>
  <li>cheese</li>
  <li>chocolate</li>
</ul>
```



