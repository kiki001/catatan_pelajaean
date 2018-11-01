# Align Elements Menggunakan Properti align-items

Properti align-items mirip dengan justify-content. Ingat bahwa properti justify-content menyejajarkan item flex di sepanjang sumbu utama. Untuk baris, sumbu utama adalah garis horizontal dan untuk kolom adalah garis vertikal.

Wadah fleksibel juga memiliki sumbu silang yang merupakan kebalikan dari sumbu utama. Untuk baris, sumbu silang adalah vertikal dan untuk kolom, sumbu silang adalah horisontal.

CSS menawarkan properti align-items untuk menyelaraskan item flex sepanjang sumbu silang. Untuk berturut-turut, ia memberi tahu CSS cara mendorong item di seluruh baris ke atas atau ke bawah dalam penampung. Dan untuk kolom, cara mendorong semua barang ke kiri atau ke kanan di dalam wadah.

Nilai-nilai yang berbeda tersedia untuk menyelaraskan item termasuk:

* flex-start: meratakan item ke awal dari wadah fleksibel. Untuk baris, ini meratakan item ke bagian atas penampung. Untuk kolom, ini meluruskan item di sebelah kiri wadah.
* flex-end: meluruskan item ke ujung wadah flex. Untuk baris, ini meratakan item ke bagian bawah penampung. Untuk kolom, ini meratakan item di sebelah kanan penampung.
* center: menyelaraskan item ke pusat. Untuk baris, ini secara vertikal menyelaraskan item \(ruang yang sama di atas dan di bawah item\). Untuk kolom, ini secara horizontal meluruskannya \(ruang yang sama ke kiri dan kanan item\).
* peregangan: regangkan barang untuk mengisi wadah fleksibel. Misalnya, baris item direntangkan untuk mengisi wadah fleksibel dari atas ke bawah.
* baseline: menyelaraskan item ke baseline mereka. Baseline adalah konsep teks, anggap saja sebagai garis yang digunakan huruf-huruf.

---

Contoh membantu menunjukkan properti ini beraksi. Tambahkan properti CSS sejajar-item ke elemen \# kotak-kontainer, dan berikan nilai tengah.

Bonus

Coba opsi lain untuk properti align-items di editor kode untuk melihat perbedaannya. Tetapi perhatikan bahwa nilai pusat adalah satu-satunya yang akan melewati tantangan ini.



Soal :

1. Elemen \# kotak-kontainer harus memiliki properti item-sejajar yang disetel ke nilai tengah.

Jawaban :

```
<style>
  #box-container {
    background: gray;
    display: flex;
    height: 500px;
    align-items: center;
  }
  #box-1 {
    background-color: dodgerblue;
    width: 200px;
    font-size: 24px;
  }

  #box-2 {
    background-color: orangered;
    width: 200px;
    font-size: 18px;
  }
</style>

<div id="box-container">
  <div id="box-1"><p>Hello</p></div>
  <div id="box-2"><p>Goodbye</p></div>
</div>
```



