# Integrasi PENA — Bahan Presentasi

Halaman aplikasi telah digabungkan ke website PENA tanpa mengganti homepage, halaman Gagasan, Jejak, Peta, Arsip, Admin, atau Tanya Om Tije.

## URL
- Website utama: https://pena.mytije.com/
- Bahan Presentasi: https://pena.mytije.com/bahan-presentasi/
- Tanya Om Tije: https://pena.mytije.com/tmt.html

## Backend
Halaman Bahan Presentasi memakai Google Apps Script Web App:
https://script.google.com/macros/s/AKfycbxX2JlkGcbVPCvUR2z-nXjM3mL39acJRbfUJ1Jfup-cKufdRGKe5ivRbLJmT-EBehI/exec

URL telah dipasang pada konstanta `API_URL` di `bahan-presentasi/index.html`.
Tidak perlu mengubah atau men-deploy ulang backend jika endpoint tersebut tetap aktif.

## Perubahan homepage
1. Menambahkan tautan navigasi **Bahan Presentasi**.
2. Menambahkan kartu **Bahan Presentasi** pada grid topik Penyuluh.
3. Menambahkan tautan Bahan Presentasi pada footer.
4. Semua halaman dan aset lama dipertahankan.
5. Aplikasi berjalan di subfolder `/bahan-presentasi/`, bukan mengganti `index.html` utama.
6. Tautan Tanya Om Tije dari aplikasi diarahkan ke `../tmt.html`.

## Deploy
Upload isi folder `pena-mytije-main` ke repository GitHub Pages yang terhubung ke `pena.mytije.com`, dengan mempertahankan struktur folder.
