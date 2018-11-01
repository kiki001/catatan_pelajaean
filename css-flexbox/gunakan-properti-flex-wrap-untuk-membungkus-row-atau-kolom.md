# Gunakan Properti flex-wrap untuk Membungkus Row atau Kolom

Namun, menggunakan properti flex-wrap, itu memberitahu CSS untuk membungkus item. Ini berarti item tambahan pindah ke baris atau kolom baru. Titik istirahat dimana pembungkus terjadi tergantung pada ukuran barang dan ukuran wadah.

CSS juga memiliki opsi untuk arah pembungkusan:

* nowrap: ini adalah pengaturan default, dan tidak membungkus item.

* wrap: membungkus item dari kiri ke kanan jika mereka berurutan, atau dari atas ke bawah jika mereka berada dalam kolom.

* wrap-reverse: membungkus barang dari bawah ke atas jika mereka berturut-turut, atau kanan-ke-kiri jika mereka berada di kolom.
  ---

Tata letak saat ini memiliki terlalu banyak kotak untuk satu baris. Tambahkan properti CSS flex-wrap ke elemen \# box-container, dan beri nilai bungkus.

Soal :

1. Elemen \# box-container harus memiliki properti flex-wrap yang disetel ke nilai wrap.

Jawaban :

```
<style>
  #box-container {
    background: gray;
    display: flex;
    height: 100%;
    flex-wrap: wrap;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 25%;
    height: 50%;
  }

  #box-2 {
    background-color: orangered;
    width: 25%;
    height: 50%;
  }
  #box-3 {
    background-color: violet;
    width: 25%;
    height: 50%;
  }
  #box-4 {
    background-color: yellow;
    width: 25%;
    height: 50%;
  }
  #box-5 {
    background-color: green;
    width: 25%;
    height: 50%;
  }
  #box-6 {
    background-color: black;
    width: 25%;
    height: 50%;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
  <div id="box-3"></div>
  <div id="box-4"></div>
  <div id="box-5"></div>
  <div id="box-6"></div>
</div>
```





