# 📝 Flutter Simple Note App

Aplikasi catatan sederhana yang dibangun menggunakan **Flutter** dengan sistem penyimpanan data lokal **SQLite**. Aplikasi ini dirancang dengan antarmuka yang bersih, responsif, dan mendukung fitur tema adaptif.

---

## 📸 Preview Aplikasi
Aplikasi menyediakan pengalaman visual yang nyaman dengan dua mode utama:
* 🌙 **Dark Mode**: Tampilan gelap untuk kenyamanan mata di malam hari.
* ☀️ **Light Mode**: Tampilan bersih dan cerah untuk penggunaan siang hari.

---

## ✨ Fitur Utama
* ➕ **Tambah Catatan**: Membuat catatan baru dengan judul, isi, dan nama penulis.
* ✏️ **Edit & Update**: Memperbarui catatan yang sudah ada secara dinamis.
* 🗑️ **Hapus Catatan**: Menghapus catatan yang sudah tidak diperlukan.
* 💾 **Penyimpanan Lokal**: Menggunakan SQLite agar data tersimpan permanen di perangkat.
* ⚡ **Auto-Save**: Otomatis menyimpan perubahan saat pengguna menekan tombol kembali.
* 🌗 **Dynamic Theme**: Switcher tema gelap/terang langsung dari halaman utama.

---

## 🛠️ Teknologi & Package
| Teknologi | Keterangan |
| :--- | :--- |
| **Flutter** | Framework UI utama |
| **Dart** | Bahasa pemrograman |
| **SQLite (sqflite)** | Database relasional lokal |
| **Provider / setState** | Management state aplikasi |
| **Path** | Penanganan lokasi direktori file |

---

## 📂 Struktur Folder
```text
lib/
├── models/
│   └── note_model.dart       # Model data & fungsi toMap/fromMap
├── pages/
│   ├── home_page.dart       # Tampilan utama daftar catatan
│   └── note_page.dart       # Editor catatan (Tambah/Edit)
├── services/
│   └── database_helper.dart # Konfigurasi & Query CRUD SQLite
├── widgets/
│   └── note_card.dart       # Komponen UI kartu catatan
└── main.dart
<img width="455" height="936" alt="Cuplikan layar 2026-05-13 105538 (1)" src="https://github.com/user-attachments/assets/425facd7-a9cc-4235-9c28-5046995fa9ef" />
<img width="460" height="937" alt="Cuplikan layar 2026-05-13 105515" src="https://github.com/user-attachments/assets/e1e987c0-68af-44e8-9519-fdb315ab7136" />
<img width="453" height="940" alt="Cuplikan layar 2026-05-13 105458 (1)" src="https://github.com/user-attachments/assets/77a187d8-026b-4eac-9778-6ea6a470d53e" />



