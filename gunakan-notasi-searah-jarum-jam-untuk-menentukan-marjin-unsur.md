# Gunakan Notasi Searah Jarum Jam untuk Menentukan Marjin Unsur

Contoh :

Mari coba lagi, tapi dengan margin kali ini.

Daripada menentukan properti margin-atas, margin-kanan, margin-bawah, dan margin-kiri, Anda dapat menentukan semuanya dalam satu baris, seperti ini:

```
margin: 10px 20px 10px 20px;
```

Keempat nilai ini bekerja seperti jam: atas, kanan, bawah, kiri, dan akan menghasilkan hasil yang sama persis seperti menggunakan instruksi margin sisi-spesifik.

Gunakan Notasi Searah Jarum Jam untuk memberi elemen dengan green-box class margin 40px pada sisi atas dan kiri, tetapi hanya 20px pada sisi bawah dan kanannya.

Soal :

1. Kelas green-box Anda harus memberikan bagian atas elemen 40px margin. 
2. Kelas green-box Anda harus memberikan hak dari 20px margin elemen. 
3. Kelas green-box Anda harus memberikan bagian bawah elemen 20px margin. 
4. Kelas green-box Anda harus memberikan elemen kiri 40px margin.

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

Jawaban :

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
    padding: 20px 40px 20px 20px;
  }
  
  .red-box {
    background-color: red;
    margin: 20px 40px 20px 40px;
  }

  .green-box {
    background-color: green;
    margin: 40px 20px 20px 40px;
  }
</style>
<h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box green-box">padding</h5>
</div>

```



