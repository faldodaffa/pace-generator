# PACE SE2026 (Prompt Assistant & Creative Engine)

PACE SE2026 adalah aplikasi generator prompt cerdas berbasis web yang dirancang khusus untuk mendukung Tim Kerja Kehumasan Badan Pusat Statistik (BPS) dalam memproduksi aset visual Sensus Ekonomi 2026.
Aplikasi ini berfungsi sebagai jembatan antara standar branding BPS dan teknologi Generative AI (seperti Google Gemini, Midjourney, atau DALL-E), memastikan setiap gambar yang dihasilkan memiliki konsistensi karakter, akurasi atribut, dan relevansi konteks ekonomi.

Fitur Utama
1. Standardisasi Karakter "Bung Itung" (Anatomy Lock)
Menggunakan algoritma prompting khusus untuk menjaga konsistensi bentuk wajah (mata, hidung, rasio kepala) maskot "Bung Itung" dan "Mbak Sasa", meskipun diubah ke dalam berbagai pose, gender, atau kostum.

2. Integrasi KBLI 2025 (Klasifikasi Baku Lapangan Usaha)
Database aplikasi telah terintegrasi dengan KBLI 2025. Pengguna cukup memilih sektor ekonomi (misal: Pertanian, Konstruksi, atau Digital), dan aplikasi otomatis menyusun deskripsi pakaian (wearables), alat kerja (held items), dan latar belakang (environment) yang relevan secara teknis.

3. Smart Wearable & Modesty Logic
Sistem logika cerdas untuk mencegah hallucination (kesalahan) pada AI:
-	Logika Hijab: Jika karakter berhijab dipilih, deskripsi rambut otomatis dihapus dan pakaian disesuaikan menjadi lengan panjang/tertutup.
-	Logika Topi/Helm: Jika memakai helm proyek atau mahkota adat, deskripsi rambut disesuaikan (terlihat sedikit atau tertutup total) agar tidak clipping (tembus).
4. Fitur Kustomisasi Nusantara (Edisi Nasional)
Dirancang inklusif untuk seluruh BPS Provinsi di Indonesia:

-	Custom Aksesoris: Memungkinkan input teks manual untuk aksesoris adat lokal (misal: Udeng Bali, Ulos Batak, Tanjak Melayu).
-	Preset Papua: Dilengkapi preset khusus untuk Noken dan Mahkota Bulu Kasuari dengan detail tekstur yang presisi.
-	Tone Kulit: Pilihan warna kulit yang variatif (Kuning Langsat, Sawo Matang, Gelap Eksotis) dengan logika Image Weight dinamis untuk mencegah warna kulit "belang".
5. Output JSON untuk Image-to-Image
Menghasilkan output dalam format struktur JSON yang rapi, memisahkan Positive Prompt, Negative Prompt, dan parameter teknis (Aspect Ratio, Image Weight). Format ini dioptimalkan untuk metode Image-to-Image agar hasil generate sangat mirip dengan referensi asli.

Teknologi
-	Platform: Web-based (HTML5, CSS3 Tailwind, Vanilla JavaScript).
-	Sifat: Client-side (Berjalan sepenuhnya di browser pengguna, tidak menyimpan data ke server, aman dan cepat).
-	Lisensi: Open Source / Bebas digunakan untuk kepentingan dinas BPS.
-	Kompatibilitas: Responsif di Desktop, Tablet, dan Smartphone.
Cara Penggunaan Singkat
1.	Pilih Identitas: Tentukan gender, warna kulit, dan ekspresi wajah karakter.
2.	Pilih Konteks: Tentukan Sektor Ekonomi (KBLI) atau biarkan "Tanpa Konteks" untuk aset polos.
3.	Atur Aksesoris: Pilih topi/helm atau masukkan aksesoris adat kustom.
4.	Generate: Klik tombol untuk membuat prompt.
5.	Eksekusi: Salin prompt JSON dan aset referensi (tersedia di menu atas) ke dalam AI Generator (Google Gemini/Midjourney).
👨‍💻 Kredit Pengembang
Tim Pelaksana SE 2026 - Tim Kerja Kehumasan
BPS Provinsi Papua
© 2026
Konsep & Pengembangan: @faldodaffa
<img width="468" height="645" alt="image" src="https://github.com/user-attachments/assets/e2dd0111-7468-4ff5-8f91-989da6b20650" />
