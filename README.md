# Tugas Sesi #2 — Prototype WebView MIT App Inventor

Proyek ini merupakan prototipe aplikasi Android yang dibuat menggunakan MIT App Inventor. Aplikasi menampilkan situs berita teknologi Kompas Tekno di dalam komponen WebViewer.

## Anggota Kelompok

| Nama | NPM |
|---|---|
| Ardiyanti Daffa Maisan | 41155050240022 |
| Lutfi Alfiqri | 41155050240002 |
| M. Ridho Saputra | 4155050240010 |

## Fitur

- Membuka halaman Kompas Tekno saat aplikasi dijalankan.
- Menampilkan situs di dalam aplikasi menggunakan WebViewer.
- Tombol **BERANDA** untuk kembali ke halaman awal.
- Tombol **MUAT ULANG** untuk memuat ulang halaman.
- Mengikuti tautan yang dibuka dari halaman berita.

## Komponen dan blok utama

| Komponen | Fungsi |
|---|---|
| `WebViewerNews` | Menampilkan `https://tekno.kompas.com/` di dalam aplikasi. |
| `BtnHome` | Memanggil `WebViewerNews.GoHome`. |
| `BtnReload` | Memanggil `WebViewerNews.Reload`. |

## Struktur berkas

```text
TUGAS 2 - PROTOTYPE WEBVIEW MIT APP INVENTOR/
├── README.md
├── TeknoUpdateMIT.aia
└── SumberProyek/
    ├── youngandroidproject/project.properties
    └── src/appinventor/ai_ardiyanti/TeknoUpdateMIT/
        ├── Screen1.scm
        └── Screen1.bky
```

- `TeknoUpdateMIT.aia` adalah arsip sumber proyek untuk diimpor ke MIT App Inventor.
- `SumberProyek/` berisi salinan pengaturan proyek, desain layar, dan blok.

## Cara mengimpor dan menjalankan

1. Buka [MIT App Inventor](https://ai2.appinventor.mit.edu/) dan masuk ke akun Anda.
2. Pilih **Projects → Import project (.aia) from my computer**.
3. Pilih berkas `TeknoUpdateMIT.aia`.
4. Untuk mencoba di HP, pasang **MIT AI2 Companion**, lalu pilih **Connect → AI Companion** di App Inventor dan pindai QR code.
5. Untuk membuat APK, pilih **Build → Android App (.apk)**. Setelah proses selesai, unduh APK yang dihasilkan.

> Berkas APK belum disertakan. APK perlu dibuat dari menu **Build** setelah proyek diimpor ke MIT App Inventor.

Aplikasi memerlukan koneksi internet untuk memuat situs berita.

## W PHONE
<img width="739" height="1600" alt="2 F" src="https://github.com/user-attachments/assets/f1b69376-a673-40fa-b1ca-6245577badc3" />
