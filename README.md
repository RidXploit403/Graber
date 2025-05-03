# Search Domain Tool

## Deskripsi
**Search Domain Tool** adalah alat untuk mencari domain secara otomatis berdasarkan kata kunci yang diberikan, mengecek status HTTP, dan mendeteksi halaman login seperti **WordPress** dan **cPanel**. Alat ini menyimpan hasil pencarian dalam file terpisah, memungkinkan pengguna untuk menganalisis lebih lanjut setiap domain yang ditemukan.

## Fitur Utama
- Mencari domain berdasarkan kata kunci melalui Website Informer.
- Mengecek status HTTP (200, 403, 503, dll) untuk memastikan aksesibilitas domain.
- Mendeteksi halaman login untuk platform seperti WordPress (`wp-login.php`) dan cPanel (port `2083`, `2087`).
- Menyimpan hasil pencarian dalam file output terpisah berdasarkan kategori.
- Mempercepat proses pencarian dengan menggunakan threading.
- Mendukung filter domain berdasarkan ekstensi tertentu (misalnya `.id`, `.ac.id`, dll).

## Persyaratan
- Python 3.x
- Pustaka `requests` dan `beautifulsoup4`
- Platform: Windows, Linux, atau macOS

## Instalasi

Ikuti langkah-langkah berikut untuk menginstal dan menjalankan proyek ini:

1. Clone repositori:
    ```bash
    git clone https://github.com/username/Search-Domain-Tool.git
    ```

2. Pindah ke direktori proyek:
    ```bash
    cd Search-Domain-Tool
    ```

3. Instal pustaka yang dibutuhkan:
    ```bash
    pip install requests beautifulsoup4
    ```

## Penggunaan

Setelah instalasi selesai, ikuti langkah-langkah berikut untuk menjalankan alat ini:

1. Siapkan file berisi kata kunci pencarian (misalnya `keyword.txt`).
2. Jalankan skrip dengan perintah berikut:
    ```bash
    python search_domain.py
    ```

3. Masukkan nama file yang berisi daftar kata kunci dan ekstensi domain (jika diinginkan).

4. Tunggu proses selesai. Hasil pencarian akan disimpan dalam file output terpisah.

## Output
Setelah menjalankan skrip, hasil pencarian akan disimpan dalam file berikut:

- **`hasil_domain.txt`**: Menyimpan daftar domain yang ditemukan.
- **`domain_wordpress.txt`**: Menyimpan domain yang memiliki halaman login WordPress (`wp-login.php`).
- **`domain_cpanel.txt`**: Menyimpan domain yang memiliki halaman login cPanel (port `2083`, `2087`).

## Lisensi
Proyek ini dilisensikan di bawah [Lisensi MIT](https://opensource.org/licenses/MIT).

## Penafian
> **Peringatan:** Gunakan hanya untuk tujuan pendidikan dan pengujian penetrasi yang sah! Alat ini hanya untuk digunakan dengan izin eksplisit dari pemilik situs.

## Badge
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## Kontak
Jika Anda memiliki pertanyaan atau masalah, jangan ragu untuk membuka [issue](https://github.com/username/Search-Domain-Tool/issues) di GitHub atau hubungi saya di [email@example.com](mailto:email@example.com).

## Terima Kasih
Terima kasih telah menggunakan **Search Domain Tool**. Semoga proyek ini bermanfaat dalam pengujian dan analisis keamanan domain!

[GitHub Repo](https://github.com/username/Search-Domain-Tool)
