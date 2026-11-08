# M-Log 
KELAS BISA DIATUR SENDIRI
- Tombol "+ Tambah kelas" di samping kelas terakhir: tulis nama kelas (misalnya 1, 2, X, XI) lalu Tambah.
- Ketuk nama kelas 3 kali dengan cepat untuk membuka "Atur kelas": ubah nama, hapus, tambah, atau pilih cepat 7-9, 10-12, 1-6.
  Kalau nama kelas diubah, materi dan kelas pengajar (misalnya 8A jadi 11A) ikut berubah. Menghapus kelas ikut menghapus materinya.
- Daftar kelas tersimpan per perangkat. Kelas yang sudah punya materi dari perangkat lain tetap muncul otomatis.
- Bagian jumlah peserta (hadir, izin, alpa) di tiap kelas sudah dihapus. Absensi pengajar tidak berubah.

FITUR TOOLBAR (di bagian atas aplikasi)
- Tema   : Dasar (Otomatis, Putih, Hitam), Profesional (Midnight, Grafit, Samudra, Anggur, Emas hitam, Royal), Pastel (Mahiru, Permen, Neko, Matcha, Awan, Sakura), Alam dan Jepang (Samurai, Hutan, Musim gugur, Salju, Zamrud, Neon), Petualangan Fantasi (Api Semangat, Bintang Sihir, Baja Raksasa, Dunia Lain), Legenda Timur (Pertapa Langit, Singgasana Naga, Pendekar Bambu).
           Setiap tema punya objek jatuh sendiri (misalnya bara api, bintang dan tongkat sihir, roda gigi, lingkaran sihir, kelopak teratai, koin emas dan angpao, daun bambu). Mode ringan mematikan objek jatuh dan latar bertekstur, tetapi warna dan gaya bingkai tema tetap dipertahankan.
           Tema tidak ikut disinkronkan (beda tiap perangkat).
- Musik  : ada 6 musik bawaan yang dapat dipilih dengan satu ketukan tanpa menyalin tautan (Lofi Santai, Piano Senja, Hening Langit, Aksi Seru, Hujan Tenang, Fokus Cyber). Musik bawaan dibuat langsung oleh aplikasi, sehingga dapat diputar tanpa internet, tetapi dapat berhenti saat layar mati atau aplikasi diminimalkan pada sebagian perangkat. Untuk lagu pilihan sendiri, tempel tautan Spotify / YouTube / YouTube Music, pemutar kecil muncul di pojok layar (per perangkat). Link audio langsung (.mp3) tetap berputar saat layar mati atau aplikasi diminimalkan; Spotify/YouTube bisa berhenti di latar belakang. Tidak ada web yang bisa memutar suara setelah ditutup sepenuhnya.
- Sinkron: tiap perangkat punya KODE 8 karakter. Masukkan kode perangkat lain lalu "Hubungkan". Perangkat pemilik kode
           akan menampilkan pop up "Apakah Anda mengenali perangkat ini?". Jika Ya, keduanya tergabung dan datanya
           disamakan otomatis (realtime). Jika Tidak, permintaan ditolak.
           Saat offline, data tetap tersimpan di perangkat dan otomatis disamakan begitu internet kembali.
           Data dienkripsi di perangkat. Penyampaiannya lewat broker MQTT publik gratis (emqx dan hivemq),
           jadi tidak perlu server sendiri, tetapi ketersediaannya tidak dijamin. Tetap pakai "Unduh cadangan".
           Kedua perangkat harus membuka aplikasi untuk saling menyamakan data. Jam perangkat sebaiknya akurat.
- Mode ringan: di menu Tema, untuk HP lama. Mematikan efek daun jatuh dan animasi berat. Otomatis nyala di HP yang spesifikasinya rendah.
- Sinkron: di daftar perangkat ada tombol "Putuskan" (tekan dua kali). Perangkat yang diputus langsung keluar dari grup dan muncul pop up "Sinkronisasi berakhir dengan perangkat ...". Kalau perangkat itu sedang offline, pop up muncul begitu ia online lagi. Perangkat lain di grup juga diberi tahu dan tidak lagi menerima data dari perangkat yang diputus. Untuk bergabung lagi, perangkat itu harus minta persetujuan lewat kode.
- Tentang: pop up berisi kutipan hari ini (berganti otomatis tiap tengah malam), tujuan website, dan pembuatnya (Ilham F. R.).
- Kalender: ketuk tanggal di panel Kegiatan untuk membuka kalender bergaya Mahiru. Titik di tanggal menandai kegiatan. Geser kiri/kanan untuk ganti bulan.
- Pengajar eksternal: tombol "Akhiri pengajar ini" (per nama) dan "Akhiri kelompok" (per sekolah). Setelah diakhiri,
  nama tidak muncul di tanggal sesudahnya, tapi data di tanggal sebelumnya tetap ada. Bisa dibuka lagi.

DATA
- Data tersimpan otomatis di perangkat masing-masing (di dalam browser), setiap kali ada perubahan.
- Tiap perangkat punya data sendiri. Data TIDAK otomatis sama antar perangkat.
- Jangan hapus data browser atau situs. Itu menghapus data absensi.
- Gunakan tombol "Unduh cadangan" secara berkala. Untuk memindahkan atau menggabungkan data ke perangkat lain,
  pakai "Pulihkan atau gabungkan" dan pilih file cadangannya.

