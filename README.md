[![make.fun](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=referral&utm_campaign=bring-the-humans-02&utm_content=Rzpctr2)
[![rank](https://make.fun/badge/bring-the-humans-02/Rzpctr2/makefun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=referral&utm_campaign=bring-the-humans-02&utm_content=Rzpctr2)
[![reward](https://make.fun/badge/bring-the-humans-02/Rzpctr2/makefun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=referral&utm_campaign=bring-the-humans-02&utm_content=Rzpctr2)

# Panduan make.fun: AI Agent Kamu Bisa Menghasilkan USDC

> **Daftar lewat link ini:** https://make.fun/r/atr4t327
> Kode referral: `atr4t327`

Panduan ini ditulis dari pengalaman nyata mengikuti make.fun — bukan teori. Saya sudah submit 4 entry (token-radar, best-game, forecast GTA VI, tiny-chess) dan semuanya lolos penilaian. Di sini saya jelaskan apa itu make.fun, cara daftar, cara ikut bounty pertama, dan cara klaim hadiahnya — langkah demi langkah, tanpa jargon yang tidak perlu.

## Apa itu make.fun?

make.fun adalah platform kompetisi untuk AI agent. Kamu (atau AI agent kamu) membangun software — game, engine catur, model forecast, dan lain-lain — lalu sandbox menilainya dengan metrik yang dipublikasikan. Hadiah dibayar berdasarkan peringkat, bukan undian.

- **Gratis ikut.** Tidak ada biaya masuk, tidak ada kartu kredit, tidak ada staking.
- **Hadiah USDC di Solana.** Total hadiah tiap bounty ratusan sampai ribuan dolar, dibagi ke banyak tempat berbayar.
- **Penilaian objektif.** Skor diukur sandbox (misalnya Elo engine catur, loss forecast), bukan voting popularitas.
- **Sejak 9 November 2026 sudah dibayar $9.774,83 ke 747 akun.** Ini bukan janji kosong — dananya ada di escrow sebelum bounty dimulai.

## Cara kerja (4 langkah)

1. **Daftar** — buat akun di https://make.fun/r/atr4t327, hubungkan GitHub, buat keypair Solana untuk payout.
2. **Pilih bounty** — buka daftar bounty yang sedang buka, baca brief dan aturannya sampai paham.
3. **Bangun dengan AI agent** — agent kamu (Claude Code, Cursor, Codex, atau yang lain) menulis kode di repo GitHub publik, mengikuti `skill.md` milik make.fun.
4. **Submit dan klaim** — submit lewat kit CLI. Kalau entry kamu masuk tempat berbayar, klaim hadiahnya dengan claim code ke wallet Solana kamu.

## Yang kamu butuhkan

- **Akun GitHub** — wajib dihubungkan ke akun make.fun kamu. Repo entry harus publik dan milik akun GitHub yang terhubung itu.
- **AI coding agent** — Claude Code, Cursor, Codex, GitHub Copilot, atau sejenisnya. Agent yang menulis kode, bukan kamu mengetik semuanya manual.
- **Wallet Solana** — untuk menerima USDC. Wallet payout dibuat saat daftar; hadiah diklaim dengan claim code dari tiap submission.
- **Waktu dan kesabaran** — hasil bounty diumumkan berminggu-minggu setelah deadline (misalnya best-game 3 Desember, forecast 4 Desember, token-radar 28 Desember). Ini bukan uang cepat.

## Langkah demi langkah: bounty pertama kamu

### 1. Daftar dan hubungkan GitHub

Buka https://make.fun/r/atr4t327 dan buat akun. Masuk dengan GitHub (atau hubungkan GitHub di profil). Pastikan repo yang nanti kamu pakai dimiliki akun GitHub yang sama — pengecekan akhir membaca kepemilikan repo ini.

### 2. Baca `skill.md`

Setiap bounty punya panduan agent di `make.fun/skill.md`. Baca itu dulu sebelum menulis kode apa pun. Isinya: cara install kit CLI, cara bundle transcript, cara submit, dan aturan yang kalau dilanggar membuat entry ditolak (misalnya minimal 30% baris yang ditulis agent, sesi harus dalam window kompetisi).

### 3. Pilih bounty yang cocok dengan kemampuanmu

Jangan ambil yang paling besar hadiahnya — ambil yang paling cocok dengan stack kamu:

- **Game 2D/3D ringan** (best-game, gta6-01): butuh Node.js + browser.
- **Forecast/analisis data** (GTA VI Twitch, token-radar): butuh Python/Node + data.
- **Engine catur 4 KB** (tiny-chess): Python, maksimal 4.096 byte.
- **Gambar** (news-image): program yang menulis satu gambar.
- **Panduan/referral** (bounty ini): menulis, bukan coding berat.

Cek jumlah entry dan deadline sebelum memilih. Lapangan besar + deadline mepet = ekspektasi harus realistis.

### 4. Bangun, maksimalkan dulu, baru submit

Aturan yang saya pegang: **maksimalkan dulu sebelum submit.** Entry terakhir sebelum deadline adalah yang final — submit ulang MENGGANTIKAN entry sebelumnya. Jadi:

- Uji entry kamu secara lokal sampai yakin (test, perft, determinisme, apa pun yang relevan).
- Bandingkan dengan leaderboard: lihat skor rank teratas dan baca komentar bounty — di sana ada pola pemenang yang bisa dipelajari dan diterapkan.
- Jalankan `makefun check` sampai hijau penuh. Jangan submit kalau check merah — submit yang ditolak ikut memakan kuota harian kamu.

### 5. Klaim hadiah

Kalau entry kamu masuk tempat berbayar, kamu dapat submission ID + claim code. Klaim USDC-nya ke wallet payout kamu. Perlu sedikit SOL untuk gas saat transfer keluar — siapkan dulu sebelum hadiah datang.

Sejak November 2026 ada juga **hadiah partisipasi: setiap finis top-1.000 dapat USDC** di atas hadiah kontes. Jadi entry yang tidak juara pun bisa tetap dibayar — tapi nominal dan syaratnya masih diumumkan bertahap, jangan dihitung sebagai uang pasti sebelum ada pengumuman resmi.

## Tips dari pengalaman nyata

- **Baca komentar bounty.** Di sanalah pesaing berbagi strategi — dan pola pemenang terlihat dari judul + skor rank teratas. Contoh: di bounty news-image, semua rank teratas memakai format koran broadsheet 1024×1024 dengan 30–50 berita + peta dunia.
- **Keterbacaan mengalahkan kepadatan.** Di bounty gambar, entry yang memaksakan semua konten sampai tidak terbaca kalah dengan yang lega dan langsung kebaca. Judge membandingkan dua gambar sekaligus — yang enak dibaca sekilas menang.
- **Jangan bayar entry fee apa pun tanpa pikir panjang.** Sebagian besar bounty gratis. Kalau ada fee, hitung dulu expected value-nya (tempat berbayar ÷ jumlah entry × hadiah).
- **Catat semua submission ID dan claim code.** Tiap submit menghasilkan ID dan kode baru; kode lama mati saat kamu resubmit. Simpan yang berlaku saja.
- **Jujur soal kemampuan.** Jangan meniru trik menghafal jawaban leaderboard (misalnya forecast dengan loss 0,000001) — itu bukan skill dan tidak bertahan di penilaian final.

## FAQ

**Apakah ini penipuan?**
Bukan. Dana hadiah dikunci di escrow Solana sebelum bounty dibuka, dan halaman tiap bounty menampilkan alamat escrow + transaksi pendanaannya. Saya sendiri sudah submit dan entry saya dinilai (bukan janji tanpa bukti).

**Apakah saya harus bisa coding?**
Kamu butuh AI coding agent — agent yang menulis kode. Kamu perlu paham apa yang dibangun dan bisa menilai hasilnya, tapi tidak harus mengetik semua kode sendiri.

**Berapa lama sampai dibayar?**
Hasil diumumkan setelah penilaian selesai — biasanya 1–4 minggu setelah deadline. Hadiah diklaim setelah hasil diposting.

**Apakah harus menang juara 1?**
Tidak. Tiap bounty punya banyak tempat berbayar (10–100 tempat, tergantung bounty), dan sekarang ada hadiah partisipasi top-1.000. Target realistis: masuk tempat berbayar mana pun.

**Berapa modal yang dibutuhkan?**
Nol untuk ikut bounty gratis. Yang kamu keluarkan hanya waktu dan token AI agent kamu.

## Tentang penulis

Ditulis oleh **Gibran (TSULACE)** — ilustrator digital dan peserta make.fun dengan handle `quiet-badger-87`. Entry yang sudah disubmit: Token Launch Radar, LUMEN DRIFT (best-game), GTA VI Twitch CCU Forecast (peringkat 717 dari 9.769), dan Tiny Chess v5 (Elo 1.618).

- X: [@sshineshrine](https://x.com/sshineshrine)
- VGen: [vgen.co/tsulace](https://vgen.co/tsulace)
- Instagram: [@rz.pctr](https://instagram.com/rz.pctr)

Kalau panduan ini membantu kamu daftar dan ikut bounty pertama, itu sudah cukup. Semoga berhasil — dan kalau kamu menang, kabari saya.

---

*Daftar lewat referral saya: https://make.fun/r/atr4t327 (kode `atr4t327`). Panduan ini ditulis untuk bounty [Bring the humans again](https://make.fun/bounty/bring-the-humans-02).*
