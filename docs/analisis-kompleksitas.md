# Analisis Kompleksitas Algoritma

## 1. Analisis Waktu

| Operasi | Kompleksitas | Alasan |
|---|---|---|
| Insert di awal | O(1) | Mengubah referensi head tanpa penelusuran |
| Search | O(n) | Memeriksa node satu per satu |
| Delete berdasarkan kode | O(n) | Mencari node sebelum menghapus |
| Traversal | O(n) | Mengunjungi seluruh node |

Catatan: Pada program ini, pengecekan kode duplikat sebelum Insert membutuhkan O(n), sehingga keseluruhan proses penambahan melalui menu memiliki kompleksitas O(n).

## 2. Analisis Memori

Linked List menggunakan memori O(n) untuk menyimpan n barang.

Setiap node menyimpan data barang serta referensi menuju node berikutnya.

## 3. Pengujian Program

| No. | Pengujian | Hasil yang diharapkan | Hasil aktual |
|---|---|---|---|
| 1 | Menambah BRG001 | Barang berhasil ditambahkan | Belum dicatat |
| 2 | Menambah BRG002 | Barang berhasil ditambahkan | Belum dicatat |
| 3 | Mencari BRG001 | Data ditemukan | Belum dicatat |
| 4 | Mencari kode tidak tersedia | Barang tidak ditemukan | Belum dicatat |
| 5 | Menghapus BRG001 | Barang berhasil dihapus | Belum dicatat |
| 6 | Menampilkan semua barang | Daftar barang muncul | Sudah terlihat |
| 7 | Menampilkan daftar kosong | Pesan daftar kosong | Belum dicatat |
| 8 | Menambah kode duplikat | Penambahan ditolak | Belum dicatat |

Hasil aktual harus diperbarui berdasarkan pengujian langsung melalui terminal.

## 4. Kesimpulan Analisis

Singly Linked List efisien untuk penambahan node di awal daftar dengan O(1). Namun, pencarian dan penghapusan berdasarkan kode membutuhkan O(n).

Struktur ini sesuai untuk pembelajaran operasi dasar struktur data dinamis, meskipun bukan pilihan paling cepat untuk pencarian inventori berskala besar.