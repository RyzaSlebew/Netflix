# Netflix

# Projek Akhir ASD

##
# Kelompok 4
  Anggota :
-	Raihan Yodistya (2209116053)
-	Kevin Aditya Agusto Awang (2209116101)
-	Muhammad Aidil Anugrah T (2209116102)
##

## Penjelasan Program
Program ini merupakan program Python yang terdiri dari beberapa fungsi untuk sebuah layanan menonton film. Ini menggunakan database online untuk menyimpan informasi tentang film, seperti id film, judul, tahun rilis, dan rating film. Program ini mencakup fungsi untuk login pengguna, menonton film untuk pengguna member VIP dan member biasa, serta fungsi penyortiran untuk mengurutkan film berdasarkan rating dan tahun. Program ini juga menampilkan daftar film yang tersedia untuk ditonton, serta detail filmnya
##

## Algoritma Pada Program
Program ini terdiri dari beberapa bagian untuk mengelola aplikasi streaming film, yaitu:

1. Mengimpor beberapa modul yang dibutuhkan, seperti PrettyTable untuk membuat tabel yang lebih bagus, Queue untuk mengantri pesan, serta mysql.connector dan pymysql untuk menghubungkan aplikasi dengan database Online.

2. Membuat kelas Node dan LinkedList untuk menyimpan data dalam bentuk linked list.

3. Membuat fungsi 'databaseakun()' untuk menghubungkan aplikasi dengan database Online pada layanan db4free.net.

4. Membuat fungsi 'login()' untuk mengatur proses login ke aplikasi. Fungsi ini akan meminta username dan password dari pengguna, kemudian mencocokannya dengan data yang ada di database. Jika username dan password cocok dengan data di database, pengguna akan diarahkan ke menu utama aplikasi. Jika gagal maka di minta ulang memasukkan username dan password nya dengan benar.

5. Membuat fungsi 'merge_sort()' dan 'shell_sort()' untuk mengurutkan data dalam bentuk list menggunakan algoritma merge sort dan shell sort.

6. Membuat fungsi 'filmvip()' dan 'filmbiasa()' untuk menampilkan film-film yang ada di database untuk akun VIP dan akun biasa, masing-masing. Fungsi ini akan mengambil data dari database dan menyimpannya dalam linked list. Kemudian, data akan ditampilkan dalam bentuk tabel menggunakan modul PrettyTable. Fungsi 'filmvip()' menggunakan metode pagination untuk memudahkan pengguna dalam melihat daftar film yang panjang, sedangkan fungsi 'filmbiasa()' menggunakan algoritma shell sort untuk mengurutkan film-film berdasarkan tahun.
##

## Tujuan Program 
Tujuan dibuatnya program Netflix tersebut adalah untuk memfasilitasi pengguna dalam menonton film secara online dengan menyediakan berbagai pilihan film dan fitur-fitur yang dapat mempermudah pengguna untuk menemukan dan menonton film yang diinginkan. Program ini juga memudahkan pengguna untuk memilih kategori film yang diinginkan, melihat informasi film seperti sinopsis dan rating, serta melihat daftar film yang telah ditonton sebelumnya. Selain itu, program ini juga menyediakan sistem akun VIP yang dapat memberikan akses khusus kepada pengguna yang telah berlangganan.
##

## Mamfaat Program 
Mamfaatnya adalah agar setiap orang dapat menonton film dimana saja tanpa harus keluar rumah atau pergi ke tempat nonton film pada umumnya. Jadi program ini dibuat supaya mempermudah para pengguna untuk menonton film yang di inginkan tanpa mengeluarkan budget dan tanpa menguras tenaga untuk keluar rumah.

## Fungsi Program
Program tersebut adalah sebuah program Python yang digunakan untuk menampilkan daftar film pada sebuah platform streaming. Program tersebut memiliki beberapa fungsi, yaitu:

1. Fungsi Node dan LinkedList: 
- Node dan LinkedList adalah struktur data yang digunakan untuk membuat linked list. Linked list sendiri adalah sebuah tipe data yang terdiri dari node-node yang saling terhubung dan masing-masing node memiliki data dan referensi ke node berikutnya.

2. Fungsi databaseakun:
- Fungsi ini digunakan untuk membuat koneksi ke sebuah database Online yang berisi informasi akun pengguna platform streaming.

3. Fungsi login:
- Fungsi ini digunakan untuk melakukan proses login pada platform streaming. Proses login dilakukan dengan meminta pengguna untuk memasukkan username dan password. Setelah itu, program akan melakukan query ke database untuk mencari apakah username dan password yang dimasukkan benar dan sesuai dengan akun VIP atau akun biasa.

4. Fungsi merge_sort:
- Fungsi ini adalah algoritma pengurutan merge sort yang digunakan untuk mengurutkan data dalam list.

5. Fungsi filmvip:
- Fungsi ini digunakan untuk menampilkan daftar film VIP yang tersedia pada platform streaming. Program akan menampilkan 5 film pada setiap halaman, dan pengguna dapat memilih halaman yang ingin ditampilkan.

6. Fungsi filmbiasa:
- Fungsi ini digunakan untuk menampilkan daftar film biasa yang tersedia pada platform streaming. Program akan menampilkan film-film tersebut dalam bentuk tabel yang diurutkan berdasarkan rating film.
