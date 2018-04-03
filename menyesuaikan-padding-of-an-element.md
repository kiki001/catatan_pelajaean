# Menyesuaikan Padding of Element

Contoh :

Sekarang mari letakkan App Cat Photo kami untuk sementara dan pelajari lebih lanjut tentang styling HTML.

Anda mungkin telah memperhatikan ini, tetapi semua elemen HTML pada dasarnya adalah persegi panjang kecil.

Tiga properti penting mengontrol ruang yang mengelilingi setiap elemen HTML: padding, margin, dan border.

Padding elemen mengontrol jumlah ruang antara elemen dan perbatasannya.

Di sini, kita dapat melihat bahwa kotak hijau dan kotak merah bersarang di dalam kotak kuning. Perhatikan bahwa kotak merah memiliki padding lebih dari kotak hijau.

Ketika Anda meningkatkan padding kotak hijau, itu akan meningkatkan jarak antara padding teks dan perbatasan di sekitarnya.

Ubah padding kotak hijau Anda agar cocok dengan kotak merah Anda.

Soal :

1. Kelas green-box Anda harus memberikan elemen 20px padding.

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

  .silver-background {
    background-color: silver;
  }
  #cat-photo-form {
    background-color: green;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p>Click here for <a href="#">cat photos</a>.</p>

<a href="#"><img class="smaller-image thick-green-border" alt="A cute orange cat lying on its back. " src="https://bit.ly/fcc-relaxing-cat"></a>

<div class="silver-background">
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
</div>

<form action="/submit-cat-photo" id="cat-photo-form">
  <label><input type="radio" name="indoor-outdoor" checked> Indoor</label>
  <label><input type="radio" name="indoor-outdoor"> Outdoor</label>
  <label><input type="checkbox" name="personality" checked> Loving</label>
  <label><input type="checkbox" name="personality"> Lazy</label>
  <label><input type="checkbox" name="personality"> Energetic</label>
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
</form>
```

Jawaban :

```css
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }

  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }

  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }

  .red-box {
    background-color: red;
    padding: 20px;
  }

  .green-box {
    background-color: green;
    padding: 20px;
  }


</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
```



