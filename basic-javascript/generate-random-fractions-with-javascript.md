## Hasilkan Pecahan Acak dengan JavaScript

Angka acak berguna untuk menciptakan perilaku acak.

JavaScript memiliki`Math.random()`fungsi yang menghasilkan angka desimal acak antara`0`\(inklusif\) dan tidak cukup hingga`1`\(eksklusif\).Dengan demikian`Math.random()`dapat mengembalikan`0`tetapi tidak pernah cukup mengembalikan a`1`

**Catatan**  
Seperti[Menyimpan Nilai dengan Equal Operator](https://learn.freecodecamp.org/storing-values-with-the-assignment-operator), semua panggilan fungsi akan diselesaikan sebelum`return`dieksekusi, jadi kita bisa`return`nilai`Math.random()`fungsi.



Ubah`randomFraction`untuk mengembalikan nomor acak alih-alih kembali`0`.



Soal :

1. randomFraction harus mengembalikan nomor acak.
2. Angka yang dikembalikan oleh randomFractionharus desimal.
3. Anda harus menggunakan Math.randomuntuk menghasilkan angka desimal acak.

Jawaban :

```
function randomFraction() {

  // Only change code below this line.

  return Math.random();

  // Only change code above this line.
}
```



