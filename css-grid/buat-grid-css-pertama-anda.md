# Buat Grid CSS Pertama Anda

gabungkan elemen HTML apa pun ke dalam penampung grid dengan menyetel properti tampilan ke kisi. Ini memberi Anda kemampuan untuk menggunakan semua properti lain yang terkait dengan CSS Grid.

Catatan

Dalam CSS Grid, elemen induk disebut sebagai wadah dan anak-anaknya disebut item.

Ubah tampilan div dengan kelas kontainer ke grid.



Soal :

1. kelas kontainer harus memiliki properti tampilan dengan nilai grid.

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
    /* add your code below this line */
    display: grid;
    
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



