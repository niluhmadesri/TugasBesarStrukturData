## Anggota Kelompok
- Ni Luh Made Sri Utami P.	(103102400055) 

- Yoan Natasya Agustin	    (103102430001) 

- Fira Adelia Septa 		(103102430002) 

- Safa Ayu Artanti  		(103102430004) 


# 🎵 SyfoPlay – Aplikasi Pemutar Musik Berbasis Python

## Deskripsi Aplikasi
SyfoPlay adalah aplikasi pemutar musik berbasis Python yang menggunakan antarmuka grafis (GUI) serta pustaka pygame untuk pemutaran audio. Aplikasi ini dikembangkan sebagai tugas besar dengan tujuan mengimplementasikan konsep struktur data dan algoritma dalam aplikasi nyata tanpa menggunakan database eksternal.

## Fitur Aplikasi
- Login dan manajemen pengguna
- Library lagu
- Pemutaran audio (play, pause, stop)
- Pengaturan volume
- Playlist pengguna
- Antrian lagu (Queue / FIFO)
- Riwayat pemutaran lagu (Stack / LIFO)
- Penyimpanan data menggunakan file JSON

## Teknologi yang Digunakan
- Python 3
- Tkinter / CustomTkinter
- Pygame (Audio Playback)
- JSON
- Struktur Data: Linked List, Stack, Queue

## Cara Menjalankan Program

### 1. Instalasi
Pastikan Python sudah terpasang.

Install library yang dibutuhkan:
pip install pygame customtkinter
### 2. Menjalankan Aplikasi
Masuk ke folder proyek, lalu jalankan:
python main.py
Catatan:
- Jika pygame tidak tersedia, aplikasi akan berjalan dalam mode simulasi.

## Struktur Proyek

SyfoPlay_Tubes_Strukdat/
├── Aplikasi_Syfoplay.ipynb
├── README.md
├── syfoplayCLI.ipynb
├── syfoplayGUI.ipynb
├── syfoplay_library_gui.json
├── syfoplay_users_gui.json
Keterangan:
- `Aplikasi_Syfoplay.ipynb` : Merupakan file utama aplikasi SyfoPlay yang berisi integrasi logika program, pengelolaan struktur data, serta pengujian fitur pemutar musik secara keseluruhan.
- `README.md` : Dokumentasi aplikasi.
- `syfoplayCLI.ipynb` : Berisi implementasi aplikasi SyfoPlay berbasis Command Line Interface (CLI) yang digunakan untuk pengujian logika program dan struktur data tanpa antarmuka grafis.
- `syfoplayGUI.ipynb` : Merupakan file aplikasi SyfoPlay berbasis Graphical User Interface (GUI) yang dibangun menggunakan CustomTkinter, mencakup fitur login, manajemen lagu, playlist user, dan pemutaran audio.
- `syfoplay_library_gui.json` : Menyimpan data lagu (library) secara permanen menggunakan format JSON.
- `syfoplay_users_gui.json` : Menyimpan data pengguna dan playlist.
- `README.md` : Dokumentasi aplikasi.
