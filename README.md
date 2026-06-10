# Kelana Pikir - Deploy ke Vercel

Folder ini sudah siap di-deploy ke Vercel sebagai static website.

## Isi folder
- `index.html` = file utama website
- `vercel.json` = konfigurasi agar semua route diarahkan ke `index.html`

## Cara deploy lewat Vercel
1. Buka https://vercel.com
2. Login atau daftar akun.
3. Pilih **Add New Project**.
4. Upload folder ini ke GitHub terlebih dahulu, lalu import repository tersebut ke Vercel.
5. Pada pengaturan project, biarkan default.
6. Klik **Deploy**.

## Cara cepat lewat Vercel CLI
Jalankan perintah berikut di terminal pada folder ini:

```bash
npm i -g vercel
vercel
```

Ikuti instruksi yang muncul. Untuk Production Deploy, jalankan:

```bash
vercel --prod
```

## Catatan
Website ini berbasis HTML, CSS, dan JavaScript dalam satu file. Tidak perlu build command khusus.
