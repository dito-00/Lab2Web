# Lab2Web - Praktikum 2: CSS Dasar

### Isi folder
- `step1_structure.html`  -> Struktur HTML dasar (tanpa CSS)
- `step2_internal.html`   -> Menambahkan CSS internal (style di <head>)
- `step3_inline.html`     -> Menambahkan inline CSS pada paragraf
- `step4_external.html`   -> Menggunakan CSS eksternal (`style_eksternal.css`)
- `step5_selectors.html`  -> Contoh specificity: elemen, id, class, inline
- `style_eksternal.css`   -> File CSS eksternal

---
## langkah demi langkah (screenshot)
1. Buka file `step1_structure.html` di browser (double-click atau `file://`).
   <img width="1709" height="276" alt="image" src="https://github.com/user-attachments/assets/7b396142-ea0e-4f97-b138-ec9f8a87bdb3" />
   <img width="1655" height="565" alt="image" src="https://github.com/user-attachments/assets/cdd17963-6168-48c4-9708-1427d4d956a7" />


2. Buka file `step2_internal.html` di browser untuk melihat efek internal CSS.
   <img width="1910" height="439" alt="image" src="https://github.com/user-attachments/assets/81d5de05-07b7-4fe4-9c70-10a98d2aa2f9" />
   <img width="628" height="873" alt="image" src="https://github.com/user-attachments/assets/100c9970-1dd3-4704-a5b3-de5bac71ab19" />
   <img width="1681" height="566" alt="image" src="https://github.com/user-attachments/assets/3d2165b4-bd55-4335-942c-d36b20953235" />


3. Buka file `step3_inline.html` untuk melihat paragraf yang menggunakan inline CSS.
   <img width="1898" height="431" alt="image" src="https://github.com/user-attachments/assets/acbcbdb3-d8c3-45f8-9dbe-a66bc49d6029" />
   <img width="1028" height="703" alt="image" src="https://github.com/user-attachments/assets/0443e14e-ce3e-4566-bd7f-f4bdc3209fa4" />


4. Buka file `step4_external.html` untuk melihat efek CSS eksternal (`style_eksternal.css`).
   <img width="1908" height="399" alt="image" src="https://github.com/user-attachments/assets/651c052f-fcad-4b22-a78e-f6e1cc61dd94" />
   <img width="1684" height="470" alt="image" src="https://github.com/user-attachments/assets/fdb73179-6481-4662-b445-c6261ff14b3f" />


5. Buka file `step5_selectors.html` untuk melihat contoh specificity (ID > class, inline > both).
   <img width="1910" height="448" alt="image" src="https://github.com/user-attachments/assets/20db041d-6d5f-47be-a5de-9a33244c5608" />
   <img width="1692" height="671" alt="image" src="https://github.com/user-attachments/assets/3c3d1241-0839-4369-9fae-442662b0b867" />

6. File style_eksternal.css
   <img width="1717" height="874" alt="image" src="https://github.com/user-attachments/assets/d5124111-fa52-4694-851c-1aa3f7873bd1" />
   <img width="1729" height="378" alt="image" src="https://github.com/user-attachments/assets/a8222775-a09d-4776-897a-9aea9f1640ba" />


---
## Keterangan singkat jawaban tugas 
1. **Eksperimen CSS**: ubah properti/warna/font pada file `style_eksternal.css` atau internal CSS (`step2_internal.html`) untuk melihat perubahan.
2. **Perbedaan `h1 {}` vs `#intro h1 {}`**: `h1 {}` memengaruhi semua <h1>, sedangkan `#intro h1 {}` hanya memengaruhi <h1> di dalam elemen dengan id="intro".
3. **Prioritas Internal/Eksternal/Inline**: prioritasnya `inline > internal > external` jika specificity sama.
4. **ID vs Class**: ID memiliki specificity lebih tinggi dari class, sehingga aturan ID mengalahkan class untuk properti yang sama.
---
