# Gunakan Properti rileks-menyusutkan ke Shrink Items

Yang pertama adalah properti flex-shrink. Ketika digunakan, itu memungkinkan item menyusut jika wadah fleksibel terlalu kecil. Item menyusut ketika lebar wadah induk lebih kecil dari lebar gabungan semua item flex di dalamnya.

Properti flex-shrink mengambil angka sebagai nilai. Semakin tinggi angkanya, semakin banyak yang menyusut dibandingkan dengan barang-barang lainnya dalam wadah. Sebagai contoh, jika satu item memiliki nilai flex-shrink 1 dan yang lainnya memiliki nilai flex-shrink 3, yang satu dengan nilai 3 akan menyusut tiga kali lebih banyak dari yang lain.

---

Tambahkan properti CSS dengan flex-shrink ke \# box-1 dan \# box-2. Beri \# kotak-1 nilai 1 dan \# kotak-2 nilai 2.

Soal :

1. Elemen \# box-1 harus memiliki properti setel-set-fleksibel ke nilai 1.
2. Elemen \# box-2 harus memiliki properti setel-set-fleksibel ke nilai 2.

Jawaban :

```
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 100%;
    height: 200px;
    
  }

  #box-2 {
    background-color: orangered;
    width: 100%;
    height: 200px;
    flex-shrink: 2;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



