## Koleksi Rekam

Anda diberi objek JSON yang mewakili bagian dari koleksi album musik Anda.Setiap album memiliki beberapa properti dan nomor id unik sebagai kuncinya.Tidak semua album memiliki informasi lengkap.

Tulis fungsi yang mengambil album`id`\(suka`2548`\), properti`prop`\(suka`"artist"`atau`"tracks"`\), dan`value`\(suka`"Addicted to Love"`\) untuk mengubah data dalam koleksi ini.

Jika`prop`tidak`"tracks"`dan`value`tidak kosong \(`""`\), perbarui atau setel`value`properti album rekaman itu.

Fungsi Anda harus selalu mengembalikan seluruh objek koleksi.

Ada beberapa aturan untuk menangani data yang tidak lengkap:

Jika`prop`adalah`"tracks"`namun album tidak memiliki`"tracks"`properti, membuat array kosong sebelum menambahkan nilai baru untuk properti yang sesuai album.

Jika`prop`ada`"tracks"`dan`value`tidak kosong \(`""`\), dorong`value`ke ujung`tracks`larikalbum yang ada.

Jika`value`kosong \(`""`\), hapus`prop`properti yangdiberikandari album.

**Petunjuk**  
Gunakan`bracket notation`saat[mengakses properti objek dengan variabel](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/accessing-object-properties-with-variables).

Push adalah metode array yang dapat Anda baca di[Jaringan Pengembang Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push).

Anda dapat merujuk kembali ke[Memanipulasi Objek Kompleks](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/manipulating-complex-objects)Memperkenalkan Notasi Objek JavaScript \(JSON\) untuk penyegaran.



Soal :

1. Setelah itu updateRecords\(5439, "artist", "ABBA"\), artistseharusnya"ABBA"
2. Setelah itu updateRecords\(5439, "tracks", "Take a Chance on Me"\), tracksharus ada "Take a Chance on Me"elemen terakhir.
3. Setelah itu updateRecords\(2548, "artist", ""\), artistjangan diatur
4. Setelah itu updateRecords\(1245, "tracks", "Addicted to Love"\), tracksharus ada "Addicted to Love"elemen terakhir.
5. Setelah itu updateRecords\(2468, "tracks", "Free"\), tracksharus ada "1999"elemen pertama.
6. Setelah itu updateRecords\(2548, "tracks", ""\), tracksjangan diatur
7. Setelah itu updateRecords\(1245, "album", "Riptide"\), albumseharusnya"Riptide"

Jawaban :

```
// Setup
var collection = {
    "2548": {
      "album": "Slippery When Wet",
      "artist": "Bon Jovi",
      "tracks": [ 
        "Let It Rock", 
        "You Give Love a Bad Name" 
      ]
    },
    "2468": {
      "album": "1999",
      "artist": "Prince",
      "tracks": [ 
        "1999", 
        "Little Red Corvette" 
      ]
    },
    "1245": {
      "artist": "Robert Palmer",
      "tracks": [ ]
    },
    "5439": {
      "album": "ABBA Gold"
    }
};
// Keep a copy of the collection for tests
var collectionCopy = JSON.parse(JSON.stringify(collection));

// Only change code below this line
function updateRecords(id, prop, value) {
  if (prop === "tracks" && value !== "") {
   if(collection[id][prop]) {
    collection[id][prop].push(value);
   }
   else {
    collection[id][prop]=[value];
   }
  } else if (value !== "") {
    collection[id][prop] = value;
  } else {
    delete collection[id][prop];
  }
  
  return collection;
}

// Alter values below to test your code
updateRecords(5439, "artist", "ABBA");

```



