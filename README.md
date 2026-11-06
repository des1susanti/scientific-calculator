# SciCalc — Scientific Calculator

Kalkulator saintifik modern dengan tema gelap dan efek kaca (*glassmorphism*). Dibuat dalam **satu file** `index.html` (HTML + CSS + Vanilla JavaScript), tanpa framework dan tanpa proses build.

## Fitur

- Operasi dasar: `+ − × ÷`, persen (`200 + 10% = 220`), kurung, `mod`
- Trigonometri: sin, cos, tan, dan inversnya (tombol **2nd**)
- Mode sudut **DEG / RAD**
- Logaritma & eksponen: log, ln, eˣ, 10ˣ, xʸ, x², √x, akar pangkat n (`3 ⁿ√ 27 = 3`)
- Konstanta π dan e, faktorial `x!`, kebalikan `1/x`, tombol `Ans`, ubah tanda `±`
- Memori: MC, MR, M+, M−
- Hasil langsung tampil saat mengetik, kurung yang belum ditutup ditutup otomatis
- Riwayat 50 perhitungan terakhir (tersimpan di browser)
- Pesan error yang jelas: pembagian dengan nol, di luar domain, sintaks salah, dll.
- Tanpa `eval()`: ekspresi dihitung oleh parser sendiri
- Responsif (desktop & HP) dan mendukung keyboard

## Pintasan Keyboard

| Tombol | Fungsi |
|---|---|
| `0–9` `.` | Angka |
| `+` `-` `*` `/` `^` `%` `!` `(` `)` | Operator |
| `Enter` / `=` | Hitung |
| `Backspace` | Hapus satu karakter |
| `Esc` | Hapus semua |
| `S` `C` `T` | sin, cos, tan |
| `L` / `G` | ln / log |
| `R` / `Q` | √x / x² |
| `P` / `E` | π / e |
| `I` | 2nd (invers) |
| `D` | Ganti DEG/RAD |
| `H` | Buka/tutup riwayat |

## Menjalankan

**Lokal:** buka `index.html` langsung di browser, atau di VS Code klik kanan → *Open with Live Server*.

**Online (GitHub Pages):**
1. Unggah `index.html` dan `README.md` ke repository GitHub.
2. Buka **Settings → Pages**.
3. Pada *Source* pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Setelah 1–2 menit aplikasi dapat diakses di `https://<username>.github.io/<nama-repo>/`.

## Teknologi

HTML5 · CSS3 (Grid, backdrop-filter) · JavaScript ES2020 (Vanilla)

## Lisensi

MIT
