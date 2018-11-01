# Gunakan unit Grid CSS untuk Mengubah Ukuran Kolom dan Baris

Anda dapat menggunakan unit absolut dan relatif seperti px dan em di CSS Grid untuk menentukan ukuran baris dan kolom. Anda dapat menggunakan ini juga:

fr: menetapkan kolom atau baris ke sebagian kecil dari ruang yang tersedia,

otomatis: menetapkan kolom atau baris ke lebar atau tinggi kontennya secara otomatis,

%: menyesuaikan kolom atau baris ke lebar persen wadahnya.

Inilah kode yang menghasilkan output dalam pratinjau:

`grid-template-columns: auto 50px 10% 2fr 1fr;`

Cuplikan ini membuat lima kolom. Kolom pertama seluas isinya, kolom kedua adalah 50px, kolom ketiga adalah 10% dari wadahnya, dan untuk dua kolom terakhir; ruang yang tersisa dibagi menjadi tiga bagian, dua dialokasikan untuk kolom keempat, dan satu untuk yang kelima.

---

Buat grid dengan tiga kolom yang lebarnya sebagai berikut: 1fr, 100px, dan 2fr.



Soal :

1. kelas kontainer harus memiliki properti grid-template-columns yang memiliki tiga kolom dengan lebar berikut: 1fr, 100px, dan 2fr.

Jawaban :

```
<style>
  .d1{background:LightSkyBlue;}
  .d2{background:LightSalmon;}
  .d3{background:PaleTurquoise;}
  .d4{background:LightPink;}
  .d5{background:PaleGreen;}
  
  .container {
    font-size: 40px;
    width: 100%;
    background: LightGray;
    display: grid;
    /* modify the code below this line */
    
    grid-template-columns: auto 50px 10% 2fr 1fr;
    grid-template-columns: 1fr 100px 2fr;
    /* modify the code above this line */
    grid-template-rows: 50px 50px;
  }
</style>
  
<div class="container">
  <div class="d1">1</div>
  <div class="d2">2</div>
  <div class="d3">3</div>
  <div class="d4">4</div>
  <div class="d5">5</div>
</div>
```



