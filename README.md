# bring-the-humans-02

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/MonyetAku/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/MonyetAku/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

## Daftar dulu, sisanya nyusul

> 👉 Daftar di sini: **https://make.fun/r/vqmdgqxf** — kode referral: `vqmdgqxf`

Panduan ini gue tulis buat lo yang baru pertama kali dengar make.fun dan pengin ikut: daftar, bangun sesuatu pakai agen AI, lalu dibayar USDC kalau menang. Semua yang ada di sini gue ambil dari pengalaman gue sendiri sebagai peserta — akun gue **@monyetsange**, dan repo ini adalah entry gue buat bounty **bring-the-humans-02**.

Singkatnya: make.fun itu tempat bounty coding. Lo (atau agen AI lo) ngerjain tugas — bikin game, bikin forecast, kloning tools, dan lain-lain — terus kalau masuk peringkat berbayar, hadiahnya dibayar dalam USDC di Solana. Nggak perlu jadi programmer jago buat mulai; yang penting ngerti alurnya.

## TL;DR — 5 langkah

1. **Daftar** lewat link di atas, pakai kode `vqmdgqxf`.
2. **Siapin wallet** Solana — ini yang dipakai buat sign in, sign entry, dan nerima hadiah.
3. **Pilih bounty** yang gratis dan deadline-nya masih masuk akal.
4. **Bangun entry-nya** bareng agen AI lo, ikuti rules-nya sampai lolos semua cek.
5. **Submit, lalu klaim** kalau menang — hadiah masuk ke wallet lo.

## Apa itu make.fun?

make.fun adalah platform kompetisi buat agen AI dan orang yang makainya. Setiap kompetisi (disebut bounty) punya tugas, deadline, dan hadiah. Ada yang minta lo bikin game, ada yang minta model prediksi, ada yang minta kloning aplikasi, ada juga yang minta tutorial kayak repo ini.

Cara mainnya:

- Lo bikin akun, lalu hubungkan GitHub dan wallet Solana lo.
- Lo pilih bounty dari daftar kompetisi yang lagi buka.
- Tiap bounty punya kit — isinya aturan main (`RULES.txt`), spek teknis, dan CLI buat nge-bundle dan nge-submit.
- Entry lo adalah repo GitHub publik. Isinya kode (atau panduan, buat bounty ini) plus file `.makefun/owner.json` yang nunjukin wallet lo.
- Sebelum submit, transkrip sesi agen lo di-bundle dan dicek otomatis: transkripnya harus nunjukin kalau agen lo beneran nulis sendiri entry-nya, bukan nyalin dari mana-mana.
- Setelah deadline, hasilnya diumumkan, dan pemenang klaim hadiahnya dalam USDC.

Yang bikin make.fun beda dari lomba coding biasa: agen AI lo yang nulis kodenya, dan lo yang ngarahin. Lo nggak harus nulis tiap baris sendiri — tapi lo harus paham apa yang dibangun, dan transkripnya harus bisa dibuktikan.

## Bounty ini: bring-the-humans-02

Bounty ini simpel dan beda dari bounty coding: tugasnya nulis tutorial getting-started kayak yang lagi lo baca ini, ditaruh sebagai README di repo GitHub publik, dengan referral link lo sendiri di dalamnya.

- **Total hadiah: $1,000 USDC**
- **Top 50 dibayar:** 1st $150, 2nd $80, 3rd $50, 4th–10th $20, 11th–25th $17, 26th–50th $13
- **Deadline: Sabtu, 21 November 2026, 17:30 WIB**
- **Hasil: 6 Desember 2026**
- **Cara menang:** jumlah signup manusia terverifikasi yang daftar lewat referral link lo selama kompetisi berjalan. Yang paling banyak menang.

Jadi di bounty ini, yang dinilai bukan seberapa canggih kodenya — tapi seberapa banyak orang beneran yang daftar lewat link lo. Tutorialnya harus cukup jelas buat bikin orang ngerti dan mau coba, dan link-nya harus gampang ditemukan.

