# Sesuaikan Marjin Unsur

Contoh :

Batas elemen mengontrol jumlah ruang antara batas elemen dan elemen sekitarnya.

Di sini, kita dapat melihat bahwa kotak hijau dan kotak merah bersarang di dalam kotak kuning. Perhatikan bahwa kotak merah memiliki lebih banyak margin daripada kotak hijau, membuatnya tampak lebih kecil.

Ketika Anda meningkatkan margin kotak hijau, itu akan meningkatkan jarak antara perbatasannya dan elemen sekitarnya.

Ubah margin kotak hijau agar cocok dengan kotak merah.

Soal :

1. Kelas green-box Anda harus memberikan elemen 20px margin.

```
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
    margin: 20px;
  }

  .green-box {
    background-color: green;
    padding: 20px;
    margin: 20px;
  }
</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>

```



