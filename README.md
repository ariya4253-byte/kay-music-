# KAY MUSIC V1

Website musik statis untuk GitHub Pages atau Vercel.

## Fitur
- Pemutar audio: play/pause, next/previous, seek, volume.
- Impor URL audio langsung (MP3, OGG, WAV, dan format yang didukung browser).
- Impor file audio dari perangkat.
- Pencarian, filter, hapus lagu.
- URL audio disimpan di LocalStorage browser.
- Tidak ada iklan yang ditambahkan oleh website ini.

## Batasan penting
- Link Spotify biasa bukan URL file audio, jadi tidak dapat dipakai sebagai sumber audio langsung.
- Gunakan file atau URL audio yang kamu punya hak/izin untuk streaming.
- File lokal memakai object URL dan tidak bertahan setelah sesi browser berakhir. URL audio tersimpan hanya pada browser/perangkat tersebut.
- Ini versi statis; tidak ada akun pengguna, sinkronisasi lintas perangkat, atau penyimpanan audio di server.

## Deploy ke GitHub
1. Buat repository baru bernama `kay-music`.
2. Upload `index.html` dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main`, folder `/(root)`, lalu **Save**.
6. Tunggu proses deploy selesai. GitHub akan menampilkan URL website di halaman Pages.

Atau di Vercel: import repository ini dan deploy sebagai project statis.
