# 🔐 Google Account Manager

> Aplikasi desktop yang aman untuk mengelola dan mengakses beberapa akun Google dengan enkripsi AES-256-GCM.

![Version](https://img.shields.io/github/v/release/m00ja/google-account-manager-releases?style=flat-square&label=version)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Security](https://img.shields.io/badge/encryption-AES--256--GCM-success?style=flat-square)

---

## ✨ Fitur Utama

- 🔒 **Enkripsi AES-256-GCM** — Semua data akun dienkripsi secara lokal di komputer Anda
- 👤 **Multi-Akun** — Kelola beberapa akun Google dalam satu aplikasi
- 🔑 **Master Password** — Satu password untuk mengamankan semua akun
- 🛡️ **Recovery Key** — Kunci pemulihan jika lupa master password
- 📦 **Backup & Restore** — Ekspor dan impor data dengan aman
- 🔄 **Auto Update** — Pembaruan otomatis melalui GitHub Releases

---

## 📥 Download & Instalasi

Unduh versi terbaru dari halaman **[Releases](https://github.com/m00ja/google-account-manager-releases/releases/latest)**:

| File | Keterangan |
|------|-----------|
| `Google-Account-Manager-Setup-x.x.x.exe` | Windows Installer (Direkomendasikan) |

---

## ⚠️ Panduan Windows SmartScreen

Saat pertama kali membuka installer, Windows kemungkinan akan menampilkan peringatan seperti ini:

<div align="center">

**"Windows protected your PC"**

</div>

> *Microsoft Defender SmartScreen prevented an unrecognized app from starting.*

**Ini adalah peringatan normal** untuk aplikasi yang baru dirilis. Aplikasi ini **aman** — data Anda hanya disimpan secara lokal dan tidak pernah dikirim ke server manapun.

### Cara Melanjutkan Instalasi:

**Langkah 1 — Klik "More info"** (Informasi selengkapnya)

```
┌───────────────────────────────────────────────────┐
│  🛡️  Windows protected your PC                   │
│                                                   │
│  Microsoft Defender SmartScreen prevented an      │
│  unrecognized app from starting. Running this     │
│  app might put your PC at risk.                   │
│                                                   │
│  App: Google Account Manager Setup                │
│                                                   │
│  [ More info ]                    [ Don't run ]   │
└───────────────────────────────────────────────────┘
                    ↑
              Klik di sini
```

**Langkah 2 — Klik "Run anyway"** (Tetap jalankan)

```
┌───────────────────────────────────────────────────┐
│  🛡️  Windows protected your PC                   │
│                                                   │
│  App:       Google Account Manager Setup          │
│  Publisher: Unknown Publisher                     │
│                                                   │
│  [ Run anyway ]                   [ Don't run ]   │
└───────────────────────────────────────────────────┘
       ↑
  Klik di sini
```

✅ **Instalasi akan berjalan normal setelah langkah ini.**

---

### ❓ Mengapa Peringatan Ini Muncul?

Windows SmartScreen menggunakan **sistem reputasi** berdasarkan jumlah pengguna yang telah mengunduh suatu aplikasi. Aplikasi yang baru dirilis belum memiliki reputasi yang cukup di database Microsoft, sehingga peringatan ini muncul secara otomatis — **meskipun aplikasinya sepenuhnya aman**.

Seiring bertambahnya pengguna yang mengunduh aplikasi ini, peringatan SmartScreen akan **berkurang secara otomatis** di masa mendatang.

---

## 🔒 Keamanan & Privasi

- ✅ Semua data disimpan **secara lokal** di komputer Anda
- ✅ **Tidak ada data** yang dikirim ke server eksternal manapun
- ✅ Enkripsi menggunakan **AES-256-GCM** (standar keamanan tinggi)
- ✅ Master password di-hash dengan **Argon2id** (algoritma terkuat saat ini)
- ✅ Kode sumber tersedia untuk audit publik di [repositori utama](https://github.com/m00ja/google-account-manager)

---

## 🚀 Cara Penggunaan

1. **Jalankan** aplikasi setelah instalasi selesai
2. **Buat Master Password** — Password ini melindungi semua data Anda
3. **Simpan Recovery Key** — Simpan kunci pemulihan di tempat yang aman (penting!)
4. **Tambah Akun Google** — Klik "Tambah Akun" dan ikuti langkah login
5. **Akses Akun** — Klik akun yang diinginkan untuk membuka browser secara otomatis

---

## 🐛 Melaporkan Bug / Masalah

Menemukan bug atau masalah? Silakan buat [Issue baru](https://github.com/m00ja/google-account-manager-releases/issues/new) dengan menyertakan:

- Versi aplikasi yang digunakan
- Versi Windows (10 / 11)
- Langkah-langkah untuk mereproduksi masalah
- Screenshot error (jika ada)

---

## 📄 Lisensi

MIT License — Aplikasi ini bebas digunakan untuk keperluan pribadi.

---

<div align="center">
  <p>Dibuat dengan ❤️ oleh <a href="https://muliawan.me">Muliawan.me</a></p>
  <p>
    <a href="https://github.com/m00ja/google-account-manager-releases/releases/latest">⬇️ Download Sekarang</a>
  </p>
</div>
