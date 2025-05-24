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
## 📱Tampilan Login 
![alt text](https://github.com/user-attachments/assets/39181977-9e62-40d9-98ec-ef8d0ca24961?raw=true)
## 📲Tampilan Register
![alt text](https://github.com/user-attachments/assets/39181977-9e62-40d9-98ec-ef8d0ca24961?raw=true)
## 📵Login Gagal
![alt text](https://github.com/renld22/Pemograman4-UMB/blob/master/pictures/login%20gagal.png?raw=true)
## ⛔Password kurang dari 6 karakter
![alt text](https://github.com/renld22/Pemograman4-UMB/blob/master/pictures/password%20kurang.png?raw=true)
## ✅Login Berhasil
![alt text](https://github.com/renld22/Pemograman4-UMB/blob/master/pictures/login%20berhasil.png?raw=true)

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
