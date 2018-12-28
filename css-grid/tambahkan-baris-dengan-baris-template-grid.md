# Tambahkan Baris dengan baris-template-grid

properti grid-template-rows dengan cara yang sama yang Anda gunakan grid-template-columns dalam tantangan sebelumnya.

Tambahkan dua baris ke grid dengan tinggi 50px.

 

Soal :

1. kelas kontainer harus memiliki properti baris-template-baris dengan dua unit 50px.

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
    grid-template-columns: 100px 100px 100px;
    /* add your code below this line */
    grid-template-rows: 50px 50px;
    
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


