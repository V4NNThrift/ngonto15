# 🐧 Yanzz Ubuntu Runner

> Gratis! Pakai GitHub Actions + Tailscale untuk bikin runner Ubuntu sementara dengan akses SSH. Cocok buat nge-deploy, testing, atau eksplorasi jaringan.

## ✨ Fitur

- 🛠️ Install otomatis paket dasar (git, curl, nodejs, npm, dll)
- 🔐 Akses SSH aman via Tailscale
- ⚡ Jalan otomatis saat workflow dipicu

## 🚀 Cara Pakai

Klik **"Run workflow"** di tab *Actions* repo ini, lalu tunggu hingga selesai. Setelah itu, konek lewat SSH:

```bash
ssh runner@<IP-TAILSCALE>
# Password: Evan123456
```

## 📋 Syarat

- Akun Tailscale dengan auth key  
- Secrets `TAILSCALE_AUTH_KEY` di repo ini

## 👨‍💻 Contributor

- [@V4NNThrift](https://github.com/V4NNThrift) — Pembuat

## 📄 Lisensi

MIT
