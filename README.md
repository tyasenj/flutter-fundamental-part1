# hello_world

A new Flutter project

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## **Praktikum 1: Membuat Project Flutter Baru**

**Langkah 1:**

Buka VS Code, lalu tekan tombol Ctrl + Shift + P maka akan tampil Command Palette, lalu ketik Flutter. Pilih New Application Project.

<img src= 'gambar/p1_gambar1.jpg'>

**Langkah 2**

Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.

<img src= 'gambar/p1_gambar2.jpg'>

**Langkah 3**

Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesa

<img src= 'gambar/p1_gambar3.jpg'>

**Langkah 4**

Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" artinya Anda telah berhasil membuat project Flutter baru.

<img src= 'gambar/p1_gambar4.jpg'>

## **Praktikum 2: Menghubungkan Perangkat Android atau Emulator**

<img src= 'gambar/p2_gambar1.jpg'>

## **Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum**

**Langkah 1:**

Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"

<img src= 'gambar/p3_gambar1.jpg'>

**Langkah 2**

Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut.

<img src= 'gambar/p3_gambar2.jpg'>

**Langkah 3**

Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.

<img src= 'gambar/p3_gambar3.jpg'>

**Langkah 4**

Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.

<img src= 'gambar/p3_gambar4.jpg'>

**Langkah 5**

Beri pesan commit "tambah gitignore" lalu klik Commit (✔)

<img src= 'gambar/p3_gambar5.jpg'>

**Langkah 6**

Lakukan push dengan klik bagian menu titik tiga > Push

<img src= 'gambar/p3_gambar6.png'>

**Langkah 7**

Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"

<img src= 'gambar/p3_gambar7.png'>

**Langkah 8**

Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote

<img src= 'gambar/p3_gambar8_a.png'>

Setelah berhasil, tulis remote name dengan "origin"

<img src= 'gambar/p3_gambar8_b.png'>

**Langkah 9**

Lakukan hal yang sama pada file README.md mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.

<img src= 'gambar/p3_gambar9.jpg'>

**Langkah 10**

Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.

<img src= 'gambar/p3_gambar10.jpg'>

**Langkah 11**

Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.

<img src= 'gambar/p3_gambar11.jpg'>

**Langkah 12**

Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.

## **Praktikum 4: Menerapkan Widget Dasar**

**Langkah 1: Cupertino Button dan Loading Bar**

Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

<img src= 'gambar/p4_gambar1.jpg'>

**Langkah 2: Floating Action Button (FAB)**

Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.

Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

<img src= 'gambar/p4_gambar2.jpg'>

## **Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino**

**Langkah 1: Cupertino Button dan Loading Bar**

Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

<img src= 'gambar/p5_gambar1.jpg'>

**Langkah 2: Floating Action Button (FAB)**

Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.

Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

<img src= 'gambar/p5_gambar2.jpg'>

**Langkah 3: Scaffold Widget**

Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.

Ubah isi kode main.dart seperti berikut.

<img src= 'gambar/p5_gambar3.jpg'>

**Langkah 4: Dialog Widget**

Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.

Ubah isi kode main.dart seperti berikut.

<img src= 'gambar/p5_gambar4_alert.jpg'>

<img src= 'gambar/p5_gambar4_showdialog.jpg'>

**Langkah 5: Input dan Selection Widget**

Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.

Contoh penggunaan TextField widget adalah sebagai berikut:

<img src= 'gambar/p5_gambar5.jpg'>

**Langkah 6: Date and Time Pickers**

Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.

<img src= 'gambar/p5_gambar6_a.jpg'>

<img src= 'gambar/p5_gambar6_b.jpg'>

Kode Your first Flutter: https://github.com/tyasenj/namer_app/
