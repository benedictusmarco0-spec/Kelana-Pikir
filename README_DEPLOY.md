# Kelana Pikir - Vercel Ready

Folder ini siap di-deploy ke Vercel sebagai static site.

Isi utama:
- index.html: file website utama
- vercel.json: konfigurasi rewrite agar semua route diarahkan ke index.html

Pengaturan Vercel yang disarankan:
- Framework Preset: Other
- Build Command: kosongkan
- Output Directory: .
- Install Command: kosongkan

Catatan:
Website ini memakai localStorage/browser storage, sehingga data akun, keranjang, pesanan, dan stok tersimpan di browser pengguna, bukan database server.
