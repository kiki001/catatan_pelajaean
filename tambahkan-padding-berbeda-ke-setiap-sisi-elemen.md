# Tambahkan Padding Berbeda ke Setiap Sisi Elemen

Contoh :

Kadang-kadang Anda akan ingin menyesuaikan elemen sehingga memiliki padding yang berbeda pada masing-masing sisinya.

CSS memungkinkan Anda mengontrol padding elemen pada keempat sisi dengan properti padding-top, padding-right, padding-bottom, dan padding-left.

Berikan kotak hijau padding 40px di bagian atas dan sisi kiri, tetapi hanya 20px di bagian bawah dan sisi kanan.

Soal :

Kelas green-box  Anda harus memberikan bagian atas elemen 40px padding.

Kelas green-box  Anda harus memberikan elemen kiri 40px padding.

Kelas green-box  Anda harus memberikan hak elemen 20px padding.

Kelas green-box  Anda harus memberikan bagian bawah elemen 20px padding.

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
    padding-top: 40px;
    padding-right: 20px;
    padding-bottom: 20px;
    padding-left: 40px;
  }

  .green-box {
    background-color: green;
    padding-top: 40px;
    padding-right: 20px;
    padding-bottom: 20px;
    padding-left: 40px;
  }
</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
```



