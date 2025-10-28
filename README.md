# Nama : Ahmad septa argya putra
# Nim : 362458302017
# Kelas : TRPL 2B

# A. Tujuan praktikum
-	Memahami konsep dasar API
-	Melakukan operasi CRUD terhadap data melalui API
-	Mengimplementasikan styling dasar pada komponen UI untuk 
# B. Dasar Teori (Penjelasan singkat tentang API, REST, JSON, http pakcage)
-	API merupakan seperangkat aturan protokol yang memungkinkan dua aplikasi perangkat lunak yang berbeda untuk saling berkomunikasi
-	REST merupakan gaya arsitektur untuk merancang API yang menggunakan protokol standar seperti HTTP
-	JSON merupakan format teks ringan yang digunakan untuk menyimpan dan mengirimkan data
-	HTTP pakcage merupakan pustaka (library) perangkat lunak yang menyediakan fungsionalitas untuk beekerja dengan protokol HTTP
# C.	Langkah langkah implementasi
1.	Menambahkan pakcage HTTP ke dalam pubspec.yaml
   <img width="414" height="123" alt="image" src="https://github.com/user-attachments/assets/77b6df06-6434-4e40-b4a2-8ca92ae7fe62" />

2.	Lalu menjalankan (flutter pub get)
   <img width="525" height="438" alt="image" src="https://github.com/user-attachments/assets/e6ebd9b8-41f1-4ce9-b1bb-e579de99812e" />

3.	Membuat file “user_model.dart” didalam folder lib
   <img width="675" height="720" alt="image" src="https://github.com/user-attachments/assets/07c4b921-d6c9-4af1-9986-c8f92524edb7" />

4.	Membuat file “api_service.dart” didalam folder lib
   <img width="675" height="640" alt="image" src="https://github.com/user-attachments/assets/439a4ffb-d912-45ef-8e2c-59c093b145db" />

5.	Memodifikasi main.dart ganti sesuai dengan modul
   <img width="675" height="1287" alt="image" src="https://github.com/user-attachments/assets/bdfa2c67-037e-4d2f-a924-7f60754cf1ad" />

6.	Menambahkan method createUser di file api_service.dart
    <img width="675" height="483" alt="image" src="https://github.com/user-attachments/assets/f5219284-8a49-4434-9bf0-fcd6cd8594a0" />

7.	Membuat halaman tambah user, buat file “add_user_page.dart”
    <img width="675" height="588" alt="image" src="https://github.com/user-attachments/assets/4d134a64-4dcd-41b5-a108-b64e42f62b39" />

8.	Implementasi request update
    <img width="675" height="518" alt="image" src="https://github.com/user-attachments/assets/616b37f1-dd90-4abb-acf4-fc2a9941e3ca" />

9.	Implementasi request delete
    <img width="675" height="375" alt="image" src="https://github.com/user-attachments/assets/a9e125c7-b702-4080-8d0d-121eb0bb1a70" />

# D.	Analisi kode (Penjelasan bagian penting dari kode yang telah dibuat)
1. <img width="299" height="37" alt="image" src="https://github.com/user-attachments/assets/1163a272-3f9a-4767-9c8a-062779d96bf3" />
- Menggunakan PUT untuk mengubah data berdasarkan ID yang di targetkan
2. <img width="299" height="74" alt="image" src="https://github.com/user-attachments/assets/3e755124-5e8a-40a8-92c6-ab2cd4ba864a" />
- Data baru (nama dan job) dikirim dalam format json
3. <img width="299" height="56" alt="image" src="https://github.com/user-attachments/assets/9d7f3c7f-4d57-4f84-a420-f8c61e5bf0de" />
- Pembaruan berhasil jika server mengembalikan Status Code 200 (OK)
# E. Kesimpulan
Praktikum ini sudah berhasil mengimplementasikan aplikasi mobile flutter yang terintegrasi penuh dengan REST API eksternal, dan telah memenuhi tujuan untuk memahami penerapan operasi CRUD, namun masih ada error pada bagian daftar awal pengguna (Read).
