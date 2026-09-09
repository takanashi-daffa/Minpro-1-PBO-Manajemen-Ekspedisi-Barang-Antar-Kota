# Mini Project 1 PBO - Manajemen Ekspedisi Barang Antar Kota

NAMA : Daffa Arkhabista

NIM : 2509116018

## Deskripsi Singkat Program

Program ini dibuat untuk mengelola data pada jasa ekspedisi barang antar kota. Program menggunakan bahasa Java dan menerapkan CRUD (Create, Read, Update, Delete).

Terdapat 3 data yang digunakan, yaitu pelanggan, barang, dan pengiriman. Data tersebut disimpan menggunakan ArrayList. Pengguna dapat menambah, melihat, mengubah, dan menghapus data.

Program ini dibuat sebagai Mini Project 1 pada praktikum PBO dengan menggunakan class, object, constructor, ArrayList, percabangan, dan perulangan.

## Alur Program

Saat program dijalankan, pengguna akan masuk ke menu utama yang terdiri dari:

1. Tambah Data
2. Lihat Data
3. Ubah Data
4. Hapus Data
5. Keluar

Pengguna memilih menu dengan memasukkan angka sesuai pilihan.

Pada menu **Tambah Data**, pengguna dapat memilih data Pelanggan, Barang, atau Pengiriman yang ingin ditambahkan.

Pada menu **Lihat Data**, pengguna dapat memilih data Pelanggan, Barang, atau Pengiriman untuk melihat data yang sudah tersimpan.

Pada menu **Ubah Data**, pengguna memilih jenis data kemudian memasukkan ID data yang ingin diubah.

Pada menu **Hapus Data**, pengguna memilih jenis data kemudian memasukkan ID data yang ingin dihapus.

Program akan terus berjalan sampai pengguna memilih menu **Keluar**.

## Nilai Tambah

### Access Modifier

Access modifier digunakan pada class Pelanggan, Barang, dan Pengiriman. Atribut pada ketiga class tersebut menggunakan `private`.

Contohnya pada class **Pelanggan**:

    private String idPelanggan;
    private String nama;
    private String noTelepon;
    private String alamat;

### Encapsulation

Encapsulation diterapkan dengan menggunakan atribut `private` serta getter dan setter.

Contohnya pada class **Pelanggan**:

    public String getNama(){
        return nama;
    }

    public void setNama(String nama){
        this.nama = nama;
    }

Getter digunakan untuk mengambil data, sedangkan setter digunakan untuk mengubah data.

