# PENA — Jejak & Admin v1

Tambahan final pada existing PENA:

- `jejak.html` — halaman editorial "Jejak Sejarah" dengan arsip Tugu Narkoba Bogor.
- `admin.html` — fondasi PENA Admin untuk CRUD konten Jejak (editor lokal/browser).
- `pena-jejak-seed.json` — data awal Tugu Narkoba.
- `index.html` — bagian Jejak diperkuat dengan kartu Tugu Narkoba dan tautan PENA Admin.

## Catatan produksi

GitHub Pages bersifat static. `admin.html` v1 sengaja belum diberi kemampuan menulis ke server.
Data saat ini disimpan di localStorage dan dapat diekspor/impor JSON.

Tahap produksi berikutnya:
PENA Admin -> Google Apps Script API -> Google Sheets -> halaman Jejak.
Authentication admin harus ditambahkan pada tahap tersebut; jangan menganggap `admin.html` ini sebagai sistem keamanan produksi.

## Prinsip kurasi

Pisahkan:
1. Fakta terverifikasi
2. Konteks sejarah
3. Interpretasi/makna
4. Catatan PENA

Klaim yang belum didukung sumber primer diberi status/label dan dapat diperbarui.
