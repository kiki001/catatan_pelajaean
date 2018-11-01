# ambahkan Kolom dengan grid-template-kolom

Cukup membuat elemen grid tidak membuat Anda sangat jauh. Anda perlu menentukan struktur grid juga. Untuk menambahkan beberapa kolom ke grid, gunakan properti grid-template-columns pada penampung grid seperti yang ditunjukkan di bawah ini:

```
.container {
  display: grid;
  grid-template-columns: 50px 50px;
}
```

Ini akan memberikan grid Anda dua kolom yang masing-masing memiliki lebar 50px.

Jumlah parameter yang diberikan ke properti grid-template-columns menunjukkan jumlah kolom dalam grid, dan nilai setiap parameter menunjukkan lebar setiap kolom.

Berikan penampung grid tiga kolom dengan lebar masing-masing 100 piksel.



Soal :

kelas kontainer harus memiliki properti grid-template-columns dengan tiga unit 100px.

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
    /* add your code below this line */
    grid-template-columns: 100px 100px 100px;
    
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



