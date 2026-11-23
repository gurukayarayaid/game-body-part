# GAME DRAG BODY PARTS — Parts of the Body (Bahasa Inggris Kelas 3 SD)

Game edukasi mencocokkan gambar dan kata bertema **Parts of the Body** dengan drag and drop.
Cocok untuk desktop, Interactive Flat Panel (IFP), dan layar sentuh.

## Fitur

- 16 gambar bagian tubuh fotorealistis (head, hair, eye, ear, nose, mouth, teeth, neck,
  shoulder, arm, hand, fingers, leg, knee, foot, toes)
- Drag and drop dengan mouse maupun sentuh (Pointer Events), plus fallback ketuk-kata lalu ketuk-gambar
- Pengaturan jumlah pemain (1–4), jumlah soal (6/8/10/12/16), dan timer per soal (15/20/30/45 detik atau tanpa batas)
- Skor: 100 poin per jawaban benar + bonus 5 poin per detik sisa
- Papan skor langsung, animasi benar/salah, efek suara, tombol layar penuh
- Pengaturan terakhir disimpan di `localStorage`

## Menjalankan

Situs statis tanpa build. Buka `index.html` langsung, atau jalankan server statis lokal:

```bash
python -m http.server 8000
```

## Struktur

```
index.html
css/style.css
js/data.js     # daftar 16 bagian tubuh
js/game.js     # logika permainan
assets/parts   # 16 gambar bagian tubuh
```
