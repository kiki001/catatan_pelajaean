# Tambahkan Margin yang Berbeda ke Setiap Sisi Elemen

Contoh :

Kadang-kadang Anda akan ingin menyesuaikan elemen sehingga memiliki margin yang berbeda pada masing-masing sisinya.

CSS memungkinkan Anda mengontrol margin suatu elemen pada keempat sisinya dengan properti margin-top, margin-right, margin-bottom, dan margin-left.

Beri kotak hijau margin 40px di bagian atas dan sisi kiri, tetapi hanya 20px di sisi bawah dan kanannya.

Soal :

1. Kelas green-box Anda harus memberikan bagian atas elemen 40px margin. 
2. Kelas green-box Anda harus memberikan elemen kiri 40px margin. 
3. Kelas green-box Anda harus memberikan hak dari 20px margin elemen. 
4. Kelas green-box Anda harus memberikan bagian bawah elemen 20px margin.

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
    margin-top: 40px;
    margin-right: 20px;
    margin-bottom: 20px;
    margin-left: 40px;
  }

  .green-box {
    background-color: green;
    margin-top: 40px;
    margin-right: 20px;
    margin-bottom: 20px;
    margin-left: 40px;
  }
</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>

```