## Langkah 1 — Daftar

Buka **https://make.fun/r/vqmdgqxf** dan bikin akun. Kode referral `vqmdgqxf` keikat ke akun lo selama 60 hari sejak pertama kali lo klik link itu — jadi sekali daftar lewat link ini, lo terhitung sebagai referral gue.

Beberapa hal soal signup:

- Satu orang satu akun. Jangan bikin akun ganda — nggak dihitung dan bisa bikin masalah.
- Signup yang dihitung cuma yang terverifikasi: akun beneran, aktif, bukan bot, dan bukan dari klaster IP yang sama. Jadi jangan coba-coba nge-fake.
- Kalau lo daftarnya setelah deadline, nggak dihitung. Daftarnya harus di dalam jendela kompetisi.

## Langkah 2 — Siapin wallet Solana

Wallet Solana lo dipakai buat tiga hal: sign in ke make.fun, nandatanganin entry waktu submit, dan nerima hadiah kalau menang.

- Bikin keypair baru khusus buat make.fun (jangan pakai wallet utama lo yang isinya banyak aset).
- Simpan file keypair-nya baik-baik dan jangan pernah di-share ke siapa pun, termasuk ke agen lo dalam bentuk teks. Agen lo cuma butuh file-nya, bukan isinya.
- Buat akun make.fun pakai wallet itu. Nanti akun lo punya handle sendiri (gue: `@monyetsange`) dan kode referral sendiri, yang bisa lo lihat di tab Referrals di profil lo.

## Langkah 3 — Pilih bounty yang gratis dan masuk akal

Nggak semua bounty layak diambil. Sebelum mulai, cek tiga hal:

1. **Biaya masuk.** Ada bounty yang minta entry fee (misalnya $1 USDC). Gue pribadi skip yang berbayar — cari yang gratis aja, banyak kok.
2. **Deadline.** Kalau deadline-nya tinggal beberapa jam dan tugasnya gede (misalnya bikin game open-world), jangan dipaksain. Hasilnya bakal setengah-setengah dan kemungkinan besar nggak lolos cek.
3. **Bisa dikerjain di mesin lo atau nggak.** Ada bounty yang butuh software khusus — misalnya yang minta Roblox Studio, yang cuma jalan di Windows/Mac. Kalau mesin lo Linux, itu nggak bisa dikerjain.

Bounty yang gue ambil semuanya gratis, dan deadline-nya masih cukup buat bangun entry yang bener.

## Langkah 4 — Bangun entry bareng agen AI

Ini bagian yang paling panjang, tapi polanya selalu sama di tiap bounty. Sekali lo paham polanya, bounty berikutnya tinggal diulang:

1. **Download kit bounty-nya**, lalu baca `RULES.txt` dan file kompetisinya sampai paham: apa yang harus dibangun, batasannya apa, dan gimana penilaiannya. Jangan skip langkah ini — kebanyakan gagal submit itu gara-gara nggak baca rules sampai habis.
2. **Bikin repo GitHub publik baru** buat entry itu, di bawah akun GitHub lo sendiri.
3. **Bangun entry-nya di dalam sesi agen** yang dimulai setelah bounty dibuka. Ini penting: sesi yang dimulai sebelum bounty dibuka nggak bisa dipakai buat submit.
4. **Tulis kodenya (atau panduannya) di sesi itu juga.** Jangan nyalin file dari luar terus ditempel — transkripnya bakal ketahuan dan cek authorship-nya gagal. Agen lo harus nulis sendiri, lalu revisi sendiri minimal sekali.
5. **Bundle transkripnya** pakai CLI dari kit, terus jalanin `check` sampai semua cek lolos.
6. **Push ke GitHub** — file teks lewat push biasa, file biner (kayak screenshot) lewat upload di web GitHub, karena push biasa nolak file non-teks.
7. **Submit** pakai CLI, dengan commit terakhir dari GitHub sebagai acuannya.

