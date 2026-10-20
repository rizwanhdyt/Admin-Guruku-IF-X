ADMIN GURUKU — PROTOTIPE 0.1

Fitur: tampilan ramah HP, kategori dokumen, pencarian isi, daftar isi otomatis, favorit, pengaturan ukuran teks, buat/edit/hapus, impor TXT/Markdown, ekspor satu dokumen, cadangan/pemulihan koleksi JSON, penyimpanan lokal, manifest dan service worker untuk PWA.

PENTING: konten CP/TP dan modul ajar yang muncul adalah DEMO, bukan kutipan resmi. Ganti dengan dokumen yang sudah diverifikasi.

CARA DEPLOY DARI HP (contoh alur hosting statis):
1. Ekstrak ZIP ini menggunakan pengelola berkas Android.
2. Gunakan layanan hosting statis yang mendukung unggah folder/proyek melalui browser HP. Unggah isi folder ini (index.html, manifest.json, sw.js) ke situs baru.
3. Setelah situs memiliki alamat HTTPS, buka alamat itu di Chrome Android.
4. Pilih menu ⋮ > Tambahkan ke layar utama / Install app (nama menu bisa berbeda).
5. Buka aplikasi sekali dengan internet agar service worker menyimpan file aplikasi. Setelah itu shell aplikasi bisa dibuka offline.

UJI LOKAL: membuka index.html langsung dari file manager bisa menguji banyak fitur, tetapi instalasi PWA dan service worker memerlukan HTTPS atau localhost.

BATASAN: DOCX/PDF belum diimpor otomatis. Salin teks dari dokumen ke editor aplikasi atau simpan sebagai TXT/Markdown lalu impor. Data disimpan di browser/perangkat itu saja; tidak ada login atau sinkronisasi otomatis. Ekspor koleksi JSON untuk pindah perangkat. Cadangkan berkala karena penghapusan data browser dapat menghilangkan dokumen.

Untuk dipakai banyak sekolah: masing-masing sekolah dapat memasang aplikasi yang sama. Berbagi koleksi saat ini dilakukan lewat file cadangan JSON; sinkronisasi terpusat membutuhkan backend dan bukan offline murni.
