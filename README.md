Array method di js
-------------------------------------------------------
(array.toString()) = digunakan untuk merubah semua array menjadi string
(array.join(penghubung))
let array = [1, 2, 3, "halo", false, true];
console.log(array.join()); // Output: 1,2,3,halo,false,true
console.log(array.join(" ")); // Output: 1 2 3 halo false true
console.log(array.join("#")); // Output: 1#2#3#halo#false#true

concat() digunakan untuk menggabungkan 2 array atau lebih.

pop(), mengeluarkan element terakhir dari sebuah array.
  
push(), menambah element di bagian akhir dari sebuah array.

reverse() akan mengurutkan element pada array dari index yang terbesar hingga index yang terkecil

shift(), mengeluarkan element pertama dari sebuah array.

sort() akan mengurutkan element di suatu array

unshift(), menambah element di bagian awal array.

let buah = ["Pisang", "Jeruk", "Apel", "Mangga"];

buah.splice(2, 0, "Lemon", "Kiwi");

console.log(buah); // Output: ["Pisang", "Jeruk", "Lemon", "Kiwi", "Apel", "Mangga"]
Penjelasan contoh di atas:

Parameter pertama bernilai 2, mendefinisikan posisi di mana element baru harus ditambahkan, yaitu di index ke 2 atau element ke 3 (ingat, index di array dimulai dari angka 0).
Parameter kedua bernilai 0, mendefinisikan jumlah element yang harus dihapus, yaitu berjumlah 0 (tidak ada yang dihapus).

----------------------------------------------------------------------------------------------------------------------------------------------
Objek Math (Math Object).

Math.sqrt(angka) Untuk menentukan akar pangkat bilangan



