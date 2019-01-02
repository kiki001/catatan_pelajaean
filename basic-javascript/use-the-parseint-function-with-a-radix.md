## Gunakan Fungsi parseInt dengan Radix

The`parseInt()`fungsi mem-parsing string dan mengembalikan integer.Dibutuhkan argumen kedua untuk radix, yang menentukan basis nomor dalam string.Radix dapat berupa bilangan bulat antara 2 dan 36.

Panggilan fungsi terlihat seperti:

`parseInt(string, radix);`

Dan ini sebuah contoh:

`var a = parseInt("11", 2);`

Variabel radix mengatakan bahwa "11" ada dalam sistem biner, atau basis 2. Contoh ini mengubah string "11" menjadi bilangan bulat 3.



Gunakan`parseInt()`dalam`convertToInteger`fungsi sehingga mengkonversi angka biner ke integer dan mengembalikannya.



Soal :

1. convertToIntegerharus menggunakan parseInt\(\)fungsi
2. convertToInteger\("10011"\) harus mengembalikan nomor
3. convertToInteger\("10011"\) harus mengembalikan 19
4. convertToInteger\("111001"\) harus mengembalikan 57
5. convertToInteger\("JamesBond"\) harus mengembalikan NaN

Jawaban :

```
function convertToInteger(str) {
  return parseInt(str, 2)
}

convertToInteger("10011");
```



