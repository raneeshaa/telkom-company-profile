# Telkom University Company Profile - Praktikum

Proyek simulasi website company profile menggunakan HTML, CSS, PHP Native, MySQL/MariaDB, dan version control Git/GitHub.

---

## Fitur Utama Website
- **Beranda (`index.php`):** Menampilkan highlight program studi dan berita terbaru dari database.
- **Profil (`profile.php`):** Visi pembelajaran, tujuan proyek, dan fokus materi.
- **Program Studi (`programs.php`):** Menampilkan daftar program studi secara dinamis dari database.
- **Berita & Detail (`news.php` & `news_detail.php`):** Daftar kegiatan dan detail berita menggunakan *Prepared Statement*.
- **Kontak (`contact.php` & `contact_process.php`):** Form pengiriman pesan dengan operasi `INSERT` ke database.
- **Admin Lokal (`admin/add_news.php`):** Form simulasi penambahan berita baru.

---

## Cara Menjalankan Project Secara Lokal

1. **Salin Folder Project:**
   Pastikan folder `telkom-company-profile` berada di dalam direktori `C:\xampp\htdocs\`.

2. **Jalankan Web Server:**
   Buka **XAMPP Control Panel**, lalu klik **Start** pada modul **Apache** dan **MySQL**.

3. **Import Database:**
   - Buka browser dan akses `http://localhost/phpmyadmin/`.
   - Buat database baru bernama `telkom_profile`.
   - Import file SQL yang berada di lokasi: `database/telkom_profile.sql`.

4. **Akses Website:**
   Buka browser dan jalankan URL:
   `http://localhost/telkom-company-profile/`

---

## Riwayat Praktikum Git

- **Remote Repository:** `https://github.com/raneeshaa/telkom-company-profile.git`
- **Release Tag:** `v1.0.0`

> *Seluruh konten institusi pada proyek ini bersifat simulasi untuk keperluan praktikum.*