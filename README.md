# Portofolio Ferliyana Ronnan

Website portofolio pribadi berbasis **HTML statis** (single-file, `index.html`) dengan tema *dark* bernuansa gradasi pink–hijau–kuning. Dibuat untuk menampilkan proyek, pencapaian, pengalaman kerja, dan sertifikasi di bidang **Data Science & AI Engineering**.

🔗 Live: [portofolio-ferliyana-ronnan.vercel.app](https://portofolio-ferliyana-ronnan.vercel.app/)

---

## ✨ Fitur

- **Single HTML file** = semua CSS & JavaScript inline, tidak butuh build tool atau dependency eksternal (kecuali Google Fonts).
- **Dua mode tampilan**
  - 🌙 *Moon mode* = gradasi pink–kuning–hijau (dark)
  - ☀️ *Sun mode* = tampilan terang
- **Multi-bahasa** = Indonesia / English / 日本語, dengan sistem terjemahan berbasis `data-i18n`.
- **Navigasi** = nav pills di desktop + menu hamburger minimalis untuk mobile, mencakup section: Home, About, Projects, Achievements, Experience, Certifications, Contact.
- **Hero section** = nama besar dengan efek gradient teks, foto profil.
- **About** = foto dengan twibbon tema data science/AI, tombol *Unduh CV* & *Download Portofolio*, serta animasi angka (jumlah proyek, podium nasional, teknik/model yang dikuasai).
- **Tools marquee** = scroll otomatis menampilkan tools yang biasa dipakai (Python, scikit-learn, TensorFlow, PyTorch, LightGBM, XGBoost, CatBoost, Prophet, Optuna, SHAP, Docker, Git, Figma, MySQL, dll).
- **Projects** = grid proyek dengan filter kategori & scope, pencarian by judul/tools/kategori, serta modal detail (deskripsi, tools, gambar, link repo & notebook GitHub).
- **Achievements** = daftar pencapaian/kompetisi dengan tanggal, ikon klik untuk membuka detail lomba + foto kegiatan.
- **Experience** = timeline pengalaman kerja/organisasi.
- **Certifications** = grid sertifikat (LinkedIn), dengan tombol *View Credential* khusus sertifikat Dicoding.
- **Contact** = form "get in touch" yang mengirim email, plus link cepat ke LinkedIn, GitHub, dan Email.

## 🗂️ Struktur

```
.
└── index.html   # seluruh markup, style (CSS custom properties + animasi), dan logic (JS) dalam satu file
```

## 🎨 Desain

| Elemen        | Detail                                             |
|----------------|-----------------------------------------------------|
| Font judul     | `Playfair Display` (italic/bold)                  |
| Font body      | `Poppins`                                          |
| Font mono      | `JetBrains Mono`                                   |
| Warna aksen    | Pink `#ff4f9d`, Kuning `#ffc857`                   |
| Efek visual    | Blob animasi background, sparkle field, reveal-on-scroll |

Tema warna dikontrol lewat CSS custom properties (`--bg`, `--text`, `--pink`, dll.) yang berubah sesuai atribut `data-theme="moon"` / `data-theme="sun"` pada elemen `<html>`.

## 🚀 Menjalankan secara lokal

Karena murni HTML statis, cukup buka file langsung di browser:

```bash
# opsi 1: buka langsung
open index.html        # macOS
start index.html       # Windows

# opsi 2: pakai local server (disarankan agar semua fitur JS berjalan normal)
python -m http.server 8000
# lalu buka http://localhost:8000
```

## ☁️ Deployment

Website ini di-deploy melalui **Vercel** sebagai static site (tidak memerlukan proses build).

## 🛠️ Tech Stack

- HTML5, CSS3 (custom properties, animasi/keyframes), Vanilla JavaScript
- Google Fonts (Playfair Display, Poppins, JetBrains Mono)
- Vercel (hosting)

## 👤 Kontak

- LinkedIn: [linkedin.com/in/ferliyana-ronnan](https://linkedin.com/in/ferliyana-ronnan)
- GitHub: [github.com/FerliyanaRonnan](https://github.com/FerliyanaRonnan)
- Email: ronnanferliyana@gmail.com
