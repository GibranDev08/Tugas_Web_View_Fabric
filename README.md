# Tugas WebView – MIT App Inventor

Aplikasi Android sederhana yang dibuat dengan **MIT App Inventor** menggunakan komponen **WebView**. Saat dibuka, aplikasi langsung menampilkan sebuah website di dalam aplikasi tanpa berpindah ke browser.

## Identitas

| | |
|---|---|
| **Nama** | Mochammad Gibran K.R |
| **NPM** | 41155050240024 |
| **Program Studi** | Teknik Informatika |
| **Universitas** | Universitas Langlangbuana (UNLA) |
| **Mata Kuliah** | Pemograman Mobile |


## Deskripsi

Proyek ini adalah tugas untuk mempelajari komponen **WebView** pada MIT App Inventor. WebView memungkinkan aplikasi memuat dan menampilkan halaman web langsung di dalam layar aplikasi. Aplikasi ini memuat website: **https://www.unla.ac.id/**.

## Fitur

- Memuat website otomatis saat aplikasi dibuka (`Screen1.Initialize`)
- Menampilkan halaman web di dalam aplikasi menggunakan komponen WebView
- [tambahkan fitur lain, mis. tombol Kembali, Refresh, atau Beranda]

## Teknologi

- [MIT App Inventor](https://appinventor.mit.edu/)
- Komponen **WebView** (properti `HomeUrl` / blok `GoToUrl`)
- Android

## Komponen yang Digunakan

| Komponen | Fungsi |
|---|---|
| `Screen1` | Layar utama aplikasi |
| `WebViewer1` | Menampilkan halaman website |
| [komponen lain] | [fungsi] |

## Blok Program

Alur logika utama aplikasi:

```
when Screen1.Initialize
do  call WebViewer1.GoToUrl
        url  "https://contoh-website.com"
```

> Sesuaikan URL di atas dengan website yang dipakai pada proyek.

## Cara Menjalankan

### Opsi 1 – Impor file proyek (.aia)

1. Buka [MIT App Inventor](https://ai2.appinventor.mit.edu/) dan login dengan akun Google.
2. Pilih **Projects → Import project (.aia) from my computer**.
3. Pilih file `.aia` dari repositori ini.
4. Jalankan lewat **Connect → AI Companion** (scan QR code dengan aplikasi MIT AI2 Companion) atau **Build → Android App (.apk)**.

### Opsi 2 – Instal APK

1. Unduh file `.apk` dari repositori ini.
2. Izinkan instalasi dari sumber tidak dikenal di perangkat Android.
3. Buka file APK dan instal.

## Struktur Repositori

```
Tugas_Web_View_Fabric/
├── README.md
├── [nama-proyek].aia      # File proyek MIT App Inventor
├── [nama-proyek].apk      # Aplikasi siap instal
└── screenshots/           # Tangkapan layar aplikasi
```

## Tangkapan Layar

| Tampilan Awal | Tampilan Website |
|---|---|
| !<img width="575" height="1280" alt="WhatsApp Image 2026-11-16 at 09 43 20" src="https://github.com/user-attachments/assets/41cb0354-f740-4af0-9423-3ecbba483ffb" />) | !<img width="576" height="1280" alt="WhatsApp Image 2026-11-16 at 10 07 55" src="https://github.com/user-attachments/assets/10939368-aa9f-4359-9e39-ac6c038f2ab8" /> |

## Catatan

- Perangkat harus terhubung ke internet agar website dapat dimuat.
- Beberapa website membatasi tampilan di dalam WebView.

## Pembuat

**Mochammad Gibran K.R** – Teknik Informatika, Universitas Langlangbuana
GitHub: [GibranDev08](https://github.com/GibranDev08)
