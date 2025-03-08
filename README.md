 
 **Penyelesaian Tugas:**
 
 1. Menghitung luas persegi panjang 
 2. Menghitung diameter, keliling, dan luas lingkaran
 3. Menentukan sudut ketiga segitiga jika dua sudut diketahui
 4. Menghitung selisih antara dua tanggal dalam hari
 5. Menampilkan inisial nama dalam huruf besar
 
 ## 1. Menghitung luas persegi panjang 
 **kode**:
  ```
 const panjang = 5
 const lebar = 3
 const luasPersegiPanjang = panjang * lebar

 alert(`panjang: ${panjang} Di X lebar: ${lebar} maka hasilnya = ${luasPersegiPanjang}`)
  ```
 **Hasil:** 
 > 5 di X 3  maka hasilnya = 15
 
 ## 2. Menghitung diameter, keliling, dan luas lingkaran
 **kode:**
 ```
const r = 5
const d = 2 * r
const pi = 3.141592653589793
const keliling = pi * d
const luas_lingkaran = pi * r * r
const luas_lingkaran_bulat = Math.floor(luas_lingkaran * 1000) / 1000
 
alert (`Jari-jari: ${r}  Diameter: ${d}, Keliling: ${keliling}, Luas: ${luas_lingkaran_bulat}`)
 ```
 **Hasil:** 
 > Jari-jari: 5, Diameter: 10, Keliling: 31.4159 dan Luas: 78.539
 

 ## 3. Menentukan sudut ketiga segitiga jika dua sudut diketahui
 **kode:**
```
 let a = 80
 let b = 65
 let c = 180 - (a + b) =?
 
 const a = 80;
 const b = 65;
 const c = 180 - (a + b);
 
 alert (`Diketahui sudut: a = ${a}°, b = ${b}°  maka hasil Sudut ketiga adalah: ${c}°`)
```
 **Hasil:**
 > Diketahui sudut: a = 80°, b = 65° maka hasil Sudut ketiga adalah: 35°
 

 ## 4. Menghitung selisih antara dua tanggal dalam hari
 **kode:**
 ```
let tanggalPertama = first Date("2024-03-19");
let tanggalKedua = second Date("2024-03-21");

const selisih_waktu = tanggalKedua.getTime() - tanggalPertama.getTime();
const selisih_hari = Math.round(selisih_waktu / (1000 * 3600 * 24));

alert (`Selisih hari antara ${tanggalPertama.toDateString()} dan ${tanggalKedua.toDateString()} → ${selisih_hari} hari`);
 ```
 **Hasil:**
 
 > Selisih hari antara 19 Mar 2024 dan 21 Mar 2024 → adalah 2 hari
 
 ## 5. Menampilkan inisial nama dalam huruf besar
 **kode:**
 ```
 let nama = 'Null or 1'
if (nama ==Null) {nama = 'John Doe'} //"John Doe" adalah nama fiktif yang digunakan untuk merujuk pada seseorang yang identitasnya tidak diketahui atau dirahasiakan. Nama ini sering digunakan dalam kasus hukum, forensik, atau contoh umum dalam dokumen dan tutorial
else { nama = 'Achmad Choiri' }
(jika di atas diisi Null maka akan muncul nama John Doe tetapi jika diisi angka yang lain seperti angka 1 maka akan otomatis jadi Nama Achmad Choiri
alert (`nama inisial adalah ${nama}) 
```
**Output:**
 
 > Nama inisial : John Doe / Achmad Choiri
