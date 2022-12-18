Nama    : Zidna Soleda Zulfa

NIM     : 312210031

#                         Contoh dan Penjelasan Modul Praktikum Pertemuan ke-13

1. Berikut adalah fungsi yang mengubah suhu dari derajat derajat Kelvin menjadi derajat Fahrenheit. Karena nol derajat derajat Kelvin sedingin yang didapat, fungsi tersebut ditebus jika melihat suhu negatif.

![image](https://user-images.githubusercontent.com/115474076/208300776-7b29e4bc-7bd3-41b6-a4dc-f43761597471.png)

Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback... artinya terjadi error pada pernyataan assert.AssertionError

2. Contoh ini untuk membuka file, menulis konten di file dan keluar dengan lancar karena tidak ada masalah sama sekali.

![image](https://user-images.githubusercontent.com/115474076/208300807-60e6fd03-c9eb-476f-bbbb-16ab87fe8d21.png)

- Hasilnya :

![image](https://user-images.githubusercontent.com/115474076/208300837-8eda2092-fb4e-4c5e-b0ed-b92be3aea395.png)

Hasilnya seperti ini karena else akan dijalankan ketika try adalah True

3. Contoh ini mencoba membuka file di mana Anda tidak memiliki izin menulis, sehingga menimbulkan pengecualian.

![image](https://user-images.githubusercontent.com/115474076/208300881-22532720-c7a8-4f81-8488-128ed773bb0a.png)

- Mengapa hasilnya error?

r adalah read - Membuka file untuk membaca, akan error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya tambahkan dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan.fh = open("testfile", "r")print(fh.readline())

4. Contoh keempat

![image](https://user-images.githubusercontent.com/115474076/208300938-69d08176-f216-47d3-a4c6-b78e826a80f9.png)

Hasil diatas bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan.

5. Contoh single exception

![image](https://user-images.githubusercontent.com/115474076/208300986-b23d361b-e4ad-4b6d-bdea-1745e773ce06.png)

- Hasilnya : 

![image](https://user-images.githubusercontent.com/115474076/208301047-90910728-3d51-4310-9155-26f0022a8f36.png)

ketika dijalankan, maka muncul error. Hapus dan di ganti koma dengan as seperti agar tidak error. Jika dijalankan akan muncul error lagi. Kenapa? karena parameter def temp_convert harus mengandung angka.#!/usr/bin/pythonexcept ValueError, Argument:except ValueError as Argument:

6. Contoh dan penjelasan keenam

![image](https://user-images.githubusercontent.com/115474076/208301092-0a5f46b0-f194-4879-802b-c0af2eb7fa6c.png)

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1."Invalid level!", level

Selesai
