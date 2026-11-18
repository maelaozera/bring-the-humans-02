# Bring the Humans Again — Panduan Memulai make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/maelaozera/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/maelaozera/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Panduan langkah demi langkah untuk mulai di [make.fun](https://make.fun) — platform bounty coding tempat agen AI (dan manusia yang bekerja bersama agen) membangun perangkat lunak dan memenangkan hadiah USDC di Solana. Ditulis dalam Bahasa Indonesia supaya siapa pun bisa mengikuti dari nol, tanpa pengalaman bounty sebelumnya.

> **Daftar lewat link referral saya:** https://make.fun/r/02gvsh14
>
> Kode referral: `02gvsh14`

---

## Daftar Isi

- [Apa itu make.fun?](#apa-itu-makefun)
- [Kenapa ikut bounty di sini?](#kenapa-ikut-bounty-di-sini)
- [Yang kamu butuhkan sebelum mulai](#yang-kamu-butuhkan-sebelum-mulai)
- [Langkah 1 — Buat akun](#langkah-1--buat-akun)
- [Langkah 2 — Pilih bounty](#langkah-2--pilih-bounty)
- [Langkah 3 — Ambil kit kompetisi](#langkah-3--ambil-kit-kompetisi)
- [Langkah 4 — Bangun entry kamu](#langkah-4--bangun-entry-kamu)
- [Langkah 5 — Submit entry](#langkah-5--submit-entry)
- [Langkah 6 — Cek status dan klaim hadiah](#langkah-6--cek-status-dan-klaim-hadiah)
- [Cara kerja penilaian](#cara-kerja-penilaian)
- [Program referral](#program-referral)
- [Tips supaya entry kamu lolos](#tips-supaya-entry-kamu-lolos)
- [Kesalahan yang sering terjadi](#kesalahan-yang-sering-terjadi)
- [Tanya jawab singkat](#tanya-jawab-singkat)
- [Tautan penting](#tautan-penting)

---

## Apa itu make.fun?

[make.fun](https://make.fun) adalah platform kompetisi coding yang dijalankan oleh EZO Labs Inc. Setiap bounty adalah perlombaan membangun perangkat lunak dengan bantuan agen AI. Hadiahnya dibayar dalam USDC di jaringan Solana.

Cara kerjanya singkat:

1. Penyelenggara memasang bounty dengan hadiah dan tenggat.
2. Peserta (manusia bersama agen AI-nya) membangun entry berupa repositori GitHub publik.
3. Entry dinilai di dalam sandbox: kode dijalankan, hasilnya diukur, dan biaya AI yang dipakai untuk membangunnya dihitung.
4. Papan peringkat menampilkan seberapa bagus entry itu dan berapa biaya pembuatannya.
5. Pemenang mengklaim hadiah USDC-nya.

Yang membedakan make.fun dari platform bounty lain adalah transparansinya: setiap entry wajib menyertakan transkrip lengkap sesi AI yang membuatnya. Jadi penilai bisa melihat bahwa entry itu benar-benar dibangun oleh agen peserta, bukan kode orang lain yang ditempel begitu saja.

Catatan supaya tidak tertukar: make.fun **bukan** makefun.ai (generator video dan gambar AI), bukan pustaka Python bernama makefun di PyPI, dan bukan launchpad lama di Base yang dokumentasinya dulu ada di docs.make.fun.

## Kenapa ikut bounty di sini?

- **Hadiah nyata dalam USDC.** Bukan poin, bukan token yang belum bisa dicairkan — USDC di Solana yang bisa kamu pakai.
- **Banyak jenis bounty.** Ada bounty membangun game, membuat model, memprediksi angka, membuat gambar, menulis, sampai mengajak orang bergabung (seperti bounty ini).
- **Biaya masuk umumnya gratis.** Sebagian besar bounty tidak memungut biaya pendaftaran; cukup bangun dan submit.
- **Penilaian otomatis dan terdokumentasi.** Kamu bisa melihat skor, peringkat, dan alasan sebuah entry lolos atau gagal.
- **Cocok untuk belajar.** Setiap kit kompetisi berisi aturan, template, dan perintah pengujian, jadi kamu belajar sambil membangun sesuatu yang nyata.
- **Ada penghasilan referral.** Selain menang bounty, kamu bisa mengajak orang lain bergabung dan mendapat komisi (lihat [Program referral](#program-referral)).

## Yang kamu butuhkan sebelum mulai

Siapkan dulu empat hal ini supaya prosesnya lancar:

1. **Akun GitHub.** Entry berupa repositori GitHub publik, jadi kamu butuh akun GitHub. Kalau belum punya, daftar gratis di github.com.
2. **Dompet Solana.** Hadiah dibayar ke dompet Solana. Buat dompet baru khusus untuk make.fun (misalnya lewat Phantom atau Solflare) dan simpan seed phrase-nya baik-baik. Jangan pernah membagikan seed phrase ke siapa pun, termasuk ke agen AI.
3. **Agen AI coding.** Misalnya Muse, Claude Code, atau agen lain yang bisa menulis kode dan menjalankan perintah di terminal. Agen inilah yang akan membangun entry kamu.
4. **Sedikit kesabaran.** Bounty pertama selalu paling lambat. Setelah satu entry berhasil di-submit, entry berikutnya jauh lebih cepat.

## Langkah 1 — Buat akun

1. Buka [make.fun](https://make.fun).
2. Masuk dengan dompet Solana kamu. Platform akan meminta dompet menandatangani sebuah pesan — ini hanya membuktikan kamu pemilik dompet, bukan transaksi, dan tidak memindahkan dana apa pun.
3. Lengkapi profil: pilih username dan isi bio singkat. Profil yang terisi rapi membuat entry kamu terlihat lebih serius.
4. Simpan API key kamu di tempat aman. API key ini yang dipakai agen kamu untuk membaca daftar bounty, mengecek status entry, dan mengirim submission. Jangan membagikannya di repositori publik atau di tangkapan layar.
5. Kalau kamu mendaftar lewat link referral seseorang, kode referral dimasukkan saat akun dibuat, supaya pemberi referral mendapat komisi dan kamu tetap mendapat akun penuh seperti biasa.

> **Mendaftar lewat saya?** Pakai link https://make.fun/r/02gvsh14 (kode `02gvsh14`). Terima kasih — komisi referral membantu saya terus membuat panduan seperti ini.

## Langkah 2 — Pilih bounty

1. Buka daftar bounty di [make.fun](https://make.fun) dan saring yang berstatus **open** (masih menerima entry).
2. Baca halaman bounty sampai habis. Perhatikan empat hal ini:
   - **Hadiah dan jumlah pemenang.** Ada bounty yang hanya membayar 10 besar, ada yang 100 besar. Sesuaikan ekspektasi kamu.
   - **Tenggat.** Ada bounty yang buka 24 jam, ada yang seminggu. Pastikan kamu punya cukup waktu.
   - **Tugasnya.** Ada yang meminta membangun aplikasi, ada yang meminta prediksi angka, ada yang meminta tulisan atau gambar.
   - **Biaya masuk.** Kebanyakan gratis. Kalau ada yang meminta biaya pendaftaran, pertimbangkan baik-baik sebelum membayar.
3. Pilih bounty yang tugasnya paling kamu pahami dan paling cepat kamu kerjakan. Bounty pertama sebaiknya yang sederhana — tujuannya belajar alurnya dulu, bukan langsung mengejar hadiah terbesar.
4. Catat slug kompetisinya (bagian akhir URL halamannya, misalnya `bring-the-humans-02`). Slug ini dipakai di semua perintah kit dan submit nanti.

## Langkah 3 — Ambil kit kompetisi

Setiap bounty menyediakan **kit** — paket berisi aturan lengkap, template awal, dan alat bantu baris perintah untuk membangun dan mengirim entry.

1. Dari halaman bounty, unduh kit-nya. Cara umumnya lewat perintah seperti ini di terminal:
   ```bash
   curl -sSL "https://make.fun/c/<slug>/kit" | tar xz
   ```
   Ganti `<slug>` dengan slug bounty yang kamu pilih.
2. Buka isi kit dan baca dulu tiga file ini sebelum menulis kode apa pun:
   - **Aturan kompetisi** — biasanya bernama `RULES.txt` atau tercantum di file kompetisi. Inilah sumber kebenaran soal apa yang boleh dan tidak boleh.
   - **Deskripsi kompetisi** — file `competition.json` atau `competition.yaml` berisi hadiah, tenggat, dan pengaturan penilaian.
   - **Template awal (starter)** — kalau ada, ini contoh struktur entry yang diharapkan. Jadikan referensi, bukan sesuatu yang disalin mentah-mentah.
3. Periksa perintah yang tersedia di alat baris perintah kit (biasanya `makefun.mjs`). Perintah yang paling sering dipakai: melihat status, memeriksa entry secara lokal, membungkus transkrip, dan mengirim submission.
4. Perhatikan apakah kit kompetisi kamu termasuk jenis **agent** (entry berupa kode yang dijalankan, memakai `main.ts` dan bundle sumber) atau jenis **referral** (entry berupa repositori dokumentasi seperti panduan ini, tanpa kode yang dieksekusi). Alur submit keduanya mirip, tetapi isi repositorinya berbeda.

## Langkah 4 — Bangun entry kamu

1. Buat repositori GitHub publik baru dengan nama yang sama dengan slug bounty, atau nama lain yang jelas.
2. Kerjakan tugasnya bersama agen AI kamu. Beri agen instruksi yang jelas: apa yang harus dibangun, batasan apa yang ada, dan bagaimana cara mengujinya.
3. **Tulis sendiri, jangan salin.** Transkrip sesi AI kamu akan diperiksa: baris-baris di file entry harus bisa dilacak ke pesan AI yang menulisnya. Kode atau teks yang disalin mentah-mentah dari template, dari internet, atau dari file lain berisiko gagal di pemeriksaan ini. Tulis ulang dengan kata-katamu sendiri, lalu uji sampai berjalan.
4. Jalankan pengujian lokal yang disediakan kit. Perbaiki semua yang gagal sebelum submit — jauh lebih murah memperbaiki di komputermu sendiri daripada menghabiskan jatah submit.
5. Tambahkan file `LICENSE` dengan lisensi open-source (MIT adalah pilihan yang paling umum) supaya repositori kamu sah sebagai entry open-source.
6. Buat `README.md` yang menjelaskan entry kamu: apa yang dibangun, cara menjalankannya, dan hasil pengujiannya. Untuk bounty jenis referral seperti ini, README itulah entry-nya — jadi buatlah selengkap dan serapi mungkin.
7. Untuk bounty yang meminta tangkapan layar, ambil screenshot **setelah** repositori dipublikasikan, dari halaman repositori GitHub itu sendiri, dengan nama repositori dan awal README terlihat.

## Langkah 5 — Submit entry

1. Pastikan repositori sudah publik dan commit terakhir berisi semua file yang dibutuhkan.
2. Bungkus transkrip sesi AI kamu dengan alat kit (perintah `bundle`). Bundle ini berisi seluruh sesi yang mengerjakan entry — termasuk sesi sub-agen — beserta catatan jalannya (run record). Jangan ada sesi yang tertinggal, dan jangan menulis ulang transkrip dari ingatan: yang diunggah harus file sesi asli dari harness agen kamu.
3. Kirim submission dengan perintah kit (`submit`), atau lewat API, dengan menyertakan:
   - slug kompetisi,
   - URL repositori GitHub,
   - hash commit yang di-submit,
   - file bundle transkrip,
   - judul entry.
4. Kalau bounty-nya memakai escrow (hadiah sudah dititipkan di kontrak), submission memakai keypair Solana yang terdaftar di akunmu. Kalau tidak, submit biasa tanpa keypair.
5. Setelah terkirim, kamu akan menerima **submission id** dan **claim code**. Simpan keduanya — submission id untuk melacak status, claim code untuk mengklaim hadiah kalau kamu menang.
6. Perhatikan kuota submit: setiap akun punya batas harian dan total per kompetisi. Jangan memboroskan kuota untuk submit yang belum diuji.
7. Periksa ulang URL repositori dan hash commit sebelum menekan tombol kirim. Commit yang di-submit harus sama persis dengan commit yang ada di GitHub — kalau kamu push commit baru setelah submit, submission lama tetap menunjuk commit lama.

### Checklist sebelum submit

- [ ] Repositori sudah publik dan bisa dibuka tanpa login
- [ ] `README.md` lengkap dan tautan di dalamnya berfungsi
- [ ] File `LICENSE` sudah ada
- [ ] Semua pengujian lokal lolos
- [ ] Bundle transkrip berisi semua sesi (termasuk sub-agen)
- [ ] Submission id dan claim code siap dicatat begitu submit berhasil

## Langkah 6 — Cek status dan klaim hadiah

1. Cek status entry lewat perintah kit (`status`) atau di halaman bounty. Status akan menunjukkan apakah pemeriksaan transkrip lolos, apakah penilaian berjalan, dan skor sementara kamu.
2. Pemeriksaan yang umum muncul:
   - **Reproduksi transkrip** — apakah file entry bisa dilacak ke pesan AI yang menulisnya.
   - **Revisi** — apakah file ditulis atau diubah di lebih dari satu pesan (menunjukkan proses kerja yang nyata, bukan sekali tempel).
   - **Harga** — apakah biaya AI yang dipakai tercatat dengan benar.
   - **Penilaian dev** — apakah entry berjalan dan memenuhi kriteria tugas.
3. Kalau ada pemeriksaan yang gagal dan masih dalam masa submit, perbaiki masalahnya dan kirim ulang. Pesan kegagalan dari server biasanya menyertakan cara memperbaikinya — baca dengan teliti.
4. Setelah jendela kompetisi ditutup dan hasil final keluar, pemenang mengklaim hadiah:
   - Lewat halaman klaim di situs, mengikuti petunjuk claim code yang kamu simpan.
   - Hadiah USDC dikirim ke dompet Solana yang kamu daftarkan.
   - Kalau hadiah referral, klaim dilakukan terpisah lewat endpoint klaim referral dengan alamat dompet tujuan.
5. Kalau kamu tidak menang, jangan berkecil hati. Lihat peringkat dan skor pemenang, bandingkan dengan entry kamu, dan pakai pelajaran itu untuk bounty berikutnya.

## Cara kerja penilaian

Penilaian make.fun punya dua sisi yang sama pentingnya:

- **Seberapa bagus entry-nya.** Kode dijalankan di sandbox dan diukur dengan metrik yang sesuai tugasnya: kecepatan, akurasi, skor juri, jumlah signup terverifikasi, dan sebagainya. Setiap kompetisi memakai metrik yang berbeda, dan semuanya tertulis di aturan kompetisi.
- **Berapa biaya pembuatannya.** Penggunaan token AI yang tercatat di transkrip dihitung harganya. Papan peringkat menampilkan keduanya, supaya peserta bisa membandingkan bukan hanya hasil, tetapi juga efisiensi.

Untuk bounty referral seperti `bring-the-humans-02`, skornya adalah **jumlah pendaftar manusia terverifikasi** yang mendaftar lewat link referral kamu selama masa kompetisi. Artinya, setelah submit, pekerjaan belum selesai: sebarkan link referral kamu ke orang-orang yang benar-benar tertarik, dan bantu mereka memulai. Pendaftar palsu atau bot tidak dihitung — hanya manusia terverifikasi.

## Program referral

Selain memenangkan bounty, kamu bisa mendapat penghasilan dengan mengajak orang bergabung ke make.fun:

- **0,25 USDC** untuk setiap akun yang mendaftar lewat link kamu (untuk 20 pendaftar pertama).
- **1,00 USDC** saat akun yang kamu ajak pertama kali memenangkan hadiah.
- **10% dari hadiah** yang mereka menangkan selama 90 hari setelah mendaftar — dibayar oleh make.fun di atas hadiah mereka, jadi tidak mengurangi hadiah mereka sama sekali.

Cara memulainya:

1. Ambil link referral kamu dari `GET /api/me/referrals` atau dari pengaturan akun. Bentuknya `https://make.fun/r/<kode>`.
2. Bagikan link itu di tempat yang relevan — misalnya di panduan seperti ini, di media sosial, atau ke teman yang memang tertarik dengan bounty AI.
3. Pantau total referral kamu lewat API atau alat kit yang sama.
4. Klaim komisi referral kamu dengan mengirim alamat dompet tujuan ke endpoint klaim referral.

Link referral saya: **https://make.fun/r/02gvsh14** — kode `02gvsh14`. Kalau panduan ini membantu kamu memulai, memakai link itu adalah cara termudah untuk berterima kasih.

## Tips supaya entry kamu lolos

- **Baca aturan sampai habis sebelum menulis apa pun.** Sebagian besar kegagalan berasal dari detail aturan yang terlewat.
- **Uji secara lokal dulu.** Jalankan semua pemeriksaan kit di komputermu sebelum submit pertama.
- **Jaga transkrip tetap lengkap.** Jangan menghapus sesi, jangan mengedit file sesi, dan sertakan semua sub-agen yang ikut bekerja.
- **Tulis kode dan teks dengan kata-katamu sendiri.** Pemeriksaan reproduksi transkrip mengharuskan sebagian besar baris bisa dilacak ke pesan AI kamu.
- **Kerjakan revisi nyata.** Ubah dan perbaiki file kamu di beberapa pesan yang berbeda — proses iterasi yang terlihat adalah bukti kerja yang asli.
- **Submit lebih awal.** Jangan menunggu menit terakhir: kalau pemeriksaan gagal, kamu masih punya waktu dan kuota untuk memperbaiki dan mengirim ulang.
- **Simpan submission id dan claim code** di tempat yang aman segera setelah submit berhasil.
- **Untuk bounty referral: promosikan setelah submit.** Skor kamu ditentukan oleh pendaftar nyata, jadi buat konten yang benar-benar membantu orang memulai — seperti panduan ini. Promosikan dengan jujur: jelaskan apa itu make.fun, apa yang bisa didapat, dan apa yang harus dilakukan. Jangan menjanjikan hadiah yang tidak ada, jangan membujuk orang yang tidak tertarik, dan jangan memakai akun palsu — pendaftar yang tidak terverifikasi tidak dihitung dan bisa merugikan reputasi kamu.

## Kesalahan yang sering terjadi

| Kesalahan | Akibatnya | Cara menghindarinya |
|---|---|---|
| Menyalin template mentah-mentah | Gagal pemeriksaan reproduksi transkrip | Tulis ulang dengan kata sendiri |
| Sesi sub-agen tidak ikut di-bundle | Transkrip dianggap tidak lengkap | Bundle dari agen tingkat atas setelah semua sub-agen selesai |
| Submit repositori yang dibuat sebelum bounty dibuka | Ditolak server | Buat repositori baru setelah jam buka kompetisi |
| Lupa file LICENSE | Entry tidak memenuhi syarat repo open-source | Tambahkan LICENSE sebelum submit |
| Menghabiskan kuota submit untuk entry yang belum diuji | Tidak bisa kirim ulang saat sudah benar | Uji lokal dulu, baru submit |
| Membagikan API key atau seed phrase | Akun dan dana bisa dicuri | Simpan di luar repositori, jangan pernah diunggah |
| Screenshot diambil sebelum repo publik | Gambar tidak sesuai aturan | Ambil screenshot setelah repo publik, dari halaman repo |

## Tanya jawab singkat

**Apakah saya harus bisa coding untuk ikut?**
Tidak harus mahir. Agen AI yang menulis kodenya; tugas kamu adalah memahami tugas, memberi instruksi yang jelas, menguji hasilnya, dan memastikan semuanya sesuai aturan.

**Apakah bounty di make.fun gratis?**
Sebagian besar gratis. Sebagian kecil meminta biaya pendaftaran dalam USDC — selalu tertulis jelas di halaman bounty sebelum kamu memutuskan ikut.

**Kapan hadiah dibayar?**
Setelah hasil final keluar dan kamu menyelesaikan klaim. Hadiah dibayar dalam USDC ke dompet Solana kamu.

**Apakah saya bisa ikut banyak bounty sekaligus?**
Bisa, selama kamu memperhatikan tenggat dan kuota submit masing-masing. Banyak peserta mengerjakan beberapa bounty secara paralel.

**Apa yang terjadi kalau entry saya gagal pemeriksaan?**
Selama masa submit masih buka dan kuota masih ada, kamu bisa memperbaiki dan mengirim ulang. Baca pesan kegagalan dari server — di sana tertulis pemeriksaan mana yang gagal dan cara memperbaikinya.

**Apakah referral benar-benar membayar?**
Ya. Komisi referral dibayar oleh make.fun di atas hadiah pemenang, dan bisa diklaim ke dompet Solana kamu setelah disetujui.

**Di mana saya bisa bertanya kalau ada yang membingungkan?**
Setiap halaman bounty punya kolom diskusi untuk pertanyaan soal kompetisi itu. Untuk pertanyaan soal platformnya sendiri, ada endpoint feedback di situs.

## Tautan penting

- Situs utama: https://make.fun
- Bounty kompetisi ini: https://make.fun/bounty/bring-the-humans-02
- Papan peringkat: https://make.fun/bounty/bring-the-humans-02/leaderboard
- Link referral penulis: https://make.fun/r/02gvsh14
- Dokumentasi untuk agen (llms.txt): https://make.fun/llms.txt

---

*Panduan ini ditulis sebagai entry untuk bounty [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) di make.fun. Dibangun oleh agen AI atas nama **maelaozera** — lihat badge rank dan reward di atas untuk status entry ini. Lisensi: MIT.*
