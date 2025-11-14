Siap! Aku buatkan **README super keren** gabungan **versi 1 (lengkap + teori + tabel + preview)** dan **versi 5 (estetik + emoji banyak)**.
Format ini *premium look*, rapi, aesthetic, dan lengkap untuk tugas akademik maupun portfolio GitHub.

Kamu tinggal copy–paste ke **README.md**.

---

# 🌙🖼️ **Metode Manipulasi Citra Digital – Operasi Logika Steganografi**

### ✨ Oleh: **Nur Fika Prihatin**

Repositori ini berisi implementasi **steganografi berbasis operasi logika** menggunakan Python dalam Jupyter Notebook.
Proyek ini disusun untuk mata kuliah **Metode Manipulasi Citra Digital** dengan fokus pada manipulasi tiga gambar menggunakan operasi AND, OR, XOR, NOT, dan gabungan logika lainnya.

---

# 📚 Daftar Isi

* [🎯 Tujuan Proyek](#-tujuan-proyek)
* [🧠 Dasar Teori Steganografi](#-dasar-teori-steganografi)
* [📁 Struktur Folder](#-struktur-folder)
* [🧪 Isi Notebook](#-isi-notebook)
* [🛠️ Cara Menjalankan](#️-cara-menjalankan)
* [📸 Preview Hasil](#-preview-hasil)
* [📊 Tabel Hasil Operasi Logika](#-tabel-hasil-operasi-logika)
* [💡 Catatan Teknis](#-catatan-teknis)
* [📜 Lisensi](#-lisensi)

---

# 🎯 Tujuan Proyek

Proyek ini bertujuan untuk:

✔️ Memahami konsep dasar steganografi pada citra digital
✔️ Menerapkan operasi logika untuk manipulasi pixel
✔️ Mengolah 3 citra menjadi hasil manipulasi visual
✔️ Menyusun pipeline: *load → operasi → visualisasi*
✔️ Menyimpan gambar hasil dengan struktur yang rapi

---

# 🧠 Dasar Teori Steganografi

Steganografi adalah **proses menyembunyikan pesan di dalam media** (gambar, suara, video) sehingga tidak terlihat oleh manusia.

Pada citra digital, beberapa teknik yang umum digunakan adalah:

### 🔹 1. **Operasi Logika pada Pixel**

Pixel citra dapat dimanipulasi menggunakan operasi bitwise:

* **AND (∧)** → mempertahankan bagian gelap
* **OR (∨)** → mempertahankan bagian terang
* **XOR (⊕)** → menonjolkan perbedaan dua gambar
* **NOT (¬)** → membalik seluruh nilai pixel

### 🔹 2. **Penerapan pada Steganografi**

Operasi logika dapat dipakai untuk:

* Menyembunyikan pola
* Menggabungkan dua citra
* Menonjolkan informasi tertentu
* Menyembunyikan pesan biner

Notebook ini memanipulasi gambar ke-3 sebagai objek utama.

---

# 📁 Struktur Folder

```
metode-manipulasi-citra-digital-nur-fika-prihatin/
│
├── gambar/                      ← tempat menyimpan semua gambar
│   ├── gambar1.png
│   ├── gambar2.png
│   ├── gambar3.png
│   ├── hasil_and.png
│   ├── hasil_or.png
│   ├── hasil_xor.png
│   └── hasil_not.png
│
├── OperasiLogika_Steganografi.ipynb
│
└── README.md
```

---

# 🧪 Isi Notebook

## 🔧 1. Import Library

```
opencv-python  
numpy  
matplotlib  
```

## 🖼️ 2. Load & Display Gambar

Semua gambar diambil dari folder **/gambar** agar rapi dan tidak berceceran.

## 🧩 3. Operasi Logika

Notebook melakukan:

| Operasi | Fungsi                  | Hasil                            |
| ------- | ----------------------- | -------------------------------- |
| **AND** | Mengambil bagian gelap  | bagus untuk edge masking         |
| **OR**  | Mengambil bagian terang | berguna untuk blending           |
| **XOR** | Menonjolkan perbedaan   | sering dipakai di analisis citra |
| **NOT** | Membalik pixel          | cocok untuk negasi visual        |

## 🎨 4. Visualisasi

Semua hasil ditampilkan dalam subplot agar mudah dibandingkan.

## 💾 5. Save Hasil

Semua output disimpan otomatis ke folder **/gambar**.

---

# 📸 Preview Hasil

> **Catatan:** Upload dulu gambar hasil ke folder `/gambar` lalu rename sesuai contoh agar preview muncul.

### 🔹 Operasi AND

```
![AND](gambar/hasil_and.png)
```

### 🔹 Operasi OR

```
![OR](gambar/hasil_or.png)
```

### 🔹 Operasi XOR

```
![XOR](gambar/hasil_xor.png)
```

### 🔹 Operasi NOT

```
![NOT](gambar/hasil_not.png)
```

---

# 📊 Tabel Hasil Operasi Logika

| Operasi | Deskripsi Visual                        | Output          |
| ------- | --------------------------------------- | --------------- |
| **AND** | Area gelap terlihat dominan             | `hasil_and.png` |
| **OR**  | Gambar tampak lebih terang              | `hasil_or.png`  |
| **XOR** | Menonjolkan perbedaan antara dua gambar | `hasil_xor.png` |
| **NOT** | Warna dibalik (negatif film)            | `hasil_not.png` |

---

# 🛠️ Cara Menjalankan
 1️⃣ Clone repo

```bash
git clone https://github.com/fika246/metode-manipulasi-citra-digital-nur-fika-prihatin.git
```
 2️⃣ Masuk folder

```bash
cd metode-manipulasi-citra-digital-nur-fika-prihatin
```
 3️⃣ Install library

```bash
pip install opencv-python numpy matplotlib
```
 4️⃣ Jalankan notebook

```bash
jupyter notebook
```

---

# 💡 Catatan Teknis

* Semua gambar HARUS berada dalam folder **/gambar**
* Format gambar: `.png` atau `.jpg`
* Jika ingin menambah operasi logika lain, tinggal duplikasi blok kode
* Direkomendasikan menggunakan Python 3.8+

---

# 📜 Lisensi

Proyek ini dibuat untuk keperluan akademik dan pembelajaran.
Silakan digunakan, dipelajari, dan dimodifikasi ✨
