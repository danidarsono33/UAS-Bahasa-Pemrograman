# UAS-bahasa-Pemrograman

NAMA : DANI DARSONO

NIM : 312010189

KELAS : TI.20.B1

DOSEN : Agung Nugroho,S.Kom.,M.Kom

BAHASA PEMROGRAMAN

TEKNIK INFORMATIKA

UNIVERSITAS PELITA BANGSA


# SOAL UJIAN AKHIR SEMESTER (UAS)

Buat package dan modul dengan struktur

![1_Soal UAS](https://user-images.githubusercontent.com/73014427/105147892-59537200-5b34-11eb-9bcc-65ea97ae6152.png)

Untuk membuat Package Modul kita buka aplikasi PyCharm :

![2_New_File](https://user-images.githubusercontent.com/73014427/105147896-5b1d3580-5b34-11eb-9f5a-ec0f4b970fac.png)

 Pilih New Project Lalu simpan project sesuai Location Directory dan beri nama folder :
 
![3_New_File](https://user-images.githubusercontent.com/73014427/105147898-5bb5cc00-5b34-11eb-9b7e-7993b67db245.png)

 Kemudian Pilih New > Python Package :

 " -> Kita buat Nama Model dan View "

![4_New_File](https://user-images.githubusercontent.com/73014427/105147901-5bb5cc00-5b34-11eb-8b5c-e76d9e108dd7.png)


Tampilan Package folder Model dan View yang terdapat file_init_.py

![5_New_File](https://user-images.githubusercontent.com/73014427/105150371-47270300-5b37-11eb-9b07-2688faa0abd2.png)

Kemudian kita buat nama program Python dengan Klik Folder Model > pilih New >Python File dengan nama : daftar_nilai.py

![6_New_File](https://user-images.githubusercontent.com/73014427/105147905-5ce6f900-5b34-11eb-9707-4a2ea4617548.png)

Lalu kita buat nama program Python dengan Klik Folder view > pilih New >Python File dengan nama : input_nilai.py dan view_nilai.py

![7_New_File](https://user-images.githubusercontent.com/73014427/105147907-5d7f8f80-5b34-11eb-8cb9-2078a584715a.png)


Dan kita buat nama program Python dengan Klik di luar Folder > pilih New >Python File dengan nama : main.py

![8_New_File](https://user-images.githubusercontent.com/73014427/105148297-cff06f80-5b34-11eb-9a3d-c761684fb783.png)



Nama program python sudah kita buat :
Buat syntax program python
Membuat code program : daftar_nilai.py

![9_Daftar_Nilai](https://user-images.githubusercontent.com/73014427/105148298-d1219c80-5b34-11eb-971b-27616f38c59b.png)
![10_Daftar_Nilai](https://user-images.githubusercontent.com/73014427/105148304-d1ba3300-5b34-11eb-839a-c506dc29a3be.png)

Penjelasan :

Disini kita menggunakan dictionary ya untuk menyimpan inputan data mahasiswa
Def tambahkan : Dibagian ini kita gunakan print untuk penulisan bagian input data mahasiswa nanti agar terlihat rapih
Def hapus :
Disini kita buat inputan yang menginput nama
Gunanya untuk menghapus data mahasiswa dari nama mahasiswa itu sendiri
Kita gunakan del untuk fungsi menghapus datanya
(If)Jika mahasiswa tersebut ada maka data mahasiswa tersebut akan terhapus
(Else)Jika nama mahasiswa tersebut tidak ada maka datanya tidak akan ditemukan
Def ubah
Penjelasan:
Disini kita hampir sama dengan yang hapus, kita gunakan inputan nama untuk mengubah NIM, Nilai Tugas, Ujian Tengah Semester(UTS), ataupun Ujian Akhir Semester(UAS)
Lalu setelah kita memasukkan nama maka dictionary akan mengeksekusi program menggunakan keys untuk mencari data dari nama mahasiswa tersebut
(If)Jika nama mahasiswa tersebut ketemu atau ada didalam data maka program akan masuk ke inputan NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS yang baru
(Else)Jika nama mahasiswa tersebut tidak ada didalam data maka program akan memunculkan tulisan atau perintah bahwa data mahasiswa tidak ada
Def cari
Penjelasan:
Fungsinya sama dengan Def tambahkan
Membuat code program input_nilai.py

![11_Input_Nilai](https://user-images.githubusercontent.com/73014427/105148308-d252c980-5b34-11eb-86a3-41261574e587.png)


Penjelasan:

From dan import
Penjelasan:
From digunakan untuk memanggil package sementara import untuk tujuan yang kita pilih yaitu modul daftar_nilai

Lalu kita gunakan import data_mahasiswa itu gunanya agar saat kita menginputkan data atau setiap kali kita menambah data maka data mahasiswa secara otomatis akan masuk kedalam dictionary meskipun beda atau terpisah package dan juga modulnya

Def tambah data
Penjelasan:

Disini kita buat inputan karena tadi kita sudah membuat kata - kata outputnya kali ini kita cukup membuat inputan data mahasiswanya saja
Jangan lupa gunakan perkalian untuk menghitung hasil total atau rata- ratanya
Membuat code program view_nilai.py

![12_View_Nilai](https://user-images.githubusercontent.com/73014427/105148312-d383f680-5b34-11eb-9cf4-9539411fba15.png)
![13_view_2](https://user-images.githubusercontent.com/73014427/105148315-d41c8d00-5b34-11eb-99c1-b5b9b360c79d.png)

Penjelasan:

From dan import
Penjelasan:
Fungsinya sama saja dengan yang ada dibagian Input_Nilai

Def tampil
Penjelasan:

Disini kita buat sebuah tabel untuk menampilkan data - data dan nama - nama mahasiswa didalam dictionary
(If)Jika terdapat data maka data dan nama mahasiswa tersebut akan muncul
Disini kita menggunakan for untuk melakukan perulangan nomor urut
(Else)Jika kita belum menginputkan data sama sekali maka akan muncul tulisan "tidak ada data"
Def cari data
Penjelasan:

Tadi kita sudah buat print sama seperti dibagian Input_Nilai
Kita akan langsung membuat inputan dengan format nama untuk mencari data dari mahasiswa yang sedang kita cari
(If)Jika data mahasiswa yang dicari ada didalam dictionary maka data baik Nama, NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS akan muncul
(Else)Jika data mahasiswa yang dicari tidak ada didalam dictionary maka akan muncul tulisan "datanya tidak ada"
Membuat code program : main.py

![14_Input_Nilai](https://user-images.githubusercontent.com/73014427/105148318-d41c8d00-5b34-11eb-8d34-955b1dcd23a7.png)


From dan import
Penjelasan:
Sama seperti sebelumnya hanya saja disini sedikit berbeda

From disini kita tulis package.modulnya lalu import fungsi(def) tadi

Karena dibagian main ini kita akan menggunakan atau membuat syntax pilihan menu

While True
Penjelasan:

Kita gunakan print untuk membuat pilihan menunya
Lalu kita buat inputan untuk memilih menu nanti ketika program dijalankan
(If dan Elif)Kita gunakan karena kita akan membuat cabang pilihan yang banyak
Lalu dibawahnya kita tambahkan juga fungsi - fungsi yang sudah kita buat tadi
Pada perintah ke 6 kita gunakan break untuk keluar dari program yang kita jalankan
(Else)Jika kita tidak memilih salah satu menu tersebut maka akan muncul peringatan "pilih menu yang tersedia diatas"
Menjalankan program python
Untuk menjalankan program kita klik : Run > main.py

 Pilih Menu Nomor : 1. Tambah


![16_Output_1](https://user-images.githubusercontent.com/73014427/105148324-d5e65080-5b34-11eb-9545-9c61b5b2bd24.png)

 Pilih Menu Nomor : 2. Tampil
![17_Output_2](https://user-images.githubusercontent.com/73014427/105148329-d67ee700-5b34-11eb-9256-7432bf681430.png)


 Pilih Menu Nomor : 3. Hapus
![18_Output_3](https://user-images.githubusercontent.com/73014427/105148335-d7177d80-5b34-11eb-8640-d130fb711d84.png)


 Pilih Menu Nomor : 4. Ubah

![19_Output_4](https://user-images.githubusercontent.com/73014427/105148337-d7177d80-5b34-11eb-9c92-e02f3012a3d5.png)


 Pilih Menu Nomor : 5. Cari
Kemudian ketik Nama Mahasiswa

![20_Output_5](https://user-images.githubusercontent.com/73014427/105148338-d7b01400-5b34-11eb-954a-a01a545f1952.png)

 Pilih Menu Nomor : 6. Keluar dari program
 
![21_Output_6](https://user-images.githubusercontent.com/73014427/105148339-d848aa80-5b34-11eb-95e0-75a69721c1e5.png)


Untuk Melihat syntax - syntax program python yang sudah kita buat silahkan tekan Click Here:
Package modul(daftar_nilai) Click Here
Package View(input_nilai) Click Here dan view(view_nilai) Click Here
modul main Click Here
Cukup Sekian Penjelasan dari saya.

TERIMAKASIH