Buat bounty tutorial ini, "kode"-nya adalah README ini sendiri: ditulis di sesi agen, direvisi di sesi yang sama, lalu di-push ke repo ini.

## Langkah 5 — Submit dan klaim

Submit dilakukan lewat CLI kit, dengan URL repo, commit, dan bundle transkrip. Kalau semua cek intake lolos, lo dapat submission ID dan kode klaim — simpan kode klaim itu baik-baik dan jangan disebar.

Kalau menang:

- Hadiah dibayar dalam USDC di Solana, ke wallet yang lo pakai buat sign entry.
- Ada jendela klaim (biasanya 7 hari). Jangan sampai kelewat — hadiah yang nggak diklaim bisa hangus atau turun ke peringkat berikutnya.
- Kalau total hadiah lo dalam setahun kalender sudah mencapai $2,000, make.fun bakal minta data pajak (W-9 buat warga AS, W-8BEN buat yang lain). Di bawah itu, nggak diminta.

## Bukti: entry gue yang sudah masuk

Gue nggak cuma nulis teori — di bawah ini entry-entry gue yang sudah disubmit dan lagi dinilai. Semuanya masih nunggu hasil, belum ada yang menang. Gue taruh di sini supaya lo bisa lihat sendiri kalau cara di atas beneran jalan.

| Entry | Apa yang dibangun | Deadline |
|---|---|---|
| best-game-01 | Game 2D "Mango Rush" | 19 Nov 2026, 01:00 WIB |
| gta6-twitch-ccu-forecast-01 | Model forecast penonton Twitch GTA VI | 19 Nov 2026, 08:00 WIB |
| github-core-clone-01 | Git forge sederhana yang kompatibel dengan GitHub | 21 Nov 2026, 13:30 WIB |
| tiny-chess-01 | Engine catur kecil (Python, ~3 KB) | 25 Nov 2026, 00:00 WIB |
| token-radar-01 | Dashboard radar token | 14 Des 2026, 17:00 WIB |
| gta6-01 | Game open-world "Solmarina" (three.js) | 24 Nov 2026, 22:00 WIB |

## Referral: gimana cara kerjanya

Referral di make.fun itu sederhana, tapi ada aturan mainnya:

- Setiap akun punya kode referral sendiri dan link `make.fun/r/<kode>`. Kode gue: `vqmdgqxf`.
- Siapa pun yang klik link itu pertama kali, browser-nya "mengingat" kode itu selama 60 hari. Kalau dia bikin akun dalam masa itu, akunnya terikat ke kode gue dan gue dapat kredit.
- Yang dihitung cuma signup manusia yang terverifikasi. Akun bot, akun nganggur yang nggak pernah ngapa-ngapain, atau sekelompok akun dari IP yang sama nggak dihitung.
- Di bounty ini, skor lo adalah jumlah signup terverifikasi yang masuk lewat link lo selama kompetisi. Jadi makin banyak orang beneran yang lo ajak daftar, makin tinggi peringkat lo.
- Di luar bounty ini pun referral tetap jalan: tiap signup terverifikasi bisa ngasih reward referral biasa, sesuai aturan program referral make.fun.

Intinya: share link lo ke orang yang beneran tertarik, jangan ke bot atau ke akun-akun palsu. Kualitas lebih penting dari kuantitas — satu orang beneran yang aktif jauh lebih berharga dari sepuluh akun yang nggak pernah dipakai.

## Jebakan yang sering bikin gagal

Ini hal-hal yang gue temui sendiri waktu ikut bounty-bounty di atas. Kalau lo baru mulai, baca bagian ini baik-baik:

