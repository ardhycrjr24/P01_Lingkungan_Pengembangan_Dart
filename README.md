# P01 - Lingkungan Pengembangan Dart

**Nama:** Ardiansyah  
**NIM:** 6304250091  
**Dosen Pengampu:** Depandi Enda, S.ST., M.Kom

Praktikum 1 mata kuliah Pemrograman Multiplatform: menyiapkan lingkungan pengembangan Dart dan membuat aplikasi Dart pertama.

## Tujuan

- Mempersiapkan lingkungan pengembangan Dart.
- Membuat dan menjalankan aplikasi Dart pertama.

## Alat yang Digunakan

- Flutter SDK (Dart)
- Visual Studio Code + extension Dart
- Git
- DartPad (https://dartpad.dev)

## Struktur Folder

```
P01_PengenalanDart/
├── ex1_pertama.dart    # Program Dart pertama
├── ex2_kedua.dart      # Program dengan argumen
└── ex3_dartpad.dart    # Latihan di DartPad
```

## Cara Menjalankan

Masuk ke folder `P01_PengenalanDart`, lalu jalankan:

```bash
# Program pertama
dart ex1_pertama.dart

# Program dengan argumen
dart ex2_kedua.dart Apel Durian Dendan Mangga

# Kompilasi menjadi executable
dart compile exe ex1_pertama.dart -o ex1_pertama
./ex1_pertama
```

`ex3_dartpad.dart` dijalankan melalui https://dartpad.dev.

## Output

- `ex1_pertama.dart` → `Saya telah berhasil menggunakan Dart SDK!`
- `ex2_kedua.dart` → menampilkan setiap argumen: `Apel`, `Durian`, `Dendan`, `Mangga`
- `ex3_dartpad.dart` → `Saya kuliah di Politeknik Negeri Bengkalis jurusan Teknik Informatika program studi Rekayasa Perangkat Lunak`

## Catatan

- Modul asli menggunakan Windows (`setx`, `D:\FlutterEnv`, `dart2native`, `.exe`).
- Di macOS/Linux, pengaturan PATH dilakukan lewat `~/.zshrc`/`~/.bashrc`, dan `dart2native` diganti `dart compile exe`.
