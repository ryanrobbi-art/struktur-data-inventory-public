# Pseudocode Sistem Inventori Barang

## A. Insert (Tambah Barang)

```text
MULAI
  INPUT kode, nama, stok
  JIKA data tidak valid
    TAMPILKAN pesan kesalahan
  JIKA kode sudah digunakan
    TAMPILKAN pesan duplikat
  SELAIN ITU
    BUAT node baru
    nodeBaru.next = head
    head = nodeBaru
    TAMPILKAN berhasil
SELESAI
```

## B. Search (Cari Barang)

```text
MULAI
  current = head
  SELAMA current tidak NULL
    JIKA kode cocok
      TAMPILKAN data barang
      SELESAI
    current = current.next
  TAMPILKAN barang tidak ditemukan
SELESAI
```

## C. Delete (Hapus Barang)

```text
MULAI
  JIKA head NULL
    TAMPILKAN daftar kosong
  JIKA kode head cocok
    head = head.next
  SELAIN ITU
    TELUSURI node berikutnya
    JIKA kode ditemukan
      HUBUNGKAN node sebelumnya
      KE node setelah yang dihapus
    JIKA tidak ditemukan
      TAMPILKAN barang tidak ditemukan
SELESAI
```

## D. Traversal (Tampilkan Semua Barang)

```text
MULAI
  current = head
  JIKA head NULL
    TAMPILKAN daftar kosong
  SELAMA current tidak NULL
    TAMPILKAN data barang
    current = current.next
SELESAI
```