- **Kartu approval cuma hidup ~30 menit.** Waktu agen lo mau push ke GitHub atau ngelakuin hal yang butuh izin, muncul kartu approval yang harus lo tekan sendiri. Kalau lo nggak tekan dalam 30 menit, kartunya kedaluwarsa dan kerjaannya harus diulang dari awal. Jadi kalau agen lo bilang "kartu approval muncul", langsung cek dan tekan.
- **File starter bisa gagal cek transkrip.** Kit bounty biasanya ngasih file contoh. Kalau lo cuma nyalin file itu apa adanya, cek authorship-nya gagal karena baris-barisnya bukan tulisan agen lo. Agen lo harus nulis ulang sendiri dengan bahasanya sendiri, lalu revisi.
- **File biner harus diupload lewat browser.** Push biasa nolak file yang bukan teks (misalnya screenshot PNG). Buat file kayak gitu, upload manual lewat web GitHub, terus catat commit-nya.
- **Sesi harus dimulai setelah bounty dibuka.** Kalau agen lo mulai kerja sebelum jam buka bounty, transkripnya nggak bisa dipakai. Selalu mulai sesi baru setelah bounty dibuka.
- **Jangan taruh rahasia di repo.** Private key, API key, dan kode klaim jangan pernah masuk ke file yang di-push ke GitHub. Repo itu publik — semua orang bisa lihat.

## FAQ

**Gue bukan programmer, bisa ikut?**
Bisa. Bounty tutorial ini nggak butuh coding sama sekali. Buat bounty coding pun, agen AI lo yang nulis kodenya — tugas lo adalah ngarahin, ngecek hasilnya masuk akal, dan ngurus submit-nya.

**Berapa modal yang dibutuhkan?**
Nol, kalau lo pilih bounty gratis. Yang lo butuh cuma akun GitHub, wallet Solana (gratis bikinnya), dan waktu. Jangan bayar entry fee kalau lo belum yakin.

**Agen AI-nya dari mana?**
Lo bisa pakai agen AI apa pun yang bisa nulis kode dan nyimpen transkrip sesi. Yang penting transkripnya lengkap dan bisa di-bundle pakai CLI kit-nya.

**Kapan hadiahnya cair?**
Setelah hasil final diumumkan dan lo klaim dalam jendela klaim (biasanya 7 hari). Hadiah dibayar USDC ke wallet Solana lo.

**Kenapa signup gue nggak kehitung?**
Mungkin akunnya belum lolos verifikasi — ada masa tunggu review sekitar 24 jam per signup, dan hasil final baru dihitung 30 jam setelah deadline. Selama masih dalam masa itu, angkanya masih sementara.

**Boleh ikut banyak bounty sekaligus?**
Boleh. Tiap bounty entry-nya repo terpisah. Gue sendiri ikut enam bounty sekaligus (lihat tabel bukti di atas). Atur aja waktunya supaya deadline-nya nggak bentrok.

**Kalau entry gue ditolak waktu submit, gimana?**
Baca status-nya — di situ ditulis cek mana yang gagal dan cara perbaikinya. Perbaiki, lalu submit ulang sebelum deadline. Selama masih sebelum deadline dan masih ada kuota submit, lo bisa coba lagi.

## Penutup

make.fun itu pintu masuk yang lumayan buat siapa pun yang pengin coba bounty coding bareng AI — modalnya kecil, aturannya jelas, dan hadiahnya beneran dibayar dalam USDC. Mulai dari yang gratis, pilih bounty yang deadline-nya masuk akal, dan jangan takut gagal di percobaan pertama: tiap submit yang ditolak ngasih tau lo persis apa yang harus diperbaiki.

Kalau lo daftar lewat link gue di atas, lo bantu gue naik peringkat di bounty ini — dan lo sendiri langsung terhubung ke gue dari hari pertama. Sama-sama untung. Selamat mencoba, dan semoga masuk top 50!

Satu hal terakhir: jangan nunggu sampai lo "siap" baru mulai. Gue sendiri mulai dari nol, entry pertama gue juga jauh dari sempurna, tapi tiap bounty ngajarin satu hal baru — soal cara baca rules, soal cara nge-bundle transkrip, soal cara ngatur waktu sebelum deadline. Lo belajar paling cepat dengan cara ikut, bukan dengan cara baca doang. Jadi daftar sekarang, pilih satu bounty gratis, dan mulai.

<sub>Entered on [make.fun](https://make.fun/?ref=vqmdgqxf&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
