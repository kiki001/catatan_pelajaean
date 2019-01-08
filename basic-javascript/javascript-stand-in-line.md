## Stand in Line

Dalam Ilmu Komputer,antrianadalahStruktur Dataabstraktempat item disimpan secara berurutan.Item baru dapat ditambahkan di bagian belakang`queue`dan item lama dilepas dari depan`queue`.

Tulis fungsi`nextInLine`yang menggunakan array \(`arr`\) dan number \(`item`\) sebagai argumen.

Tambahkan nomor ke akhir array, lalu hapus elemen pertama array.

The`nextInLine`fungsi maka harus kembali elemen yang telah dihapus.

Soal :

1. nextInLine\(\[ \], 5\) harus mengembalikan nomor.
2. nextInLine\(\[ \], 1\) harus kembali 1
3. nextInLine\(\[2\], 1\) harus kembali 2
4. nextInLine\(\[5,6,7,8,9\], 1\) harus kembali 5
5. Setelah itu nextInLine\(testArr, 10\), testArr\[4\]seharusnya10 

Jawaban :

```
function nextInLine(arr, item) {
  // Your code here
  arr.push(item);
  var item = arr.shift();
  return item;  // Change this line
}

// Test Setup
var testArr = [1,2,3,4,5];

// Display Code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 6)); // Modify this line to test
console.log("After: " + JSON.stringify(testArr));
```



