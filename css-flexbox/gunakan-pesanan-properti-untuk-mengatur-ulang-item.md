# Gunakan pesanan Properti untuk Mengatur Ulang Item

Properti pesanan digunakan untuk memberi tahu CSS urutan bagaimana item flex muncul dalam wadah fleksibel. Secara default, item akan muncul dalam urutan yang sama seperti yang ada di sumber HTML. Properti mengambil angka sebagai nilai, dan angka negatif dapat digunakan.

Tambahkan urutan properti CSS ke \# box-1 dan \# box-2. Beri \# kotak-1 nilai 2 dan beri \# kotak-2 nilai 1.



Soal :

1. Elemen \# box-1 harus memiliki properti pesanan yang disetel ke nilai 2.
2. Elemen \# box-2 harus memiliki properti pesanan yang disetel ke nilai 1.

Jawaban :

```
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    order: 2;
    height: 200px;
    width: 200px;
  }

  #box-2 {
    background-color: orangered;
    order: 1;
    height: 200px;
    width: 200px;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



