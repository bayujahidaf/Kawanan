# Kawanan — deployment Vercel

Prototipe statis: landing page dan aplikasi catatan ternak.

## Via GitHub
1. Ekstrak ZIP ini.
2. Buat repository GitHub dan unggah vercel.json, README.md, dan folder dist beserta seluruh isinya.
3. Di Vercel pilih Add New > Project, lalu import repository tersebut.
4. Framework Preset: Other. Root Directory: root repository. Output Directory: dist. Build Command dan Install Command: kosong.
5. Klik Deploy.

## Via komputer dengan Node.js
Dari folder yang memuat vercel.json jalankan:
```sh
npx vercel login
npx vercel
```
Perintah kedua membuat preview deployment untuk uji coba. Ikuti pilihan akun/team milik Anda dan buat project baru kawanan.

## URL
- /: landing page
- /records atau /records.html: aplikasi
- /records?view=feed: stok pakan

## Batas prototipe
Data contoh dan perubahan hanya ada dalam memori halaman. Reload menghapus perubahan. Belum tersedia akun, database, AI, atau notifikasi otomatis. Tidak membutuhkan API key atau environment variables.

Sumber dokumentasi:
https://vercel.com/docs/deployments
https://vercel.com/docs/project-configuration/vercel-json
