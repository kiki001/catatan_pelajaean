## Iterate Through a Array with For Loop

Tugas umum dalam JavaScript adalah untuk mengulangi isi array.Salah satu cara untuk melakukannya adalah dengan`for`loop.Kode ini akan menampilkan setiap elemen array`arr`ke konsol:

```
var arr = [10,9,8,7,6]; 
untuk (var i = 0; i <arr.length; i ++) { 
   console.log (arr [i]); 
}
```

Ingat bahwa Array memiliki penomoran berbasis nol, yang berarti indeks terakhir array adalah panjang - 1.Kondisikamiuntuk loop ini adalah`i < arr.length`, yang berhenti ketika`i`panjangnya - 1.

Deklarasikan dan inisialisasi variabel`total`ke`0`.Gunakan`for`loop untuk menambahkan nilai setiap elemen`myArr`array`total`.

Soal :

1. total harus dideklarasikan dan diinisialisasi ke 0
2. total harus sama dengan 20
3. Anda harus menggunakan forperulangan untuk mengulangimyArr
4. Jangan diatur totalke 20 secara langsung

Jawaban :

```
// Example
var ourArr = [ 9, 10, 11, 12];
var ourTotal = 0;

for (var i = 0; i < ourArr.length; i++) {
  ourTotal += ourArr[i];
}

// Setup
var myArr = [ 2, 3, 4, 5, 6];
var total = 0;
// Only change code below this line

for (var i = 0; i < myArr.length; i++){
  total += myArr[i];
}
```



