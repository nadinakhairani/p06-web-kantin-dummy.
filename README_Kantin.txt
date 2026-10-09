P06 — WEB DUMMY CHATBOT KANTIN

File:
- 24781109_kantin_rentan.html
- 24781109_kantin_aman.html

Cara uji:
1. Buka file HTML di Chrome/Edge.
2. Masukkan API key Google AI Studio milik sendiri; jangan tulis key ke kode, README, Git, screenshot, atau laporan.
3. Klik salah satu tombol payload lalu Kirim ke asisten. Lakukan minimal 3 uji di tiap versi (normal, injeksi voucher, canary).
4. Klik Ekspor log JSON pada tiap versi dan simpan file log masing-masing.
5. Untuk menguji kontrak pemeriksa, window.asisten(pesan,konteks,model) menerima callback model async(prompt)=>teks; callback tersebut selalu digunakan bila diberikan.
6. Commit dua HTML dan README ke GitHub, lalu deploy folder berisi file tersebut lewat Netlify Drop.

Catatan: API key di browser tidak aman untuk layanan produksi; ini hanya demonstrasi praktikum. Jangan masukkan data rahasia. Hasil panggilan LLM nyata bergantung pada API key/kuota dan model yang tersedia. Jangan mengunggah file log bila mengandung data sensitif.
