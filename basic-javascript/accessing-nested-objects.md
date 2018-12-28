## Mengakses Objek Bersarang

Sub-properti objek dapat diakses dengan merantai notasi titik atau braket.

Ini adalah objek bersarang:



```

```

Akses myStorage objek dan tetapkan konten glove box properti ke gloveBoxContents variabel. Gunakan notasi braket untuk properti dengan spasi di namanya.

soal :

1. gloveBoxContents should equal "maps"
2. Use dot and bracket notation to access myStorage

Jawaban :

```
// Setup
var myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};

var gloveBoxContents = myStorage.car.inside["glove box"]; // Change this line
```



