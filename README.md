# Aplikasi Konversi Suhu (AppKonversiSuhuFrame)

Aplikasi ini adalah sebuah program sederhana berbasis Java Swing yang berfungsi untuk mengkonversi suhu antar berbagai skala (Celsius, Fahrenheit, Reamur, dan Kelvin). Dengan tampilan antarmuka grafis yang mudah dipahami, aplikasi ini memungkinkan pengguna untuk melakukan konversi suhu dalam dua arah (contoh: dari Celsius ke Fahrenheit dan sebaliknya) dengan cepat.

## Deskripsi

Aplikasi ini memungkinkan pengguna untuk:
- Memasukkan nilai suhu dalam satu satuan tertentu
- Memilih satuan tujuan untuk mengkonversi suhu
- Memilih arah konversi (dari satuan asal ke satuan tujuan atau sebaliknya)
- Melihat hasil konversi secara otomatis saat mengetik atau dengan tombol "Convert".

## Fitur Utama

- *Konversi Real-Time*: Aplikasi akan mengupdate hasil konversi secara otomatis saat pengguna mengetik.
- *Konversi Dua Arah*: Mendukung konversi dari satuan asal ke satuan tujuan dan sebaliknya.
- *Penanganan Error*: Menampilkan peringatan jika input tidak valid atau jika arah konversi belum dipilih.
- *Reset dan Keluar*: Memiliki tombol untuk menghapus input dan keluar dari aplikasi.
- *Dukungan Berbagai Skala Suhu*: Mendukung konversi antara Celsius, Fahrenheit, Reamur, dan Kelvin.

## Keunggulan

- *Antarmuka yang Ramah Pengguna*: GUI yang mudah digunakan untuk konversi suhu dengan cepat.
- *Pengecekan Error Otomatis*: Mencegah input karakter yang tidak valid dan menyediakan pesan error yang jelas.
- *Opsi yang Dapat Disesuaikan*: Fleksibilitas dengan konversi dua arah dan berbagai skala suhu.



### Prasyarat

- Java Development Kit (JDK) terinstal (direkomendasikan versi 8 atau lebih tinggi).
- IDE Java atau alat command-line untuk mengkompilasi dan menjalankan aplikasi.

### Menjalankan Aplikasi

1. Clone atau download proyek ini ke komputer Anda.
2. Buka proyek di IDE Java pilihan Anda, atau kompilasi melalui command line.
3. Jalankan kelas utama AppKonversiSuhuFrame untuk membuka GUI.
4. Di jendela aplikasi:
   - Masukkan nilai suhu di bidang input.
   - Pilih satuan asal dan satuan tujuan dari menu dropdown.
   - Pilih arah konversi.
   - Klik tombol "Convert" atau ketik di bidang input untuk melihat hasilnya.
   - Gunakan tombol "Clear" untuk menghapus semua bidang atau "Exit" untuk menutup aplikasi.

### Contoh Penggunaan

1. Masukkan nilai dalam Celsius.
2. Pilih "Fahrenheit" sebagai satuan tujuan.
3. Klik "Convert" atau lihat hasilnya secara langsung jika konversi otomatis diaktifkan.
4. Suhu yang telah dikonversi akan muncul di bidang hasil.

## Struktur Kode

- AppKonversiSuhuFrame: Frame utama aplikasi.
- konversiSuhu: Mengelola logika konversi berdasarkan satuan yang dipilih.
- konversiOtomatis: Mengupdate hasil secara otomatis saat pengguna mengetik.
- Komponen GUI dan event listener didefinisikan untuk menangani interaksi pengguna.

## Pembuat Aplikasi
Muhammad Ridhoni Ilham (2210010515)

## Demo
![Demo GIF](https://github.com/Ridhoni123/AplikasiKomversiSuhu/blob/main/img/Recording%202024-11-10%20181514.gif)
