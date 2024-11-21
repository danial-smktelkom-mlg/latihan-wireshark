---

# **Instruksi Tugas Praktikum**

## **Tujuan Tugas**
Gunakan **Wireshark** untuk menganalisis komunikasi jaringan pada target **10.132.28.83:5001**, mengeksplorasi fitur website, dan mengidentifikasi potensi eksploitasi berdasarkan rekaman data komunikasi.

## **Langkah-langkah**

1. **Lakukan Perekaman Komunikasi**
   - Jalankan **Wireshark** untuk memulai perekaman jaringan.  
   - Pastikan filter ditujukan pada target **10.132.28.83** dengan port **5001**.

2. **Eksplorasi Target IP**
   - Akses website yang dihosting di **10.132.28.83:5001** melalui browser.  
   - Lakukan eksplorasi fitur-fitur berikut:
     - **Pembuatan akun.**
     - **Login ke website.**
     - **Menggunakan fitur seperti menambah komentar, menambah postingan, atau fitur lainnya yang tersedia.**

3. **Simpan Rekaman Data**
   - Setelah selesai eksplorasi, hentikan perekaman pada Wireshark.  
   - Simpan hasil rekaman dalam file **.pcap** untuk dianalisis.

4. **Identifikasi Hasil Rekaman**
   - Gunakan **Wireshark** untuk membaca file **.pcap**.  
   - Analisis komunikasi untuk menemukan:
     - **HTTP Method POST**: Lihat teks atau data apa saja yang dikirimkan ke server.
     - **HTTP Method GET**: Lihat teks atau data apa saja yang diterima dari server.
     - **Teks tersembunyi pada halaman komentar**: Cari tahu apa isi teks tersebut.

5. **Percobaan Eksploitasi**
   - Lakukan percobaan **bypass login screen** pada website target.  
   - Rekam proses bypass menggunakan Wireshark.  
   - Simpan hasil rekaman dan analisis file **.pcap** untuk melihat apakah **query eksploitasi** yang digunakan ikut terekam.

## **Catatan**
- **Laporan harus disusun rapi**, menyertakan bukti tangkapan layar dari proses eksplorasi dan analisis.  
- **Pastikan untuk selalu bekerja dalam lingkungan yang diizinkan** untuk mencegah pelanggaran etika.

---
