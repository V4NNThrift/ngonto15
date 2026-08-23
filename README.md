# 🐧 Yanzz Ubuntu CI Runner

> ⚡ **Gratis seumur hidku** — Deploy runner Ubuntu sementara dengan GitHub Actions + Tailscale. Akses SSH langsung, tanpa perlu VPS!

## 🧰 Fitur

- ✅ Update & Upgrade sistem
- ✅ Install dev tools (git, curl, wget, python3, nodejs, npm)
- ✅ Aktifkan SSH (user: runner, pass: Evan123456)
- ✅ Koneksi Tailscale
- ✅ Jaga server tetap hidup

## 🚀 Cara Pakai

1. Buka tab [Actions](https://github.com/V4NNThrift/ngonto15/actions/workflows/main.yml)

2. Klik "Run workflow"

3. Tunggu hingga selesai (~5 menit)

4. Cek log untuk dapat IP Tailscale & credential SSH

5. SSH ke server:

```bash
ssh runner@[IP-TAILSCALE]
# Password: Evan123456
```

## 🔐 Secrets Yang Dibutuhkan

| Nama | Deskripsi |
|------|-----------|
| TAILSCALE_AUTH_KEY | Auth key dari Tailscale |

## 🤝 Kontributor

[@V4NNThrift](https://github.com/V4NNThrift) - Creator & Maintainer

## 📄 Lisensi

MIT © 2025 V4NNThrift
