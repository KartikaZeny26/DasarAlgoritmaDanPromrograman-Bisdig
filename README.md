STUDI KASUS 1: Faktorial Menggunakan Rekursi
fungsi adalah blok kode terpisah yang digunakan untuk melakukan tugas tertentu. fungsi membantu:
Modularitas: memecah program menjadi bagian-bagian kecil yang mudah dikelola.
Reusabilitas: fungsi dapat dipanggil berulang kali dari mana saja dalam program.
Abstraksi: menyambungkan detail implementasi, sehingga kita bisa fokus pada apa yang dilakukan
Rekursi adalah teknik programan dimana sebuah fungsi memanggil dirinya sendiri. Dalam faktorial, n! = n * (n-1)!, sehingga bisa dihitung dengan memanggila fungsi itu sendiri dengan nilai yang lebih kecil sampai n = 1.

STUDI KASUS 2: Input Nilai dan Mencari Nilai Tertinggi
Perulangan yaitu memungkinkan kita mengeksekusi blok kode berulang kali. Dalam kasus ini, kita ingin menerima input nilai 5 siswa - menggunakan for loop agara efesien.
List/Array adalah struktur data di Python yang dapat menyimpan sekumpulan nilai dalam satu variabel. kita menyimpan seluruh nilai siswa dalam list agar bisa dianalisis (misalnya dengan max() untuk memcari nilai tertinggi).

STUDI KASUS 3: Diskon pada Sistem E-Commerce
Struktur Kontrol Percabangan (if,else) digunakan untuk membuat keputusan berdasarkan suatu kondisi.
Dalam kasus ini: Jika total belanja > 500.000, maka pelanggan mendapat diskon 10%.
Logika Diskon:
jika total belanja lebih dari 500.000:
total_bayar = total_belanja * 0.9
jika tidak:
total_bayar = total_belanja
