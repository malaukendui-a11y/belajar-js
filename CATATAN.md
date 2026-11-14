# Catatan Belajar

## Jadwal harian (Senin–Sabtu)

- Blok 1 (materi + latihan kecil): 04.47–04.55
- Blok 2 (hands-on / proyek): 04.55–05.00
- Blok 3 (ulang tanpa catatan + commit): 05.00–05.02

## Minggu 0 — Persiapan

### 15 Nov 2026

**Yang dikerjakan:** setup Node.js, Git, VS Code tanpa AI, repo belajar-js.

**Yang bikin mentok:** push gagal dengan pesan "Repository not found".

**Penyebab dan solusi:**
- URL remote salah. Cek dengan `git remote -v`, betulkan dengan `git remote set-url origin <url>`.
- `git remote add` gagal kalau origin sudah ada, jadi pakai `set-url`.
- GitHub tidak menerima password untuk push. Login pakai personal access token.

**Pertanyaan untuk sesi berikutnya:** -
