# TestPraktekDebian

Sebuah aplikasi sederhana untuk membantu proses pengecekan dan penilaian hasil ujian praktek Debian (atau distro Linux lainnya) dalam satu jaringan lokal. Dibuat untuk memudahkan asisten lab, pengajar, atau teknisi dalam melakukan validasi konfigurasi server secara cepat.

## Fitur Utama

Aplikasi ini dirancang untuk menyederhanakan proses penilaian dengan fitur-fitur berikut:

* **Pengecekan Jaringan:** Melakukan serangkaian tes (seperti `ping`, cek *port* terbuka, *query* DNS, dll.) ke beberapa *host* siswa secara otomatis.
* **Import Data Siswa/Peserta:** Tidak perlu input manual satu per satu. Anda bisa mengimpor daftar peserta, IP *target*, atau kriteria penilaian dari *file* (misalnya format .xlsx atau JSON).
* **Sistem Penilaian:** Memberikan skor otomatis berdasarkan kriteria yang berhasil atau gagal (misel: "Apakah *port* 80 terbuka?", "Apakah DNS *resolve*?").
* **Export Hasil:** Setelah pengecekan selesai, seluruh hasil, rangkuman, dan nilai dapat diekspor ke dalam *file* laporan (misalnya .xlsx atau PDF) untuk dokumentasi atau arsip.

## Status Proyek

Saat ini, proyek **[MASIH DALAM PENGEMBANGAN / SUDAH DIRILIS VERSI X.X / SUDAH STABIL - *pilih salah satu atau sesuaikan*]**. 

## Cara Penggunaan

*Instruksi detail tentang cara instalasi dan penggunaan akan ditambahkan di sini.*

1.  **Instalasi:**
    ```bash
    # (Contoh instruksi instalasi)
    git clone [https://github.com/username-anda/testpraktekdebian.git](https://github.com/username-anda/testpraktekdebian.git)
    cd testpraktekdebian
    pip install -r requirements.txt 
    ```
2.  **Import Data:**
    * Siapkan *file* `siswa..xlsx` dengan format: `nama,ip_address`
    * Jalankan perintah import.
3.  **Jalankan Pengecekan:**
    ```bash
    # (Contoh perintah menjalankan)
    python cek_praktek.py --file siswa..xlsx
    ```
4.  **Ekspor Hasil:**
    * Hasil akan otomatis tersimpan di `hasil_penilaian..xlsx`.

---

## Dukung Proyek Ini

Suka dengan proyek ini? Merasa terbantu? 

Setiap dukungan Anda sangat berarti untuk membantu pengembangan proyek ini, baik untuk biaya *server* uji coba, riset, atau sekadar segelas kopi agar tetap semangat *coding*.

Anda dapat memberikan apresiasi atau dukungan melalui Saweria:

**[https://saweria.co/silouteboys](https://saweria.co/silouteboys)**

Terima kasih atas setiap dukungannya!
