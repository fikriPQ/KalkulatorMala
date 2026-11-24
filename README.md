# Kalkulator Scientific

Kalkulator scientific berbasis web dalam satu file HTML, tanpa framework dan tanpa proses build. Tampilannya seperti kalkulator meja dengan layar LCD dan gulungan kertas riwayat.

## Fitur

- Operasi dasar dengan urutan operasi yang benar, tanda kurung, dan perkalian otomatis (`2π`, `3(4+1)`)
- Trigonometri: `sin`, `cos`, `tan` dan kebalikannya (`sin⁻¹`, `cos⁻¹`, `tan⁻¹`), mode **DEG / RAD**
- Logaritma dan eksponen: `ln`, `log`, `eˣ`, `10ˣ`
- Pangkat dan akar: `x²`, `x³`, `xʸ`, `√x`, `∛x`, `ʸ√x`
- Lainnya: `n!` (termasuk pecahan, lewat fungsi gamma), `1/x`, `|x|`, `%`, `±`, angka acak
- Konstanta `π`, `e`, dan `Ans` (hasil terakhir)
- Memori: `MC`, `MR`, `M+`, `M−`
- Riwayat perhitungan; klik untuk memakai hasil lama, tombol salin hasil
- Format angka Indonesia (titik ribuan, koma desimal)
- Dukungan keyboard dan tema terang/gelap otomatis
- Riwayat, memori, dan mode sudut tersimpan di browser (localStorage)

## Cara pakai

Buka `index.html` langsung di browser. Tidak perlu instalasi.

Fungsi seperti `sin`, `log`, atau `x²` bekerja pada angka di layar, atau pada isi kurung tepat sebelumnya. Contoh: `(30 + 15)` lalu `sin` → sin(45).

### Pintasan keyboard

| Tombol | Fungsi |
|---|---|
| `0`–`9`, `.` atau `,` | Angka dan desimal |
| `+` `-` `*` `/` | Operator |
| `^` | Pangkat |
| `!` | Faktorial |
| `%` | Persen |
| `(` `)` | Kurung |
| `Enter` atau `=` | Hasil |
| `Backspace` | Hapus satu karakter |
| `Esc` | Reset |

## Publikasi dengan GitHub Pages

1. Unggah isi folder ini ke repository GitHub baru.
2. Buka **Settings → Pages**.
3. Di **Source**, pilih **Deploy from a branch**, lalu pilih branch `main` dan folder `/ (root)`.
4. Klik **Save**. Setelah beberapa menit, situs tersedia di `https://<username>.github.io/<nama-repo>/`.

## Teknologi

HTML, CSS, dan JavaScript murni. Font Outfit dan Chivo Mono dimuat dari Google Fonts.
