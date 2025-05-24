## Android Login & Register App with SQLite
A simple Android application that allows users to register and login using local SQLite database. Built with **Java**, **XML**, and **SQLite** using Android Studio.

## Features
- Register with **Name**, **Email**, **Password**, and **Confirm Password**
- Login using registered **Email** and **Password**
- Input validation:
  - Valid email format
  - Password minimum 6 characters
  - Password and confirmation must match
- Store user data locally using **SQLite**
- Display welcome message with user name after login

## Alur Login/Register
1. Register:
   - Langsung menampilkan halaman Login.
   - User mengisi:
     - Nama
     - Email
     - Password
     - Konfirmasi Password
   - Validasi:
     - Semua input harus diisi
     - Email harus valid
     - Password dan konfirmasi minimal 6 karakter dan harus cocok
     - Email belum pernah digunakan
   - Jika valid:
     - Simpan data ke SQLite
     - Arahkan ke halaman Login  
2. Login:
   - User mengisi Email dan Password
   - Validasi:
     - Format email harus valid
     - Password minimal 6 karakter
   - Jika login sukses:
     - Arahkan ke halaman MainActivity
     - Tampilkan: `Selamat Datang, [Nama User]`
   - Jika gagal:
     - Tampilkan pesan error
   - Tersedia tombol untuk berpindah ke halaman Register

## Screenshot Tampilan
(https://github.com/user-attachments/assets/39181977-9e62-40d9-98ec-ef8d0ca24961)
(https://github.com/user-attachments/assets/c09aacd5-c9f8-471c-9373-4c048f6c8649)
(https://github.com/user-attachments/assets/1fbf8cb5-d3f9-4c6e-9b98-054d0e52db5d)

## Hasil Uji Coba Emulator


## Tools & Teknologi
- Java
- XML Layouts
- Android Studio
- SQLite
- Toast & Intent handling

## Cara Menjalankan
1. Clone atau download project ini
2. Buka dengan **Android Studio**
3. Jalankan di emulator atau perangkat fisik
4. Lakukan proses register, lalu login

## License
This project is intended for educational purposes and open for learning or improvement.

## Nama dan NIM
- Nama: [M. IQBAL SAPUTRA]  
- NIM: [220320003]
