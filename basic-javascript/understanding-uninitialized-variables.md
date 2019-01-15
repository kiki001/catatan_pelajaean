## Memahami Variabel yang tidak diinisialisasi

Ketika variabel JavaScript dideklarasikan, mereka memiliki nilai awal`undefined`.Jika Anda melakukan operasi matematika pada suatu`undefined`variabel, hasil Anda akan menjadi`NaN`yang berarti"Bukan Angka".Jika Anda menggabungkan string dengan`undefined`variabel, Anda akan mendapatkan literalstring yangdari`"undefined"`.

Menginisialisasi tiga variabel`a`,`b`dan`c`dengan`5`,`10`, dan`"I am a"`masing-masing sehingga mereka tidak akan`undefined`.



Soal :

1. a harus didefinisikan dan dievaluasi untuk memiliki nilai 6
2. b harus didefinisikan dan dievaluasi untuk memiliki nilai 15
3. cseharusnya tidak mengandung undefineddan harus memiliki nilai "I am a String!"
4. Jangan mengubah kode di bawah garis

Jawaban :

```
// Initialize these three variables
var a = 5;
var b = 10;
var c = "I am a";

// Do not change code below this line

a = a + 1;
b = b + 5;
c = c + " String!";
```



