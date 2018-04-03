# Gunakan Notasi Searah Jarum Jam untuk Menentukan Padding of an Element

Contoh :

Daripada menentukan properti padding-top, padding-right, padding-bottom, dan padding-left, Anda dapat menentukan semuanya dalam satu baris, seperti ini:

padding: 10px 20px 10px 20px;

Keempat nilai ini bekerja seperti jam: atas, kanan, bawah, kiri, dan akan menghasilkan hasil yang sama persis dengan menggunakan instruksi padding spesifik samping.

Gunakan Notasi Searah Jarum Jam untuk memberikan kelas "hijau-kotak" padding dari 40px di bagian atas dan sisi kiri, tetapi hanya 20px di bagian bawah dan sisi kanan.

Soal :

1. Kelas green-box Anda harus memberikan bagian atas elemen 40px padding.
2. Kelas green-box Anda harus memberikan hak elemen 20px padding.
3. Kelas green-box Anda harus memberikan bagian bawah elemen 20px padding.
4. Kelas green-box Anda harus memberikan elemen kiri 40px padding.

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
    padding: 20px 40px 20px 40px;
  }

  .red-box {
    background-color: red;
    padding: 20px 40px 20px 40px;
  }

  .green-box {
    background-color: green;
    padding: 40px 20px 20px 40px;
  }
</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>
```



