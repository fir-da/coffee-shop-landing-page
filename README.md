# Kopi Teduh — Landing Page

Landing page studi kasus coffee shop, dibuat sebagai satu file HTML mandiri (tanpa build step, tanpa dependency lokal).

## Cara pakai

Langsung buka `index.html` di browser — tidak perlu server atau instalasi apa pun.

## Deploy ke GitHub Pages

1. Buat repo baru, upload `index.html` ke root repo (nama file harus `index.html` supaya otomatis terbaca sebagai halaman utama).
2. Masuk ke **Settings → Pages**.
3. Di bagian **Source**, pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Tunggu 1–2 menit, halaman akan aktif di `https://<username>.github.io/<nama-repo>/`.

## Struktur konten

- Hero
- Kenapa pilih kami (USP)
- Menu andalan
- Suasana / galeri
- Testimoni
- FAQ (accordion, native `<details>`, tanpa JS tambahan)
- Lokasi & CTA (WhatsApp)

## Kustomisasi cepat

Semua warna diatur lewat CSS variable di bagian atas `<style>` (`:root`), jadi ganti palet cukup di satu tempat:

```css
--parchment:#F5EFE2;   /* warna latar utama */
--espresso:#2A1C12;    /* warna teks utama */
--moss:#5B6B45;        /* aksen utama / tombol */
--mustard:#C99A3B;     /* aksen sekunder */
```

Teks, harga menu, alamat, dan nomor WhatsApp ada langsung di dalam `index.html` — cari bagian `<section class="menu">` dan `<section class="lokasi">` untuk mengganti.
