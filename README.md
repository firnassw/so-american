# 🎵 ASCII Art Music Player

[👉 Klik untuk membuka web](https://firnassw.github.io/so-american/)

Seni ASCII dinamis yang bereaksi dengan pemutar musik dan sinkronisasi lirik lagu secara *real-time*. Dibangun sepenuhnya menggunakan HTML, CSS, dan Vanilla JavaScript (Canvas API).

**✨ Cara Menggunakan / Kustomisasi**

Jika kamu ingin menggunakan kode ini untuk lagu dan fotomu sendiri, ikuti langkah-langkah mudah berikut:

1. **Unduh Proyek:** *Clone* atau *Download ZIP* repository ini ke komputermu.
2. **Ganti Lagu:** Masukkan file lagu `.mp3` pilihanmu ke dalam folder proyek, lalu ubah nama file pada atribut `src` di tag `<audio>` yang ada di dalam `index.html`.
3. **Ganti Gambar:** Cari tag `<img id="bgImage">` di dalam file `index.html`, lalu ganti link pada `src` dengan *Direct Link* gambar barumu (pastikan berakhiran `.jpg` atau `.png`).
4. **Atur Waktu Lirik:** Cari bagian `config.lyrics` di dalam kode JavaScript. Sesuaikan teks lirik dengan lagumu, lalu atur `startTime` (waktu mulai) dan `endTime` (waktu selesai) dalam satuan detik.
5. **Jalankan:** Buka file `index.html` menggunakan browser. (Disarankan menggunakan ekstensi *Live Server* di VSCode agar sistem Canvas API berjalan optimal).
