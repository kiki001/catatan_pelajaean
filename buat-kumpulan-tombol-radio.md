# Buat Kumpulan Tombol Radio

Anda dapat menggunakan tombol radio untuk pertanyaan di mana Anda ingin pengguna hanya memberi Anda satu jawaban.

Tombol radio adalah jenis input

Setiap tombol radio Anda harus bersarang di dalam elemen labelnya sendiri.

Semua tombol radio terkait harus memiliki atribut nama yang sama.

Berikut ini contoh tombol radio:

```
<label> <input type = "radio" name = "indoor-outdoor"> Dalam ruangan </ label>
```

Tambahkan sepasang tombol radio ke formulir Anda. Satu harus memiliki opsi indoor dan yang lain harus memiliki opsi outdoor

Soal :

1. Halaman Anda harus memiliki dua elemen tombol radio.
2. Berikan tombol radio Anda atribut nama indoor-outdoor.
3. Masing-masing dari dua elemen tombol radio Anda harus bersarang di elemen labelnya sendiri.
4. Pastikan setiap elemen label Anda memiliki tag penutup.
5. Salah satu tombol radio Anda harus memiliki label dalam ruangan.
6. Salah satu tombol radio Anda harus memiliki label luar.

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
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
</form>
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
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
  <label>
    <input type="radio" name="indoor-outdoor">Indoor
  </label>
  <label>
    <input type="radio" name="indoor-outdoor">outdoor
  </label>
</form>

```



