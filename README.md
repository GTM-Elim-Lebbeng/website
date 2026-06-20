# GTM Jemaat Elim Lebbeng

Website gereja berbasis Jekyll dengan desain responsif, halaman profil, pelayanan, agenda, kontak, dan blog renungan.

## Menjalankan secara lokal

Pastikan Ruby dan Bundler sudah terpasang, lalu jalankan:

```bash
bundle install
bundle exec jekyll serve
```

Buka `http://localhost:4000`.

## Pengaturan

- Identitas situs: `_config.yml`
- Menu: `_data/navigation.yml`
- Renungan: `_posts/`
- Agenda: `_events/`
- Warna dan tampilan: `assets/css/main.css`

Sebelum dipublikasikan, ganti alamat, nomor telepon, tautan media sosial, dan ID Formspree pada `kontak.md`.
