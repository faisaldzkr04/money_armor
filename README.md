# 🛡️ Money Armor — Personal Financial Management App

![Money Armor Banner](moneyarmor/static/img/removebgPreview2.png)

**Money Armor** adalah aplikasi manajemen & perencanaan keuangan pribadi cerdas berbasis web yang dibangun menggunakan **Django Framework**. Aplikasi ini dirancang untuk membantu pengguna mengelola alokasi dana harian, mencatat transaksi masuk/keluar, menerapkan metode alokasi anggaran populer (70/20/10 & 50/30/20), serta berkonsultasi keuangan secara interaktif.

---

## 🌟 Fitur Utama

- 🔐 **Autentikasi & Keamanan Tingkat Lanjut**
  - Registrasi & Login Akun Pengguna.
  - Verifikasi OTP (One-Time Password) via Email untuk registrasi & reset kata sandi.
  - Proteksi data per pengguna (*Multi-user Data Isolation*).

- 📊 **Manajemen Transaksi Harian**
  - Pencatatan Pemasukan & Pengeluaran secara real-time.
  - Pengelompokan Kategori (*Kebutuhan, Tabungan, Keinginan*).
  - Visualisasi grafik & tabel ringkasan keuangan harian/bulanan.

- 🎯 **Perencanaan & Alokasi Dana (Budgeting Rules)**
  - **Metode 70/20/10:** 70% Kebutuhan Pokok, 20% Tabungan/Investasi, 10% Keinginan.
  - **Metode 50/30/20:** 50% Kebutuhan Pokok, 30% Keinginan, 20% Tabungan.
  - Simpan & atur alokasi pendapatan secara dinamis.

- 🤖 **RoboChat (AI Financial Assistant)**
  - Asisten cerdas interaktif untuk panduan, tips, dan strategi kelola keuangan.

- 👤 **Profil & Data Diri Pengguna**
  - Kustomisasi profil pengguna (Nama, Pekerjaan, No. Telepon, Foto Profil).

- 💎 **Layanan Langganan (Premium Subscription)**
  - Informasi & pilihan paket langganan keanggotaan Money Armor.

---

## 🛠️ Teknologi & Stack

- **Backend:** Python 3.x, Django 5.x
- **Database:** SQLite3
- **Frontend:** HTML5, CSS3, JavaScript (ES6+), Remix Icons, SweetAlert2, Fancybox
- **Authentication & Email Services:** Django Auth, SMTP Email Service

---

## 🚀 Panduan Instalasi & Penggunaan

### 1. Prasyarat
Pastikan Anda telah menginstal:
- [Python 3.10+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/)

### 2. Kloning Repositori
```bash
git clone https://github.com/faisaldzkr04/money_armor.git
cd money_armor
```

### 3. Persiapan Virtual Environment
```bash
# Membuat Virtual Environment
python -m venv myvenv

# Mengaktifkan Virtual Environment (Windows)
myvenv\Scripts\activate

# Mengaktifkan Virtual Environment (Linux/Mac)
source myvenv/bin/activate
```

### 4. Instalasi Dependencies
```bash
pip install django django-allauth pillow
```

### 5. Migrasi Database
```bash
cd moneyarmor
python manage.py makemigrations
python manage.py migrate
```

### 6. Jalankan Development Server
```bash
python manage.py runserver
```

Buka browser Anda dan akses: `http://127.0.0.1:8000/`

---

## 📁 Struktur Direktori Proyek

```
money_armor/
├── README.md
└── moneyarmor/
    ├── manage.py
    ├── db.sqlite3
    ├── moneyarmor/         # Konfigurasi Utama Django (settings, urls, wsgi)
    ├── myapp/              # Aplikasi Utama (models, views, urls, templates)
    │   ├── templates/      # Berkas HTML Template
    │   └── migrations/     # Berkas Skema Migrasi Database
    └── static/             # Aset Statis (CSS, JS, Gambar)
```

---

## 📜 Lisensi & Hak Cipta

© 2026 **Money Armor**. Hak cipta dilindungi undang-undang.
