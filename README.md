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

## 🖼️ Tampilan Aplikasi

| **Fitur**             | **Tampilan** |
|-----------------------|--------------|
| **Form Sisipkan** , ini digunakan untuk menyisipkan pesan rahasia ke dalam gambar. Pengguna memilih gambar `.png`, mengisi PIN, dan mengetik pesan rahasia. | ![Form Sisipkan](https://github.com/user-attachments/assets/1f4252fd-4522-4fa7-8f4f-0ac3623570ca) |
| **Form Ekstrak** , ini digunakan untuk mengekstrak pesan dari gambar stego.  Pengguna harus mengunggah gambar hasil stego dan memasukkan PIN yang benar. | ![Form Ekstrak](https://github.com/user-attachments/assets/fe1b92a7-3c9b-4729-92cf-98d36700a582) |
| **Hasil Ekstrak** , Halaman ini menampilkan pesan rahasia yang berhasil diekstrak.  Juga terlihat gambar asli dan gambar stego untuk perbandingan. | ![Hasil Ekstrak](https://github.com/user-attachments/assets/bd85e8be-d5cf-4ce2-9707-26ee0ddb304b) |

---

## 🚀 Cara Menjalankan Aplikasi

### 1. Clone repository

```bash
git clone https://github.com/IrmaDwiyanti/Steganografi-Enkripsi-Pesan.git
cd Steganografi-Enkripsi-Pesan
```

### 2. Install Depedensi

```bash
pip install -r requirements.txt
```

### 3. ▶️ Cara Menjalankan Aplikasi

```bash
python app.py
```

### 4. Lalu buka browser dan akses

```bash
http://localhost:5000
```

