## operating system used
* [WINDOWS 11]

## latihan 1
![latihan1 pertemuan6](https://github.com/nurulaisyah14/praktikum3/assets/148174512/c197427d-f992-4f85-a8c2-857d810e9d7b)
![run latihan1 pertemuan6](https://github.com/nurulaisyah14/praktikum3/assets/148174512/a8007f2f-3f11-44b5-9ac7-884d54d78382)
* Berikut adalah langkah-langkah dari kode tersebut:
- Bagian pertama menggunakan parameter end pada fungsi print() untuk menentukan karakter yang akan digunakan sebagai akhir baris. Pada contoh kode tersebut, karakter akhir baris diubah dari karakter newline (\n) menjadi spasi (' '). Oleh karena itu, setelah karakter 'A' dicetak, karakter 'B' dan 'C' dicetak pada baris yang sama dengan karakter spasi di antara keduanya. Setelah itu, fungsi print() dipanggil tanpa argumen, sehingga mencetak karakter newline dan membuat baris baru. Kemudian, karakter 'X', 'Y', dan 'Z' dicetak pada baris yang berbeda.
- Bagian kedua menggunakan parameter sep pada fungsi print() untuk menentukan karakter yang akan digunakan sebagai pemisah antara argumen. Pada contoh kode tersebut, empat variabel w, x, y, dan z dicetak dengan beberapa nilai sep yang berbeda. Pada contoh pertama, argumen dicetak dengan spasi sebagai pemisah. Pada contoh kedua, argumen dicetak dengan koma sebagai pemisah. Pada contoh ketiga, argumen dicetak tanpa pemisah. Pada contoh keempat, argumen dicetak dengan titik dua sebagai pemisah. Pada contoh kelima, argumen dicetak dengan karakter pemisah yang tidak biasa.
- Bagian ketiga menggunakan format string untuk mencetak nilai pangkat 10 dari bilangan bulat dari 0 hingga 10. Pada contoh pertama, nilai pangkat 10 dari 0 dicetak. Pada contoh kedua, nilai pangkat 10 dari 1 dicetak, dan seterusnya hingga nilai pangkat 10 dari 10 dicetak. Pada contoh keempat, format string digunakan untuk mencetak nilai pangkat 10 dengan lebar kolom 3 dan 16, masing-masing. Angka 0 hingga 10 dicetak dengan format ini.
Kode tersebut dapat digunakan untuk mempelajari penggunaan parameter end dan sep pada fungsi print(), serta penggunaan format string pada Python.

## latihan 2
![latihan2 run pertemuan6](https://github.com/nurulaisyah14/praktikum3/assets/148174512/f137229a-08cc-45f3-800d-68521e89ffd5)
* Berikut adalah langkah-langkah dari kode tersebut:
- Pertama memasukkan nilai a dan b menggunakan fungsi input().
- Selanjutnya mencetak nilai a dan b menggunakan fungsi print().
- Ketiga menggabungkan nilai a dan b menggunakan format string dan mencetak hasilnya.
- Keempat mengonversi nilai a dan b menjadi bilangan bulat menggunakan fungsi int().
- Kemudian melakukan operasi penjumlahan pada nilai a dan b, dan mencetak hasilnya menggunakan format string.
- Setelah itu melakukan operasi pembagian pada nilai a dan b, dan mencetak hasilnya menggunakan format string.

## latihan 3
![latihan3 pertemuan6](https://github.com/nurulaisyah14/praktikum3/assets/148174512/24ed907a-84ce-4d82-9438-5db6d8c1fb8b)
![run latihan3 pertemuan6](https://github.com/nurulaisyah14/praktikum3/assets/148174512/ce1c6d54-b458-4b4b-992f-67d0353f4f7c)
* Berikut adalah langkah-langkah dari kode tersebut:
- Langkah awal mencetak judul program dan garis pemisah menggunakan fungsi print().
- Selanjutnya meminta pengguna untuk memasukkan lebar belah ketupat menggunakan fungsi input().
- Kemudian melakukan loop for untuk mencetak setengah bagian atas dari belah ketupat. Loop ini mencetak spasi sebanyak lebar_belah_ketupat - i diikuti dengan bintang sebanyak i + 1 pada setiap baris.
- Setelah itu melakukan loop for untuk mencetak setengah bagian bawah dari belah ketupat. Loop ini mencetak spasi sebanyak i + 1 diikuti dengan bintang sebanyak lebar_belah_ketupat - i pada setiap baris.
  
## flowchart
![coding flowchrt prtmuan6](https://github.com/nurulaisyah14/praktikum3/assets/148174512/75aeebec-de76-4b0c-88b6-cb250d25b3fe)
* Berikut adalah langkah-langkah dari kode tersebut:
- Pertama program meminta pengguna untuk memasukkan jari-jari lingkaran menggunakan fungsi input().
- Selanjutnya menghitung luas lingkaran dengan menggunakan rumus pi * r * r, di mana pi adalah konstanta matematika dan r adalah jari-jari lingkaran yang dimasukkan oleh pengguna. Program menggunakan nilai 22/7 sebagai nilai pi.
- Kemudian menghitung keliling lingkaran dengan menggunakan rumus 2 * pi * r, di mana pi adalah konstanta matematika dan r adalah jari-jari lingkaran yang dimasukkan oleh pengguna. Program menggunakan nilai 22/7 sebagai nilai pi.
- Setelah itu mencetak luas dan keliling lingkaran menggunakan fungsi print().

## command
- git add dapat digunakan secara spesifik untuk file tertentu atau direktori, memberikan Anda fleksibilitas untuk memilih perubahan mana yang akan dimasukkan dalam staging area.
- git commit -m “hi” Untuk menyimpan perubahan yang ada kedalam database repository local
- git remote add origin (https://github.com/nurulaisyah14/praktikum3.git) Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
- git push -u origin master/main Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
- git clone [url] Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).
