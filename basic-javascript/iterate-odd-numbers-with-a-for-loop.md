## Iterasi Angka Ganjil Dengan Loop Untuk

Untuk loop tidak harus mengulanginya satu per satu.Dengan mengubah kami`final-expression`, kami dapat menghitung dengan angka genap.

Kami akan mulai di`i = 0`dan loop sementara`i < 10`.Kami akan menambah`i`2 setiap loop dengan`i += 2`.

```
var ourArray = []; 
untuk (var i = 0; i <10; i + = 2) { 
  ourArray.push (i); 
}
```

`ourArray`sekarang akan berisi`[0,2,4,6,8]`.

Mari kita ubah`initialization`sehingga kita bisa menghitung dengan angka ganjil.

Dorong angka ganjil dari 1 hingga 9 untuk`myArray`menggunakan`for`loop



Soal :

1. Anda harus menggunakan forloop untuk ini.
2. myArrayharus sama \[1,3,5,7,9\].

Jawaban :

```
// Example
var ourArray = [];

for (var i = 0; i < 10; i += 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (var i = 1; i < 10; i+=2){
  myArray.push(i);
}

```



