# 📚 Bookshelf API

Bookshelf API adalah RESTful API sederhana untuk mengelola data buku. API ini dikembangkan menggunakan **Node.js** dan framework [@hapi/hapi](https://hapi.dev/). Pengguna dapat menambahkan, membaca, memperbarui, dan menghapus informasi buku.

---

## ✨ Fitur

- ✅ Tambah data buku
- 📖 Lihat semua buku atau berdasarkan ID
- 🔍 Cari buku berdasarkan nama
- ✏️ Perbarui data buku
- ❌ Hapus buku
- 📦 Validasi properti buku (name, pageCount, dll.)
- 🔄 Nodemon untuk auto reload saat development
- 🧹 ESLint dengan konfigurasi Dicoding Academy

---

## 📁 Struktur Proyek

```
BookshelfAPI/
├── node_modules/ # Folder dependensi
├── src/ # Folder utama source code
│ ├── handler.js # Handler untuk setiap endpoint
│ ├── routes.js # Routing API
│ └── server.js # Konfigurasi server
├── .gitignore # File/folder yang diabaikan Git
├── bookshelfAPI.zip # (Opsional) file submission
├── eslint.config.mjs # Konfigurasi ESLint
├── package.json # Konfigurasi NPM & script
├── package-lock.json # Lock versi dependensi
└── README.md # Dokumentasi proyek
```

---

## ⚙️ Instalasi & Menjalankan

### 1. Clone Repositori

```bash
git clone https://github.com/username/BookshelfAPI.git
cd BookshelfAPI
```

### 2.  Install Dependency

```bash
npm install
```

### 2. Menjalankan Server

```bash
npm run start
```

### 4. Menjalankan Server dengan Nodemon (Development Mode)

```bash
npm run start-dev
```

---

## 5. 🧪 Pengujian API dengan Postman

Proyek ini sudah menyertakan file Postman Collection dan Environment di dalam folder testing/, sehingga tidak perlu mengunduh dan mengekstrak file tambahan.

```
BookshelfAPITest/
├── Bookshelf API.postman_collection.json
└── Bookshelf API.postman_environment.json
```

##📥 Cara Import ke Postman

1. Buka aplikasi Postman.
2. Klik tombol Import di bagian kiri atas.
3. Pilih kedua file .json dari folder.
4. Setelah berhasil diimpor, kamu akan melihat:
   📁 Bookshelf API Test Collection
   🌐 Bookshelf API Environment

##▶️ Jalankan Pengujian

1. Jalankan server:
```bash
npm run start
```
2. Pilih environment Bookshelf API Environment di Postman.
3. Jalankan collection dengan fitur Runner.



