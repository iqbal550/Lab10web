# Lab10web
# PHP OOP (Object Oriented Programming)
### Mata Kuliah : Pemrograman Web 1
### Nama : **M. Iqbal**  
### NIM : **312410212**  
### Kelas : **TI.24.A2**

---

## 📌 Deskripsi Singkat
Pada praktikum ini, mahasiswa mempelajari dan mengimplementasikan konsep **OOP (Object Oriented Programming)** pada PHP melalui:

- Pembuatan class dan object  
- Penerapan constructor dan method  
- Modularisasi kode (include class)  
- Pembuatan class `Form` untuk menghasilkan form secara dinamis  
- Pembuatan class `Database` untuk koneksi & operasi CRUD  
- Integrasi form input → penyimpanan → database  
- Pembuatan tampilan web yang aesthetic menggunakan CSS  

Proyek ini dibuat sesuai instruksi tugas Praktikum 10.

---


---

## 🧩 Penjelasan File
### **1. form.php**
Berisi class `Form` yang menghasilkan elemen input HTML secara dinamis.

### **2. form_input.php**
Halaman utama untuk mengisi data mahasiswa.  
Menggunakan class `Form` + styled menggunakan CSS agar aesthetic.

### **3. simpan_mahasiswa.php**
Memproses POST dari form dan menyimpan data ke database menggunakan class `Database`.

### **4. database.php**
Class untuk koneksi MySQL serta operasi dasar:
- Insert
- Update
- Delete
- Query
- Get data

### **5. config.php**
Berisi konfigurasi database:

# 1. Tamplian form input mahasiswa
<img width="1919" height="1087" alt="Screenshot 2025-12-01 145644" src="https://github.com/user-attachments/assets/97d01751-8f00-44c4-8d65-4c315b74656f" />

# 2. Tampilan data berhasil disimpan
<img width="1919" height="337" alt="Screenshot 2025-12-01 153122" src="https://github.com/user-attachments/assets/27241d10-eb89-4aec-a9d6-2d80e7eaec66" />

# 3. Tampilan tabel mahasiswa pada phpMyAdmin
<img width="1818" height="858" alt="Screenshot 2025-12-01 152733" src="https://github.com/user-attachments/assets/f52a01be-699c-46b9-9178-3cee964ebe24" />

# 4. Tampilan program Mobil
<img width="1919" height="1075" alt="Screenshot 2025-12-01 151315" src="https://github.com/user-attachments/assets/f8b0ac36-2134-4473-b5b4-1cc9620d5cbf" />

# Kesimpulan

**Melalui praktikum ini, mahasiswa memahami:**

Konsep dasar Object Oriented Programming pada PHP

Pemisahan struktur program menggunakan class

Membuat form dinamis menggunakan OOP

Mengakses database menggunakan class modular

Membangun tampilan web yang lebih menarik dengan CSS

Integrasi form → backend → database



