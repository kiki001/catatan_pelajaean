## Gunakan Beberapa Operator Bersyarat \(Ternary\)

Dalam tantangan sebelumnya, Anda menggunakan satu`conditional operator`.Anda juga dapat menyatukan keduanya untuk memeriksa beberapa kondisi.

Fungsi berikut menggunakan pernyataan if, else if, and else untuk memeriksa beberapa kondisi:

```
function findGreaterOrEqual (a, b) { 
  if (a === b) { 
    return "a dan b adalah sama"; 
  } 
  lain jika (a> b) { 
    return "a is better"; 
  } 
  else { 
    return "b lebih besar"; 
  } 
}
```

Fungsi di atas dapat ditulis ulang menggunakan banyak`conditional operators`:

```
function findGreaterOrEqual (a, b) { 
  return (a === b)? "a dan b sama": (a> b)? "a lebih besar": "b lebih besar"; 
}
```

Gunakan beberapa conditional operatorsdi checkSignfungsi untuk memeriksa apakah nomor positif, negatif atau nol.



Soal :

1. checkSign harus menggunakan banyak conditional operators
2. checkSign\(10\)harus mengembalikan "positif". Perhatikan bahwa kapitalisasi penting
3. checkSign\(-12\)harus mengembalikan "negatif". Perhatikan bahwa kapitalisasi penting
4. checkSign\(0\)harus mengembalikan "nol". Perhatikan bahwa kapitalisasi penting

Jawaban :

```
function checkSign(num) {
    return (num === 0) ? "zero" : (num > 0) ? "positive" : "negative"; 
}

checkSign(10);
```



