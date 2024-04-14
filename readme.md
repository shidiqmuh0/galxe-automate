# Panduan Penggunaan Bookmark JavaScript untuk Otomatisasi Tugas Galxe

1. Aktifkan Bookmark Bar
Pastikan bahwa bilah bookmark di browser Anda telah diaktifkan. Jika belum, Anda dapat mengaktifkannya melalui pengaturan browser.

2. Buat Bookmark Baru
Klik kanan pada bilah bookmark dan pilih opsi "Tambah Bookmark Baru" atau serupa, tergantung pada browser yang Anda gunakan.

3. Isi Detail Bookmark:

Beri nama bookmarklet dengan yang mudah diingat, misalnya "Galxe Woosh".

4. Tempelkan kode JavaScript otomatisasi yang telah Anda sediakan sebelumnya di bidang URL atau alamat situs.
```bash
javascript:(function(){const e=[].reduce((e,t,n)=>e-t/(n+1),0);document.querySelectorAll(".d-flex.height-100.width-100.click-area").forEach(e=>e.click())})();
```
5. Simpan Bookmark
Klik "Simpan" atau "Tambah" untuk menyimpan bookmarklet yang telah Anda buat.

6. Gunakan Bookmark
Ketika Anda berada di halaman web  Galxe yang sesuai untuk otomatisasi , cukup klik bookmarklet yang telah Anda buat untuk menjalankan otomatisasi.
