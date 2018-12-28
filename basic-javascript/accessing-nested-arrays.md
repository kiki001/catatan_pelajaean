## Mengakses Arang Bersarang

Seperti yang telah kita lihat dalam contoh sebelumnya, objek dapat berisi objek bersarang dan array bersarang.Mirip dengan mengakses objek bersarang, notasi braket array dapat dirantai untuk mengakses array bersarang.

Berikut adalah contoh cara mengakses array bersarang:

```
var ourPets = [
  {
    animalType: "cat",
    names: [
      "Meowzer",
      "Fluffy",
      "Kit-Cat"
    ]
  },
  {
    animalType: "dog",
    names: [
      "Spot",
      "Bowser",
      "Frankie"
    ]
  }
];
ourPets[0].names[1]; // "Fluffy"
ourPets[1].names[0]; // "Spot"
```

Ambil pohon kedua dari variabel myPlants menggunakan objek dot dan notasi braket array.

Soal :

1. secondTree should equal "pine"
2. Use dot and bracket notation to access myPlants

Jawaban :

```
// Setup
var myPlants = [
  { 
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }  
];

// Only change code below this line

var secondTree = myPlants[1].list[1]; // Change this line

```



