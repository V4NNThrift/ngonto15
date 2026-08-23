<div align="center">
  <img src=".github/logo.svg" alt="Yanzz Ubuntu Logo" width="400"/>
</div>

# 🐧 **Yanzz Ubuntu CI Runner**

> ⚡ Gratis! Gunakan GitHub Actions + Tailscale untuk deploy runner Ubuntu sementara dengan akses SSH langsung.

<div align="center">

![License](https://img.shields.io/github/license/V4NNThrift/ngonto15?style=flat&color=blue)
![Stars](https://img.shields.io/github/stars/V4NNThrift/ngonto15?style=social)
![Workflow Status](https://github.com/V4NNThrift/ngonto15/actions/workflows/main.yml/badge.svg)
![Made with 💻](https://img.shields.io/badge/Made%20with-💻-ff69b4)

</div>

---

## 🚀 Apa Ini?

Repo ini berisi workflow GitHub Actions yang secara otomatis:

- 🛠️ Install paket dasar (nodejs, npm, git, curl, dll)
- 🔐 Setup SSH & Tailscale
- ⚡ Jaga server tetap hidup sampai kamu disconnect

---

## 🧪 Cara Pakai

1. **Tekan tombol di bawah ini:**

   <img src="https://github.com/V4NNThrift/ngonto15/actions/workflows/main.yml/badge.svg" alt="Run Workflow"/>

2. Setelah jalan, lihat output di tab *Actions* untuk dapatkan IP Tailscale.
3. SSH ke server:

```bash
ssh runner@<IP-TAILSCALE>
# Password: Evan123456
```

---

## ⚙️ Secrets yang Dibutuhkan

| Nama                | Deskripsi                        |
|---------------------|----------------------------------|
| `TAILSCALE_AUTH_KEY`| Auth key dari akun Tailscale kamu|

---

## 🧑‍💻 Contributors

[@V4NNThrift](https://github.com/V4NNThrift)

---

## 📄 License

Lisensi MIT — pakai bebas, modifikasi juga bebas.
