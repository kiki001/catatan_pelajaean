Theoperator kondisional, juga disebutternary operator, dapat digunakan sebagai satu baris jika-lain ekspresi.

Sintaksnya adalah:

`condition ? statement-if-true : statement-if-false;`

Fungsi berikut menggunakan pernyataan if-else untuk memeriksa suatu kondisi:

```
function findGreater (a, b) { 
  if (a> b) { 
    return "a lebih besar"; 
  } 
  else { 
    return "b lebih besar"; 
  } 
}
```

Ini dapat ditulis ulang menggunakan`conditional operator`:

```
function findGreater (a, b) { 
  return a> b? "a lebih besar": "b lebih besar"; 
}
```

Gunakan conditional operatordalam checkEqualfungsi untuk memeriksa apakah dua nomor yang sama atau tidak. Fungsi harus mengembalikan benar atau salah.



Soal :

1. checkEqual harus menggunakan conditional operator
2. checkEqual\(1, 2\) harus mengembalikan false
3. checkEqual\(1, 1\) harus mengembalikan true
4. checkEqual\(1, -1\) harus mengembalikan false

Jawaban :

```
function checkEqual(a, b) {
  return a == b ? true : false;
}

checkEqual(1, 2);
```



