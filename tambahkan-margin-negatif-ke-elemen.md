# Tambahkan Margin Negatif ke Elemen

Contoh :

Batas elemen mengontrol jumlah ruang antara batas elemen dan elemen sekitarnya.

Jika Anda menetapkan margin elemen ke nilai negatif, elemen akan bertambah besar.

Coba atur margin ke nilai negatif seperti yang untuk kotak merah.

Ubah margin kotak hijau menjadi -15px, sehingga memenuhi seluruh lebar horizontal kotak kuning di sekitarnya.

Soal :

1. Kelas green-box Anda harus memberikan elemen -15px margin.

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
    margin: -15px;
  }

  .green-box {
    background-color: green;
    padding: 20px;
    margin: -15px;
  }
</style>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>

```



