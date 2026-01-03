# bookshelf-api

# 📚 Bookshelf API

Bookshelf API adalah RESTful API sederhana untuk mengelola data buku (bookshelf). Project ini dibuat sebagai latihan backend menggunakan **Node.js** dan **Hapi.js**, serta mengikuti praktik Git dan struktur project yang rapi.

---

## 🚀 Fitur

* Menambahkan buku
* Menampilkan semua buku
* Menampilkan detail buku berdasarkan ID
* Mengubah data buku
* Menghapus buku
* Validasi input (nama buku wajib)

---

## 🛠️ Teknologi yang Digunakan

* **Node.js**
* **Hapi.js**
* **Nanoid**
* **Nodemon** (development)

---

## 📂 Struktur Project (ringkas)

```
bookshelf-api/
├── src/
│   ├── handler.js
│   ├── routes.js
│   └── server.js
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Instalasi & Menjalankan Project

### 1️⃣ Clone repository

```bash
git clone https://github.com/salsasabila16/bookshelf-api.git
cd bookshelf-api
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Jalankan server

```bash
npm run start
```

Atau untuk mode development:

```bash
npm run dev
```

Server akan berjalan di:

```
http://localhost:9000
```

---

## 📮 Endpoint API

### ➕ Tambah Buku

**POST** `/books`

### 📚 Lihat Semua Buku

**GET** `/books`

### 📖 Detail Buku

**GET** `/books/{id}`

### ✏️ Update Buku

**PUT** `/books/{id}`

### 🗑️ Hapus Buku

**DELETE** `/books/{id}`

---

## 🧪 Testing

API ini dapat diuji menggunakan:

* Postman
* Thunder Client (VS Code)
* Curl

---

## 📌 Catatan

* Folder `node_modules` tidak disertakan di repository (menggunakan `.gitignore`)
* Data buku disimpan sementara (in-memory)

---

## 👤 Author

**Salsa Sabila**
GitHub: [https://github.com/salsasabila16](https://github.com/salsasabila16)

---

✨ Project ini dibuat untuk belajar dan latihan backend. Silakan dikembangkan lebih lanjut!
