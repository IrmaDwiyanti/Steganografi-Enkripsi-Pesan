# 🔐 Alpha Channel Image Steganography (Web-Based Flask App)

Aplikasi web ini menerapkan teknik steganografi citra digital menggunakan **Alpha Channel** untuk menyembunyikan pesan rahasia dalam gambar berformat PNG. Metode yang digunakan berbasis **Least Significant Bit (LSB)** pada channel transparansi (alpha), sehingga tidak mengubah tampilan visual gambar secara signifikan.

---

## 📸 Fitur Utama

- ✅ Menyisipkan pesan rahasia ke dalam gambar PNG
- 🔑 Proteksi dengan PIN (hash-based verification)
- 🕵️ Ekstraksi pesan rahasia dengan validasi PIN
- 💡 Tampilan web responsif dengan **Tailwind CSS**
- 💬 Menampilkan gambar asli dan gambar stego hasil proses

---

## 🖥️ Tampilan Aplikasi

| Form Sisipkan | Form Ekstrak | Hasil Ekstrak |
|---------------|--------------|----------------|
| ![Embed](screenshots/embed.png) | ![Extract](screenshots/extract.png) | ![Result](screenshots/result.png) |

---

## 🚀 Cara Menjalankan Aplikasi

### 1. Clone repository

```bash
git clone https://github.com/username/alpha-steganography-web.git
cd alpha-steganography-web
