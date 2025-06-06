# Just-nextjs

Aplikasi ini adalah proyek demo untuk menunjukkan implementasi Continuous Integration dan Continuous Deployment (CI/CD) menggunakan **GitHub Actions**. Proyek ini dibuat dengan Next.js sebagai aplikasi default, dan sudah dilengkapi dengan unit test sederhana menggunakan **Jest**.

## 📆 Teknologi yang Digunakan

* [Next.js](https://nextjs.org/) – Framework React untuk aplikasi web modern
* [Jest](https://jestjs.io/) – Framework testing JavaScript
* [GitHub Actions](https://github.com/features/actions) – Platform CI/CD untuk otomatisasi workflow

## 🚀 Cara Menjalankan Aplikasi Secara Lokal

1. **Clone repository ini**

   ```bash
   git clone https://github.com/98hub/just-nextjs.git
   cd just-nextjs
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Jalankan aplikasi**

   ```bash
   npm run dev
   ```

   Aplikasi akan berjalan di `http://localhost:3000`

## 🧲 Menjalankan Unit Test

Untuk menjalankan unit test yang tersedia, gunakan perintah berikut:

```bash
npm run test
```

Pastikan test sudah berhasil sebelum melakukan push ke repository.

## 🔄 CI/CD dengan GitHub Actions

Proyek ini telah terintegrasi dengan GitHub Actions untuk:

* Menjalankan **unit test otomatis** pada setiap push dan pull request
* Menjaga kualitas kode dan kestabilan sebelum deployment

Workflow GitHub Actions disimpan di folder `.github/workflows/` dan dapat dimodifikasi sesuai kebutuhan.

## 📁 Struktur Dasar Proyek

```
just-nextjs
├─ README.md
├─ eslint.config.mjs
├─ jest.config.js
├─ jest.setup.js
├─ jsconfig.json
├─ next.config.mjs
├─ package.json
├─ postcss.config.mjs
├─ public
│  ├─ file.svg
│  ├─ globe.svg
│  ├─ next.svg
│  ├─ vercel.svg
│  └─ window.svg
├─ server.mjs
└─ src
   └─ app
      ├─ favicon.ico
      ├─ globals.css
      ├─ layout.js
      ├─ page.js
      └─ page.test.js

```

## 🩰 Skrip NPM yang Tersedia

| Perintah        | Deskripsi                     |
| --------------- | ----------------------------- |
| `npm run dev`   | Menjalankan server dev        |
| `npm run build` | Build aplikasi untuk produksi |
| `npm run start` | Menjalankan server produksi   |
| `npm run test`  | Menjalankan unit test         |

## 📄 Lisensi

Proyek ini untuk tujuan demonstrasi dan tidak memiliki lisensi khusus.