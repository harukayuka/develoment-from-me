# develoment-from-me

Ini adalah sebuah ide, riset, dan isi beberapa perasaan dalam bentuk file markdown.

## Struktur Situs

- `index.html`: Halaman utama yang menampilkan daftar postingan.
- `post.html`: Halaman untuk menampilkan isi postingan markdown.
- `posts/`: Folder yang berisi file markdown postingan dengan format nama: `(judul | waktu | tanggal.md)`

## Cara Menambah Postingan

1. Buat file markdown baru di folder `posts/` dengan nama format: `Judul | HH:MM | YYYY-MM-DD.md`
2. Isi file dengan konten markdown.
3. Tambahkan entri baru di `index.html` dalam daftar `<ul class="post-list">`.

## Deployment

Upload semua file ke Cloudflare Pages (pages.dev) untuk hosting statis.
