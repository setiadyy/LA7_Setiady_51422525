# ACT 3 : Konsep Model View Controller MVC
1. Model (MahasiswaDAO + ModelMahasiswa)
Berisi kode untuk menghubungkan Java ke database MySQL.
Menyediakan fungsi CRUD:
✔ Add (tambah mahasiswa)
✔ Read (menampilkan semua mahasiswa)
✔ Update mahasiswa
✔ Delete mahasiswa
Mengelola data melalui objek ModelMahasiswa.

2. Controller (MahasiswaController)
Mengatur alur data antara Model dan View.
Memanggil fungsi pada DAO untuk menjalankan CRUD.
Menampilkan pesan keberhasilan atau kegagalan proses.

3. View (MahasiswaView)
Bagian yang berinteraksi langsung dengan pengguna melalui console.
Menyediakan menu:
Tampilkan semua mahasiswa
Tambah mahasiswa
Update
Hapus
Cek koneksi database
Keluar program

# ACT 4 : Konsep Dasar Object Relational Mapping (ORM) dan Framework Hibernate 
→ Konsep Dasar Object Relational Mapping (ORM)
→ Framework Hibernate
📝 Isi Laporan Secara Ringkas
Membahas pengertian ORM, yaitu teknik untuk menghubungkan objek dalam program dengan tabel di database sehingga proses CRUD lebih mudah tanpa menulis banyak query SQL.
Memperkenalkan Hibernate sebagai salah satu framework ORM paling umum digunakan pada Java.
HibeRnate berfungsi untuk mempermudah proses pengolahan data karena query dapat digantikan dengan pemanggilan class/objek dalam Java.
Laporan ini merupakan bagian kegiatan praktikum yang mempelajari dan menerapkan dasar ORM dan Hibernate.

# ACT 5 : Konsep Framework Spring, Pembuatan Project Spring dan Hibernate 
🔹 Konsep Framework Spring
🔹 Pembuatan Project Spring
🔹 Integrasi dengan Hibernate
📄 Isi Laporan Secara Ringkas
Menjelaskan dasar-dasar Spring Framework, yaitu framework Java yang digunakan untuk membangun aplikasi berbasis web maupun enterprise.
Laporan memuat proses pembuatan project Spring, mulai dari konfigurasi hingga struktur dasarnya.
Juga membahas penggunaan Hibernate bersama Spring untuk mengelola database menggunakan teknik ORM.
Terdapat screenshot kode dan hasil output program sebagai bukti implementasi.

# ACT 6 : Implementasi AOP dan Dependency Injection Pada Project Spring dan Hibernate
🔹 Implementasi AOP (Aspect Oriented Programming)
🔹 Dependency Injection
🔹 Pada Project Spring dan Hibernate
📄 Isi Secara Umum
Dalam file ini ditampilkan beberapa bagian kode penting pada project Spring + Hibernate, meliputi:
Controller → menangani request dan menghubungkan proses dengan service.
Model & Model Tabel → merepresentasikan data yang akan dikelola.
Repository → sebagai penghubung ke database untuk CRUD.
Service → menjalankan logika program dan di-inject ke controller (contoh DI).
Application Properties & POM.xml → konfigurasi database & dependency project.
View → sebagai tampilan antarmuka.
