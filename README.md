# Lab2Web - Praktikum 2: CSS Dasar
Repository template untuk tugas Praktikum 2 (CSS Dasar).

### Isi folder
- `step1_structure.html`  -> Struktur HTML dasar (tanpa CSS)
- `step2_internal.html`   -> Menambahkan CSS internal (style di <head>)
- `step3_inline.html`     -> Menambahkan inline CSS pada paragraf
- `step4_external.html`   -> Menggunakan CSS eksternal (`style_eksternal.css`)
- `step5_selectors.html`  -> Contoh specificity: elemen, id, class, inline
- `style_eksternal.css`   -> File CSS eksternal
- `screenshots/`          -> (kosong) Tempat simpan screenshot hasil praktikum

---
## Cara pakai (langkah demi langkah)
1. Download/unzip folder ini.
2. Buka file `step1_structure.html` di browser (double-click atau `file://`).
   - **Screenshot 1**: tangkapan layar halaman ini (simpan sebagai `screenshots/01_structure.png`)
3. Buka file `step2_internal.html` di browser untuk melihat efek internal CSS.
   - **Screenshot 2**: `screenshots/02_internal.png`
4. Buka file `step3_inline.html` untuk melihat paragraf yang menggunakan inline CSS.
   - **Screenshot 3**: `screenshots/03_inline.png`
5. Buka file `step4_external.html` untuk melihat efek CSS eksternal (`style_eksternal.css`).
   - **Screenshot 4**: `screenshots/04_external.png`
6. Buka file `step5_selectors.html` untuk melihat contoh specificity (ID > class, inline > both).
   - **Screenshot 5**: `screenshots/05_specificity.png`
7. Ambil juga screenshot tampilan file/folder di editor (mis. VSCode) sebelum commit:
   - **Screenshot 6**: `screenshots/06_editor_files.png`

---
## Keterangan singkat jawaban tugas 
1. **Eksperimen CSS**: ubah properti/warna/font pada file `style_eksternal.css` atau internal CSS (`step2_internal.html`) untuk melihat perubahan.
2. **Perbedaan `h1 {}` vs `#intro h1 {}`**: `h1 {}` memengaruhi semua <h1>, sedangkan `#intro h1 {}` hanya memengaruhi <h1> di dalam elemen dengan id="intro".
3. **Prioritas Internal/Eksternal/Inline**: prioritasnya `inline > internal > external` jika specificity sama.
4. **ID vs Class**: ID memiliki specificity lebih tinggi dari class, sehingga aturan ID mengalahkan class untuk properti yang sama.

---
