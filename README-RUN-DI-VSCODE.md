# Cara Run Website di VS Code

File website utama tetap `index.html`. Saya hanya menambahkan konfigurasi NPM agar web bisa dilihat live lewat VS Code.

## Langkah menjalankan

1. Extract ZIP ini.
2. Buka folder hasil extract di VS Code.
3. Buka Terminal di VS Code:
   - Menu: **Terminal > New Terminal**
4. Jalankan:

```bash
npm install
```

5. Setelah selesai, jalankan:

```bash
npm run dev
```

6. Buka link yang muncul di terminal, biasanya:

```text
http://localhost:5173/
```

## Perintah tambahan

Untuk membuat versi build:

```bash
npm run build
```

Untuk melihat hasil build:

```bash
npm run preview
```

## Catatan

- Isi halaman lama tidak dihapus.
- Konten utama tetap ada di `index.html`.
- Folder gambar/audio tetap dipakai seperti sebelumnya.
- File yang ditambahkan hanya untuk menjalankan web dengan NPM/Vite.
