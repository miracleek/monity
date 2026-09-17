# Monity

Aplikasi pencatat keuangan pribadi dengan login Google dan sinkronisasi data real-time.

**Live:** https://miracleek.github.io/monity/

## Deploy ke GitHub Pages

### 1. Buat repository di GitHub
- Buka [github.com](https://github.com) → New repository
- Nama repo: `monity`
- Set ke **Public** → Create repository

### 2. Push kode ke GitHub
Jalankan perintah ini di folder project:

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/miracleek/monity.git
git push -u origin main
```

### 3. Aktifkan GitHub Pages
- Di repo GitHub → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: **main** → folder: **/ (root)** → Save
- Tunggu ~1 menit, URL akan muncul: `https://miracleek.github.io/monity`

### 4. Tambahkan domain ke Firebase
- Buka [Firebase Console](https://console.firebase.google.com) → project lo
- **Authentication** → **Settings** → **Authorized domains**
- Klik **Add domain** → masukkan: `miracleek.github.io`
- Save

Selesai! App sudah bisa diakses dari HP dan PC dengan data yang tersinkron.
