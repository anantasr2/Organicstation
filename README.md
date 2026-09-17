# 🌿 Organicstation

> Toko online herbal & organik — dari susu kedelai sampai skincare berbahan alami, dibungkus dalam tampilan yang bersih dan cepat.

**🔗 Live Demo:** [organicstation.vercel.app](https://organicstation.vercel.app)

![Status](https://img.shields.io/badge/status-deployed-brightgreen)
![Platform](https://img.shields.io/badge/hosted%20on-Vercel-black?logo=vercel)
![Stack](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20JS-orange)

---

## 📑 Daftar Isi

- [Tentang Project](#-tentang-project)
- [Struktur Project](#️-struktur-project)
- [Tech Stack](#️-tech-stack)
- [Menjalankan Secara Lokal](#-menjalankan-secara-lokal)
- [Deployment](#-deployment)
- [Halaman](#-halaman)
- [Catatan Pengembangan](#-catatan-pengembangan)
- [Kontribusi](#-kontribusi)
- [Lisensi](#-lisensi)
- [Tentang Developer](#-tentang-developer)

---

## ✨ Tentang Project

**Organicstation** adalah website e-commerce statis untuk produk herbal dan organik — mulai dari minuman sehat (susu kedelai, susu almond) sampai lini skincare Botanico+. Project ini dibangun full **front-end** (HTML/CSS/JS + Bootstrap) tanpa backend, dengan alur belanja sederhana: **browse produk → keranjang → checkout → transaksi sukses**.

### Fitur Utama
- 🏠 **Landing page** dengan hero carousel & highlight produk terbaru
- 🛍️ **Katalog produk** — 12 halaman produk individual (`produk1.html` – `produk12.html`)
- 🛒 **Sistem keranjang** per produk (folder `keranjang/`)
- 💬 **Testimonial slider** pelanggan
- 📍 **Halaman Contact** lengkap dengan embed Google Maps
- ✅ **Halaman konfirmasi transaksi** (`transaksisukses.html`)
- 📱 Fully responsive (`responsive.css`)

---

## 🗂️ Struktur Project

```
organicstation/
├── css/
│   ├── bootstrap.css
│   ├── font-awesome.min.css
│   ├── produk.css
│   ├── responsive.css
│   ├── style.css
│   ├── style.css.map
│   └── style.scss
├── fonts/
├── images/
├── js/
│   ├── bootstrap.js
│   ├── custom.js
│   ├── jquery-3.4.1.min.js
│   └── keranjang.js
├── keranjang/                 # halaman keranjang per produk
├── contact.html
├── index.html                 # halaman utama
├── produk1.html ... produk12.html
├── shop.html
├── testimonial.html
├── transaksisukses.html
└── why.html
```

---

## 🛠️ Tech Stack

| Kategori   | Teknologi                          |
|------------|-------------------------------------|
| Markup     | HTML5                               |
| Styling    | CSS3, SCSS, Bootstrap               |
| Scripting  | JavaScript, jQuery 3.4.1            |
| Icons      | Font Awesome                        |
| Deployment | Vercel                              |

---

## 🚀 Menjalankan Secara Lokal

Karena ini pure static site, tidak perlu install dependency apapun:

```bash
# Clone repository
git clone https://github.com/<username>/organicstation.git
cd organicstation

# Buka langsung di browser
open index.html
```

Atau jalankan dengan live server (disarankan agar path relatif tetap konsisten):

```bash
npx serve .
```

---

## 🌐 Deployment

Project ini di-deploy menggunakan **Vercel** sebagai static site — cukup connect repository dan Vercel akan otomatis build & serve seluruh file HTML/CSS/JS tanpa konfigurasi tambahan.

**Live:** [https://organicstation.vercel.app](https://organicstation.vercel.app)

---

## 📄 Halaman

| Halaman | Deskripsi |
|---|---|
| `index.html` | Landing page dengan hero, produk terbaru, dan why-us |
| `shop.html` | Halaman katalog belanja |
| `produk[1-12].html` | Detail masing-masing produk |
| `keranjang/` | Halaman keranjang per produk |
| `testimonial.html` | Ulasan pelanggan |
| `contact.html` | Kontak & lokasi toko |
| `transaksisukses.html` | Konfirmasi setelah checkout |
| `why.html` | Alasan memilih Organicstation |

---

## 📌 Catatan Pengembangan

- [ ] Integrasi payment gateway (saat ini alur checkout masih statis)
- [ ] Migrasi katalog produk ke data-driven (JSON/CMS) agar tidak hardcode per halaman
- [ ] Tambah backend untuk manajemen stok & pesanan

---

## 📬 Kontak Toko

📍 Jl. Abimanyu VI No. 39, Semarang, Jawa Tengah
📧 abcd@gmail.com

---

## 🤝 Kontribusi

Kontribusi, issue, dan feature request sangat terbuka. Silakan cek [halaman issues](https://github.com/<username>/organicstation/issues) sebelum membuat yang baru.

1. Fork repository ini
2. Buat branch baru (`git checkout -b fitur/nama-fitur`)
3. Commit perubahan (`git commit -m 'feat: tambah fitur X'`)
4. Push ke branch (`git push origin fitur/nama-fitur`)
5. Buka Pull Request

---

## 📄 Lisensi

Didistribusikan dengan lisensi **MIT**. Lihat `LICENSE` untuk informasi lebih lanjut.

---

## 👨‍💻 Tentang Developer

**[Nama Kamu]**
Mahasiswa S1 Teknik Informatika — membangun project ini sebagai bagian dari eksplorasi pengembangan web front-end.

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/<username>)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/<username>)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:emailkamu@gmail.com)

> 💡 *Tertarik kolaborasi atau punya masukan? Jangan ragu untuk membuka issue atau menghubungi saya langsung.*

---

<p align="center">Dibuat dengan 🌱 untuk gaya hidup sehat.</p>