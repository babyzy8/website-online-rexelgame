# Rexel Game

Website untuk konsumen Rexel Game. Pelanggan bisa melihat daftar harga service, memilih game PS4 dari katalog, dan membuat pesanan langsung dari HP atau PC tanpa perlu login.

## Fitur

- **Service**: daftar harga service stik dan perangkat.
- **List Game PS4**: katalog game lengkap dengan gambar cover dan harga per kategori ukuran.
- **Order**: pilih game atau item dari katalog, lalu kirim pesanan.
- **Pembayaran QRIS**: pembayaran memakai QRIS toko.
- Tampilan responsif, nyaman dibuka di HP maupun PC.

## Harga Game

| Kategori | Ukuran | Harga |
|----------|--------|-------|
| Kecil | 1-5 GB | Rp20.000 |
| Sedang | 5-50 GB | Rp30.000 |
| Besar | 50-200 GB | Rp50.000 |
| Terbaru (Bola Terupdate) | - | Rp80.000 |
| PS2 (bisa dimainkan di PS4) | - | Rp20.000 |

Promo: 4 game kategori sedang = Rp100.000.

## Struktur File

```
index.html     halaman utama
games.js       daftar game (nama, kategori, nama file cover)
*.png          gambar cover game
```

## Cara Menambah Game

Buka `games.js`, lalu tambahkan satu baris di dalam daftar `GAMES`:

```js
{ n: "Nama Game", t: "sedang", img: "nama-game.png" },
```

- `n`: nama game
- `t`: kategori (`kecil`, `sedang`, `besar`, `terbaru`, atau `ps2`)
- `img`: nama file cover. Gunakan huruf kecil dan ganti spasi dengan `-`. Simpan file di folder yang sama dengan `index.html`.

Jika `img` tidak diisi, otomatis tampil cover berwarna dengan nama game.

## Menjalankan di Komputer

1. Buka folder proyek di VS Code.
2. Jalankan dengan ekstensi Live Server, atau klik dua kali `index.html`.

## Deploy

Bisa dipasang gratis lewat GitHub Pages atau Netlify. Cukup unggah seluruh isi folder, termasuk semua gambar cover.

## 0851-7244-7090
## @rexelgame_

Rexel Game, Cianjur.# website-online-rexelgame
Website katalog Rexel Game: daftar harga service, list game PS4 lengkap dengan cover, dan pemesanan online.
