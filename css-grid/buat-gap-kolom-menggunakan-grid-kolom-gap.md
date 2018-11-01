# Buat Gap Kolom Menggunakan grid-kolom-gap

Sejauh ini dalam grid yang telah Anda buat, semua kolom saling berdekatan. Terkadang Anda menginginkan celah di antara kolom. Untuk menambahkan celah di antara kolom, gunakan properti grid-column-gap seperti ini:

```
grid-column-gap: 10px;
```

Ini menciptakan 10px ruang kosong di antara semua kolom kami.

Berikan kolom di grid celah 20px.



Soal :

1. kelas kontainer harus memiliki properti grid-column-gap yang memiliki nilai 20px

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
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    /* add your code below this line */
    grid-column-gap: 20px;
    
    /* add your code above this line */
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



