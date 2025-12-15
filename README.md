# Paint 2D - Aplikasi Grafika Komputer

Aplikasi Paint 2D interaktif dengan fitur lengkap: Drawing, Transform, Selection, Windowing & Clipping.

## Fitur Utama

### 🎨 Drawing Tools
- **Point**: Gambar titik
- **Line**: Gambar garis
- **Rectangle**: Gambar persegi panjang
- **Ellipse**: Gambar elips

### ✨ Transform Operations
- **Translate**: Geser objek dengan arrow keys (↑↓←→)
- **Rotate**: Putar objek dengan R/r (15° per klik)
- **Scale**: Perbesar/perkecil objek dengan +/- (10% per klik)

### 🖱️ Selection & Multi-Select
- Klik untuk memilih objek tunggal
- Shift+Klik untuk multi-select
- Ctrl+A untuk select all

### 🪟 Clipping Window
- Set area clipping dengan mode Window
- Toggle clipping dengan tombol Clip atau tekan C

### 🎨 Atribut Gambar
- 12 warna dalam palette
- Slider untuk ketebalan garis (1-20px)
- Toggle Fill untuk solid color

### ↩️ Undo/Redo
- Ctrl+Z untuk Undo
- Ctrl+Y untuk Redo
- History hingga 50 langkah

### 💾 Save & Clear
- Save: Simpan gambar sebagai PNG
- Clear: Hapus semua objek

## Cara Deploy ke GitHub Pages

### Langkah 1: Upload ke GitHub
1. Buat repository baru di GitHub
2. Upload ketiga file ini:
   - `index.html`
   - `sketch.js`
   - `README.md` (opsional)

### Langkah 2: Aktifkan GitHub Pages
1. Buka repository Anda
2. Klik **Settings** > **Pages**
3. Di bagian **Source**, pilih branch `main` atau `master`
4. Pilih folder `/ (root)`
5. Klik **Save**

### Langkah 3: Akses Website
Setelah beberapa menit, website Anda akan tersedia di:
```
https://[username].github.io/[repository-name]/
```

## Kontrol

### Mouse
- **Klik**: Gambar point / Pilih objek
- **Drag**: Gambar shape (garis, persegi, elips)
- **Shift+Klik**: Multi-select objek

### Keyboard (objek terpilih)
- **Arrow Keys (↑↓←→)**: Geser objek
- **R/r**: Rotasi searah/berlawanan jarum jam
- **+/-**: Perbesar/perkecil objek (10%)
- **Delete/Backspace**: Hapus objek
- **Ctrl+A**: Pilih semua objek
- **Ctrl+Z**: Undo
- **Ctrl+Y**: Redo
- **Escape**: Batal seleksi

### Clipping Window
- Pilih mode Window
- Drag mouse untuk set area clipping
- Klik tombol 'Clip' atau tekan C untuk aktifkan

### Lainnya
- **H**: Toggle panduan bantuan
- **C**: Toggle clipping on/off

## Teknologi

- **p5.js**: Library JavaScript untuk creative coding
- **HTML5 Canvas**: Untuk rendering grafis
- **Vanilla JavaScript**: Tanpa framework tambahan

## Browser Support

- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## Lisensi

Free to use for educational purposes.

---

**Dibuat untuk Tugas Grafika Komputer**
