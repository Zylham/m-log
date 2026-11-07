# M-Log 
FITUR TOOLBAR
- Tema   : Otomatis, Putih, Hitam, Samurai, Sakura, Hutan, Musim gugur, Salju, Emas hitam, Royal, Zamrud, Neon.
           Daun/ranting yang jatuh ikut menyesuaikan tema. Tema tidak ikut disinkronkan (beda tiap perangkat).
- Musik  : tempel link Spotify / YouTube / YouTube Music, pemutar kecil muncul di pojok layar (per perangkat).
- Sinkron: tiap perangkat punya KODE 8 karakter. Masukkan kode perangkat lain lalu "Hubungkan". Perangkat pemilik kode
           akan menampilkan pop up "Apakah Anda mengenali perangkat ini?". Jika Ya, keduanya tergabung dan datanya
           disamakan otomatis (realtime). Jika Tidak, permintaan ditolak.
           Saat offline, data tetap tersimpan di perangkat dan otomatis disamakan begitu internet kembali.
           Data dienkripsi di perangkat. Penyampaiannya lewat broker MQTT publik gratis (emqx dan hivemq),
           jadi tidak perlu server sendiri, tetapi ketersediaannya tidak dijamin. Tetap pakai "Unduh cadangan".
           Kedua perangkat harus membuka aplikasi untuk saling menyamakan data. Jam perangkat sebaiknya akurat.
- Tentang: dibuat oleh Kak Ilham, berisi tujuan website.
- Kutipan harian berganti otomatis tiap tengah malam.
- Pengajar eksternal: tombol "Akhiri pengajar ini" (per nama) dan "Akhiri kelompok" (per sekolah). Setelah diakhiri,
  nama tidak muncul di tanggal sesudahnya, tapi data di tanggal sebelumnya tetap ada. Bisa dibuka lagi.

DATA
- Data tersimpan otomatis di perangkat masing-masing (di dalam browser), setiap kali ada perubahan.
- Tiap perangkat punya data sendiri. Data TIDAK otomatis sama antar perangkat.
- Jangan hapus data browser atau situs. Itu menghapus data absensi.
- Gunakan tombol "Unduh cadangan" secara berkala. Untuk memindahkan atau menggabungkan data ke perangkat lain,
  pakai "Pulihkan atau gabungkan" dan pilih file cadangannya.

MAU JADI FILE APK?
Setelah situsnya online (langkah 1), buka pwabuilder.com, masukkan alamatnya, lalu pilih paket Android.
Langkah ini butuh membuat kunci penandatanganan, dan hasilnya perlu dipasang manual (di luar Play Store).

MEMPERBARUI APLIKASI
Unggah ulang index.html dan sw.js (nama sama) ke GitHub, lalu pilih Commit directly to the main branch.
Perangkat yang sudah memasang akan memuat versi baru saat dibuka dengan internet, kadang baru terasa setelah dibuka dua kali.
