# Gunakan Properti yang tumbuh secara fleksibel untuk Memperluas Item

Kebalikan dari flex-shrink adalah properti yang tumbuh secara fleksibel. Ingat bahwa penyusutan-fleksibel mengecilkan ukuran item ketika wadah menyusut. Properti yang tumbuh secara fleksibel mengontrol ukuran item ketika kontainer induk mengembang.

Menggunakan contoh serupa dari tantangan terakhir, jika satu item memiliki nilai pertumbuhan fleksibel 1 dan yang lainnya memiliki nilai pertumbuhan fleksibel sebesar 3, nilai satu dengan nilai 3 akan tumbuh tiga kali lebih banyak dari yang lain.

Tambahkan properti CSS dengan flex-grow ke \# box-1 dan \# box-2. Beri \# kotak-1 nilai 1 dan \# kotak-2 nilai 2.



Soal :

1. Elemen \# box-1 harus memiliki properti yang dikembangkan secara fleksibel yang ditetapkan ke nilai 1.
2. Elemen \# box-2 harus memiliki properti yang dikembangkan secara fleksibel ke nilai 2.

Jawaban :

```
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  
  #box-1 {
    background-color: dodgerblue;
    height: 200px;
    flex-grow: 1;
  }
  
  #box-2 {
    background-color: orangered;
    height: 200px;
    flex-grow: 2;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



