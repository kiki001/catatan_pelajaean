# Gunakan Properti yang sejajar

Properti akhir untuk item flex adalah sejajar-diri. Properti ini memungkinkan Anda menyesuaikan keselarasan masing-masing item secara individual, alih-alih mengatur semuanya sekaligus. Ini berguna karena teknik penyesuaian umum lainnya menggunakan properti CSS float, clear, dan vertical-align tidak berfungsi pada item flex.

align-self menerima nilai yang sama dengan align-items dan akan mengesampingkan nilai apa pun yang ditetapkan oleh properti align-items.

Tambahkan properti CSS sejajarkan ke \# box-1 dan \# box-2. Beri \# kotak-1 nilai tengah dan beri \# kotak-2 nilai flex-end.



Soal :

1. Elemen \# kotak-1 harus memiliki properti yang disetel sendiri ke nilai pusat.
2. Elemen \# box-2 harus memiliki properti align-self yang disetel ke nilai flex-end.

Jawaban :

```
<style>
  #box-container {
    display: flex;
    height: 500px;
  }
  #box-1 {
    background-color: dodgerblue;
    align-self: center;
    height: 200px;
    width: 200px;
  }

  #box-2 {
    background-color: orangered;
    align-self: flex-end;
    height: 200px;
    width: 200px;
  }
</style>

<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```



