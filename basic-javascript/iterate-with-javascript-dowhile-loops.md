## Iterate dengan JavaScript Do ... While Loops

Anda dapat menjalankan kode yang sama beberapa kali dengan menggunakan loop.

Jenis loop berikutnya yang akan Anda pelajari disebut "`do...while`" loop karena pertama-tama akan "`do`" melewati kode di dalam loop tidak peduli apa, dan kemudian dijalankan "`while`" suatu kondisi tertentu benar dan berhenti setelah kondisi itu tidak ada lagi benar.Mari kita lihat sebuah contoh.

```
var ourArray = []; 
var i = 0; 
do { 
  ourArray.push (i); 
  i ++; 
} while (i <5);
```

Ini berperilaku seperti yang Anda harapkan dengan jenis loop lainnya, dan array yang dihasilkan akan terlihat seperti`[0, 1, 2, 3, 4]`.Namun, apa yang membuat`do...while`perbedaan dari loop lain adalah bagaimana berperilaku ketika kondisi gagal pada pemeriksaan pertama.Mari kita lihat ini dalam aksi.

Berikut ini adalah loop sementara reguler yang akan menjalankan kode dalam loop selama`i < 5`.

```
var ourArray = []; 
var i = 5; 
while (i <5) { 
  ourArray.push (i); 
  i ++; 
}
```

Perhatikan bahwa kita menginisialisasi nilai`i`menjadi 5. Ketika kita mengeksekusi baris berikutnya, kita perhatikan bahwa`i`tidak kurang dari 5. Jadi kita tidak mengeksekusi kode di dalam loop.Hasilnya adalah bahwa`ourArray`akan berakhir dengan tidak ada yang ditambahkan ke dalamnya, sehingga akan tetap terlihat seperti ini`[]`ketika semua kode dalam contoh di atas selesai berjalan.

Sekarang, lihat satu`do...while`lingkaran.

```
var ourArray = []; 
var i = 5; 
do { 
  ourArray.push (i); 
  i ++; 
} while (i <5);
```

Dalam hal ini, kami menginisialisasi nilai`i`sebagai 5, seperti yang kami lakukan dengan loop sementara.Ketika kita sampai ke baris berikutnya, tidak ada pemeriksaan untuk nilai`i`, jadi kita pergi ke kode di dalam kurung kurawal dan menjalankannya.Kami akan menambahkan satu elemen ke array dan kenaikan`i`sebelum kita sampai ke pemeriksaan kondisi.Kemudian, ketika kita mulai memeriksa jika`i < 5`melihat bahwa`i`sekarang 6, yang gagal memeriksa bersyarat.Jadi kita keluar dari loop dan selesai.Pada akhir contoh di atas, nilai`ourArray`is`[5]`.

Pada dasarnya, sebuah`do...while`loop memastikan bahwa kode di dalam loop akan berjalan setidaknya satu kali.

Mari kita coba membuat`do...while`perulangan bekerja dengan mendorong nilai ke array.

Ubah`while`loop dalam kode menjadi`do...while`loop sehingga loop akan mendorong angka 10 ke`myArray`, dan`i`akan sama dengan`11`ketika kode Anda selesai berjalan.

Soal :

1. Anda harus menggunakan do...whileloop untuk ini.
2. myArrayharus sama \[10\].
3. i harus sama 11 

Jawaban :

```
// Setup
var myArray = [];
var i = 10;

// Only change code below this line.
do {
  myArray.push(i);
  i++;
} while (i < 11)
```



