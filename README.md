# SISTEM INVENTORI BARANG
## Implementasi Singly Linked List Menggunakan Java

**Mata Kuliah:** Struktur Data  
**Program Studi:** Teknik Informatika  
**Nama Anggota Kelompok:** 

1. Ryan Robbi Antoni (25520002)
2. Sony Laksana (25520004)
3. Fregianto (25520006)
4. Hendra Hendrawan (25520007)

### 1. Deskripsi Program

Program Inventori Barang merupakan aplikasi sederhana berbasis terminal yang dibuat menggunakan bahasa pemrograman Java.

Program ini menggunakan struktur data Singly Linked List untuk menyimpan dan mengelola data barang berupa kode barang, nama barang, dan jumlah stok.

### 2. Tujuan Program

- Memahami konsep struktur data Singly Linked List.
- Mengimplementasikan operasi Insert, Delete, Search, dan Traversal.
- Mengelola data inventori secara dinamis.
- Menganalisis kompleksitas waktu setiap operasi.

### 3. Alasan Memilih Singly Linked List

Singly Linked List dipilih karena jumlah data barang dapat berubah secara dinamis.

Struktur ini memungkinkan penambahan node di awal daftar dengan kompleksitas O(1), tanpa perlu menggeser elemen seperti pada Array.

Namun, pencarian dan penghapusan berdasarkan kode barang membutuhkan penelusuran node secara berurutan dengan kompleksitas O(n).

### 4. Fitur Program

1. Tambah Barang (Insert).
2. Hapus Barang (Delete).
3. Cari Barang (Search).
4. Tampilkan Semua Barang (Traversal).
5. Keluar dari Program.

### 5. Struktur File

- `Main.java` — menu utama dan input pengguna.
- `Node.java` — struktur node untuk menyimpan data barang.
- `LinkedListBarang.java` — implementasi operasi Linked List.

### 6. Cara Menjalankan

1. Instal Java JDK dan Visual Studio Code.
2. Buka folder proyek di VS Code.
3. Pastikan ketiga file Java berada dalam satu folder.
4. Jalankan file `Main.java`.
5. Pilih menu sesuai kebutuhan.

Alternatif melalui terminal:

```text
javac Main.java Node.java LinkedListBarang.java
java Main
```

### 7. Kesimpulan

Singly Linked List dapat digunakan untuk membuat sistem inventori sederhana dengan jumlah data yang dinamis.

Melalui implementasi ini, konsep node, head, reference, serta operasi dasar Linked List dapat dipelajari secara langsung.

Data masih disimpan di memori sehingga akan hilang ketika program ditutup.
