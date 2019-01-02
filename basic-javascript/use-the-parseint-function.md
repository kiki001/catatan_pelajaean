## Gunakan Fungsi parseInt

The`parseInt()`fungsi mem-parsing string dan mengembalikan integer.Ini sebuah contoh:

`var a = parseInt("007");`

Fungsi di atas mengubah string "007" menjadi bilangan bulat 7. Jika karakter pertama dalam string tidak dapat dikonversi menjadi angka, maka kembali`NaN`.



Gunakan`parseInt()`dalam`convertToInteger`fungsi sehingga mengubah string input`str`menjadi integer, dan mengembalikannya.



Soal :

1. convertToIntegerharus menggunakan parseInt\(\)fungsi
2. convertToInteger\("56"\) harus mengembalikan nomor
3. convertToInteger\("56"\) harus mengembalikan 56
4. convertToInteger\("77"\) harus mengembalikan 77
5. convertToInteger\("JamesBond"\) harus mengembalikan NaN

Jawaban :

```
function convertToInteger(str) {
  return parseInt(str);
}

convertToInteger("56");
```



