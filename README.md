# ADVERTISING DETECTIVE

Media pembelajaran interaktif Bahasa Indonesia kelas VIII: membongkar pesan dan menguji efektivitas iklan komersial serta nonkomersial.

## Isi folder
- `index.html` — aplikasi kuis mandiri (HTML, CSS, dan JavaScript dalam satu berkas).

## Menjalankan di komputer
1. Unduh folder/repository ini.
2. Buka `index.html` menggunakan Chrome atau Edge.
3. Klik **Layar Penuh** untuk penggunaan di IFP.

## Menerbitkan dengan GitHub Pages
1. Buat repository GitHub bernama `advertising-detective`.
2. Unggah `index.html` ke folder utama (root) repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu **Save**.
5. Tunggu proses publikasi, kemudian buka alamat Pages yang ditampilkan GitHub.

## Catatan penting tentang hasil kuis
Versi ini mempertahankan fitur permainan, skor, dan papan peringkat yang sudah ada pada kode Canva. Skor masih dikelola di memori browser selama sesi permainan; belum dikirim ke Google Sheets atau basis data daring. Untuk menyimpan dan merekap hasil lintas sesi/perangkat, diperlukan integrasi penyimpanan terpisah (misalnya Google Sheets melalui Apps Script). Jangan memasukkan data pribadi sensitif murid ke repository publik.

## Penyesuaian dari Canva
Kode bootstrap dan SDK internal Canva dihapus karena tidak tersedia pada GitHub Pages. Ilustrasi sampul yang sebelumnya disuntikkan oleh Canva diganti dengan ilustrasi CSS mandiri.
