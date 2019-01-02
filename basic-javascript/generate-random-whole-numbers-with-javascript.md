## Menghasilkan Angka Utuh Acak dengan JavaScript

Sangat bagus bahwa kita dapat menghasilkan angka desimal acak, tetapi bahkan lebih berguna jika kita menggunakannya untuk menghasilkan angka bulat acak.

1. Gunakan`Math.random()`untuk menghasilkan desimal acak.
2. Kalikan desimal acak itu dengan`20`.
3. Gunakan fungsi lain,`Math.floor()`untuk membulatkan angka ke bilangan bulat terdekat.

Ingatlah bahwa`Math.random()`tidak pernah bisa mengembalikan a`1`dan, karena kita membulatkannya, tidak mungkin untuk benar-benar mendapatkannya`20`.Teknik ini akan memberi kita seluruh angka antara`0`dan`19`.

Menyatukan semuanya, seperti inilah kode kami:

`Math.floor(Math.random() * 20);`

Kami memanggil`Math.random()`, mengalikan hasilnya dengan 20, lalu meneruskan nilai`Math.floor()`berfungsi untuk membulatkan nilai ke seluruh nomor terdekat.



Gunakan teknik ini untuk menghasilkan dan mengembalikan bilangan bulat acak antara`0`dan`9`.

Soal :

1. Hasilnya randomWholeNumharus bilangan bulat.
2. Anda harus menggunakan Math.randomuntuk menghasilkan angka acak.
3. Anda harus mengalikan hasil Math.randomdengan 10 untuk menjadikannya angka antara nol dan sembilan.
4. Anda harus menggunakan Math.flooruntuk menghapus bagian desimal dari angka tersebut.

Jawaban :

```
var randomNumberBetween0and19 = Math.floor(Math.random() * 20);

function randomWholeNum() {

  // Only change code below this line.

  return Math.floor( Math.random() * 10);
}
```



