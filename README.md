---


---

<hr>
<h1 id="instruksi-tugas-praktikum">Instruksi Tugas Praktikum</h1>
<h3 id="tujuan-tugas">Tujuan Tugas</h3>
<p>Gunakan <strong>Wireshark</strong> untuk menganalisis komunikasi jaringan pada target <strong>10.132.28.83:5001</strong>, mengeksplorasi fitur website, dan mengidentifikasi potensi eksploitasi berdasarkan rekaman data komunikasi.</p>
<h3 id="langkah-langkah">Langkah-langkah</h3>
<ol>
<li>
<p><strong>Lakukan Perekaman Komunikasi</strong></p>
<ul>
<li>Jalankan <strong>Wireshark</strong> untuk memulai perekaman jaringan. Pastikan filter ditujukan pada target <strong>10.132.28.83</strong> dengan port <strong>5001</strong>.</li>
</ul>
</li>
<li>
<p><strong>Eksplorasi Target IP</strong></p>
<ul>
<li>Akses website yang dihosting di <strong>10.132.28.83:5001</strong> melalui browser.</li>
<li>Lakukan eksplorasi fitur-fitur berikut:
<ul>
<li>Pembuatan akun.</li>
<li>Login ke website.</li>
<li>Menggunakan fitur seperti menambah komentar, menambah postingan, atau fitur lainnya yang tersedia.</li>
</ul>
</li>
</ul>
</li>
<li>
<p><strong>Simpan Rekaman Data</strong></p>
<ul>
<li>Setelah selesai eksplorasi, hentikan perekaman pada Wireshark.</li>
<li>Simpan hasil rekaman dalam file <strong>.pcap</strong> untuk dianalisis.</li>
</ul>
</li>
<li>
<p><strong>Identifikasi Hasil Rekaman</strong></p>
<ul>
<li>Gunakan Wireshark untuk membaca file <strong>.pcap</strong>.</li>
<li>Analisis komunikasi untuk menemukan:
<ul>
<li><strong>HTTP Method POST</strong>: Lihat teks atau data apa saja yang dikirimkan ke server.</li>
<li><strong>HTTP Method GET</strong>: Lihat teks atau data apa saja yang diterima dari server.</li>
</ul>
</li>
<li>Perhatikan adanya teks tersembunyi pada halaman komentar. <strong>Coba cari tahu apa isi teks tersebut.</strong></li>
</ul>
</li>
<li>
<p><strong>Percobaan Eksploitasi</strong></p>
<ul>
<li>Lakukan percobaan <strong>bypass login screen</strong> pada website target.</li>
<li>Rekam proses bypass menggunakan Wireshark.</li>
<li>Simpan hasil rekaman dan analisis file <strong>.pcap</strong> untuk melihat apakah <strong>query eksploitasi</strong> yang digunakan ikut terekam.</li>
</ul>
</li>
</ol>
<h3 id="catatan">Catatan</h3>
<ul>
<li>Laporan harus disusun rapi, menyertakan bukti tangkapan layar dari proses eksplorasi dan analisis.</li>
<li>Pastikan untuk selalu bekerja dalam lingkungan yang diizinkan untuk mencegah pelanggaran etika.</li>
</ul>
<hr>

