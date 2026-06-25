# 🧠 Penjelasan Array
<p align="justify">
Array pada JavaScript adalah struktur data yang digunakan untuk menyimpan sekumpulan nilai dalam satu variabel, dengan urutan tertentu dan indeks yang dimulai dari 0. Jadi, alih-alih membuat banyak variabel untuk setiap data, kita bisa mengelompokkan semuanya dalam satu array.
</p>

---

- **Karakteristik Array:** 📎
```
 	- Kumpulan data: Bisa berisi banyak nilai sekaligus.
 	- Indeks: Elemen pertama berada di indeks 0, elemen kedua di 1, dan seterusnya.
 	- Dinamis: Ukuran array bisa bertambah atau berkurang sesuai kebutuhan.
 	- Heterogen: Bisa menyimpan berbagai tipe data (string, number, object, bahkan array lain).
 	- Terurut: Data disusun berdasarkan urutan indeks.
```

---

### 📌 Method Pada Array

- **Menambah & Menghapus Elemen** 📎
    ```
   	- push() → menambah elemen di akhir array.
   	- pop() → menghapus elemen terakhir.
   	- unshift() → menambah elemen di awal array.
   	- shift() → menghapus elemen pertama.
   	- splice() → menambah, menghapus, atau mengganti elemen di posisi tertentu.
   	- slice() → menyalin sebagian array (tidak mengubah array asli).
    ```

- **Mencari & Mengecek Elemen** 📎
    ```
   	- indexOf() → mencari indeks pertama dari elemen tertentu.
   	- lastIndexOf() → mencari indeks terakhir dari elemen tertentu.
   	- includes() → mengecek apakah elemen ada di array.
   	- find() → mengembalikan elemen pertama yang cocok dengan kondisi.
   	- findIndex() → mengembalikan indeks dari elemen yang cocok.
   	- every → mengecek apakah semua elemen benar bernilai true dan false jika ada satu yang salah.
   	- some → mengecek apakah ada satu elemen benar bernilai true dan false jika semua elemen salah.
    ```
    
- **Transformasi & Iterasi** 📎
    ```
   	- map() → membuat array baru dengan hasil transformasi tiap elemen.
   	- forEach() → menjalankan fungsi untuk setiap elemen (tidak menghasilkan array baru).
   	- filter() → membuat array baru berisi elemen yang lolos kondisi.
   	- reduce() → menggabungkan semua elemen menjadi satu nilai (misalnya jumlah total).
   	- sort() → mengurutkan elemen.
   	- reverse() → membalik urutan elemen.
    ```
    
- **Utility & Lainnya** 📎
    ```
   	- concat() → menggabungkan dua atau lebih array.
   	- join() → menggabungkan elemen menjadi string dengan separator tertentu.
   	- flat() → meratakan array bersarang (nested array).
   	- isArray() → mengecek apakah suatu variabel adalah array.
   	- toString() → mengubah array menjadi string.
    ```
