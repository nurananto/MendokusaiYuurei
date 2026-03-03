# Mendokusai Yuurei desu ga, Watashi to Koi Shite Kuremasu ka?

> Seorang Mahasiswa, Mamoru Suou mengalami serangkaian kejadian buruk: pencarian kerjanya tidak berjalan lancar, dan dia harus keluar dari tempat tinggalnya. Namun, dia bertemu dengan agen properti yang menunjukkan sebuah properti ideal. Meskipun agak tua, ukuran dan harga sewanya sangat baik, jadi dia segera pindah... Setelah pindahan selesai dengan aman, malam itu Mamoru bertemu Madoka, hantu dengan kecantikan luar biasa. Madoka menyentuh leher Mamoru dengan bibirnya yang menggoda... dan malam penuh kenikmatan dan teror dimulai...

---

## Info

| | |
|---|---|
| Judul | Mendokusai Yuurei desu ga, Watashi to Koi Shite Kuremasu ka? |
| Judul Alternatif | めんどくさい幽霊ですが私と恋してくれますか？ |
| Author | Shiogama Ume |
| Artist | Kurosaki Koko |
| Tipe | Webtoon (Berwarna) |
| Genre | Seinen · Comedy · Drama · Romance · Horror · Mystery · Ghost |

## Link

- [MangaDex](https://mangadex.org/title/f2923e0c-8b5e-4758-86ab-5aecc9f6689f/mendokusai-yurei-desu-ga-watashi-to-koi-shite-kuremasu-ka)
- [Raw](https://bookwalker.jp/series/517234/)

---

## Struktur

```
MendokusaiYuurei/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)