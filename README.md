# Praktikum 8: PHP dan Database MySQL

## Tujuan
1. Memahami konsep dasar database.
2. Memahami CRUD (Create, Read, Update, Delete) menggunakan PHP.
3. Membuat program CRUD sederhana dengan PHP.

## Langkah-Langkah Praktikum
1. **Persiapan:**
   - Pastikan MySQL Server sudah berjalan melalui XAMPP.
   - Akses PHPMyAdmin melalui `http://localhost/phpmyadmin/`.

2. **Membuat Database dan Tabel:**
   - Buat database dengan perintah:
     ```sql
     CREATE DATABASE latihan1;
     ```
   - Buat tabel `data_barang`:
     ```sql
     CREATE TABLE data_barang (
         id_barang INT(10) AUTO_INCREMENT PRIMARY KEY,
         kategori VARCHAR(30),
         nama VARCHAR(30),
         gambar VARCHAR(100),
         harga_beli DECIMAL(10,0),
         harga_jual DECIMAL(10,0),
         stok INT(4)
     );
     ```

3. **Menambahkan Data:**
   - Gunakan perintah:
     ```sql
     INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual, stok)
     VALUES 
     ('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000, 2400000, 5),
     ('Elektronik', 'HP Xiaomi Android', 'hp_xiaomi.jpg', 1000000, 1400000, 5),
     ('Elektronik', 'HP OPPO Android', 'hp_oppo.jpg', 1800000, 2300000, 5);
     ```

4. **Membuat Program CRUD:**
   - **File koneksi:** `koneksi.php`
   - **Tampilan data:** `index.php`
   - **Tambah data:** `tambah.php`
   - **Ubah data:** `ubah.php`
   - **Hapus data:** `hapus.php`

5. **Screenshot dan Laporan:**
   ![Screenshot (383)](https://github.com/user-attachments/assets/d667d662-7fb4-448f-80c8-d09c08984a86)
   ![Screenshot (384)](https://github.com/user-attachments/assets/e973ddc4-ed69-43e9-a08e-92e6f78ffdf2)
   ![Screenshot (385)](https://github.com/user-attachments/assets/567507a2-943d-42cc-a006-ea563eb0b025)


     

## Cara Menjalankan Program
1. Clone repository atau salin folder `lab8_php_database` ke `htdocs` XAMPP.
2. Jalankan Apache dan MySQL di XAMPP.
3. Akses URL: `http://localhost/lab8_php_database/`.

---
[Instagram](https://www.instagram.com/mianaqu/)
