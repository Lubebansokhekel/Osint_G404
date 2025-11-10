# 🕵️ OSINT_G404 - Open Source Intelligence Tool

**OSINT_G404** adalah alat sederhana yang dirancang untuk membantu proses pengumpulan informasi menggunakan metode OSINT (Open Source Intelligence). Script ini dijalankan di lingkungan **Termux**, dan dilengkapi pendukung yang mempercepat pekerjaan investigasi.

---

## 📸 Tampilan OSINT_G404

Berikut adalah tampilan antarmuka dari script ini di Termux:

![Screenshot OSINT di Termux](https://github.com/Lubebansokhekel/Osint_G404/blob/main/Screenshot_2025-06-20-04-57-01-469_com.termux.jpg)

---

## 🔧 Fitur dan Komponen

OSINT_G404 memanfaatkan kombinasi alat-alat ringan namun fungsional:

- [`jq`](https://stedolan.github.io/jq/) - Untuk parsing data JSON.
- `api` - Mendukung penggunaan API eksternal.
- `boxes` - Menampilkan teks artistik dalam terminal.
- `curl` - Untuk melakukan HTTP request otomatis.
- `nala` - Manajer paket berbasis APT dengan antarmuka lebih ramah.
- `MPV` - Pemutar media CLI, digunakan untuk analisis media jika dibutuhkan.
- 🔍 **Alat OSINT** tambahan untuk menunjang investigasi digital.

Gambaran yang di gunakan OSINT_G404:

![OSINT Tools](https://github.com/Lubebansokhekel/Osint_G404/blob/main/IMG-20250620-WA0001.jpg)

---

## ⚙️ Instalasi

Untuk mulai menggunakan OSINT_G404, jalankan perintah berikut di Termux:

```bash
pkg update
pkg install git xz-utils -y
git clone https://github.com/Lubebansokhekel/Osint_G404
cd Osint_G404
git pull origin main
git stash
bash osint.sh
```
## 🖊️ CATATAN

Script ini dapat mengalami downtime atau berhenti berfungsi sewaktu-waktu jika layanan eksternal/endpoint mati.
Jika Anda bersedia mendukung pengaktifan kembali atau pengembangan lebih lanjut, silakan berdonasi untuk membantu keberlanjutan proyek ini. 🙏

## 📥 DONASI
https://saweria.co/Galirus
