# Buat Daftar Terurut

Contoh :

HTML memiliki elemen khusus untuk membuat daftar yang dipesan, atau daftar gaya bernomor.

Daftar yang dipesan mulai dengan elemen &lt;ol&gt;. Kemudian mereka mengandung beberapa elemen &lt;li&gt;

Sebagai contoh :

```
<ol>
  <li> Garfield </ li>
  <li> Sylvester </ li>
</ ol>
```

akan membuat daftar bernomor "Garfield" dan "Sylvester".

Buat daftar urutan 3 hal teratas yang paling dibenci kucing.

Soal :

1. Anda harus memiliki daftar pesanan untuk "Top 3 hal kucing benci:"
2. Anda harus memiliki daftar tak terbatas untuk "Hal-hal yang disukai kucing:"
3. Anda harus memiliki tiga elemen li dalam elemen ul Anda.
4. Anda harus memiliki tiga elemen li dalam elemen ol Anda.
5. Pastikan elemen ul Anda memiliki tag penutup.
6. Pastikan elemen ol Anda memiliki tag penutup.
7. Pastikan elemen li Anda memiliki tag penutup.

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
  <li>Garfield</li>
  <li>Sylvester</li>
  <li>cigarette</li>
</ol>

```



