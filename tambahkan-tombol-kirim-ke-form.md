# Tambahkan Tombol Kirim ke Form

Mari tambahkan tombol kirim ke formulir Anda. Mengeklik tombol ini akan mengirim data dari form Anda ke URL yang Anda tentukan dengan atribut tindakan formulir Anda.

Berikut ini contoh tombol kirim :

```
<button type = "submit"> tombol ini menyerahkan form </ button>
```

Tambahkan tombol kirim ke elemen form Anda dengan ketik kirim dan "Kirim" sebagai teksnya.

Soal :

Form Anda harus memiliki tombol di dalamnya.

Tombol kirim Anda harus memiliki jenis atribut yang ditetapkan untuk dikirimkan.

Tombol kirim Anda hanya boleh memiliki teks "Kirim".

Pastikan elemen tombol Anda memiliki tag penutup.

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

<a href="#"><img class="smaller-image thick-green-border" alt="A cute orange cat lying on its back. " src="https://bit.ly/fcc-relaxing-cat"></a>

<p>Things cats love:</p>
<ul>
  <li>cat nip</li>
  <li>laser pointers</li>
  <li>lasagna</li>
</ul>
<p>Top 3 things cats hate:</p>
<ol>
  <li>flea treatment</li>
  <li>thunder</li>
  <li>other cats</li>
</ol>

<form action="/submit-cat-photo">
  <input type="text" placeholder="cat photo URL">
</form>
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

<a href="#"><img class="smaller-image thick-green-border" alt="A cute orange cat lying on its back. " src="https://bit.ly/fcc-relaxing-cat"></a>

<p>Things cats love:</p>
<ul>
  <li>cat nip</li>
  <li>laser pointers</li>
  <li>lasagna</li>
</ul>
<p>Top 3 things cats hate:</p>
<ol>
  <li>flea treatment</li>
  <li>thunder</li>
  <li>other cats</li>
</ol>
<form action="/submit-cat-photo">
  <input type="text" placeholder="cat photo URL">
  <button type="submit">submit</button>
</form>

```



