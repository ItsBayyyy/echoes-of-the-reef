# Echoes of the Reef

**Echoes of the Reef** adalah game *2D Casual Platformer* berbasis web yang dikembangkan untuk kompetisi **ICONLAB 2026**. Di balik visual *pixel-art* yang lucu dan ceria, game ini mengusung misi **SDG 14: Life Below Water** dengan menghadirkan *plot twist* psikologis mengenai polusi laut dan bahaya sampah plastik/kaca.

Dikembangkan oleh **Tim Kentang Goreng** - Universitas Primakara.

---

## Mainkan Sekarang (Live Demo)

Jika Anda ingin mencoba game ini secara langsung tanpa perlu menjalankan server lokal, silakan kunjungi tautan berikut:

👉 **[KLIK DI SINI UNTUK BERMAIN](https://itsbayyyy.github.io/echoes-of-the-reef/)**

*(Catatan: Pastikan browser Anda sudah mendukung Web Audio API dan HTML5 Canvas untuk pengalaman terbaik.)*

---

## Fitur Utama
- **No Engine Required:** Dibangun murni menggunakan HTML5 Canvas dan Vanilla JavaScript.
- **Dynamic Weight System:** Mekanik di mana "permata" yang dikumpulkan akan menumpuk dan secara fisik memperlambat pergerakan karakter.
- **Dynamic Visual & Audio Bleaching:** Warna lautan perlahan memudar (abu-abu) dan musik (BGM) mendistorsi/melambat seiring bertambahnya tumpukan sampah pemain.
- **Procedural Sound Effects:** Suara lompatan dan efek mengambil item di-generate langsung menggunakan matematika *Web Audio API* (tanpa file mp3 tambahan).
- **Save & Load Progress:** Menyimpan progres pemain (skor, posisi, inventaris tumpukan) secara otomatis menggunakan `LocalStorage` browser.
- **Mobile Friendly:** Responsif terhadap berbagai ukuran layar dengan dukungan *virtual button* untuk perangkat sentuh.

---

## Struktur Direktori
Pastikan struktur folder Anda terlihat seperti ini agar game dapat memuat seluruh aset dengan benar:

```text
📁 echoes-of-the-reef/
├── 📄 index.html             (File utama game)
├── 📄 README.md              (File dokumentasi ini)
└── 📁 assets/                (Folder utama aset)
    ├── 📄 name.png, floor.png, botol.png, dll...
    ├── 📁 audio/             (menu.mp3, piano.mp3, cowpoke.mp3)
    ├── 📁 button/            (new.png, resume.png, mute.png, unmute.png)
    ├── 📁 crystal/           (Folder animasi kristal hijau & merah)
    └── 📁 kemo/              (Folder animasi karakter: kemo_idle, kemo_walk, kemo_jump)
```

## Credits & Attributions
Seluruh aset visual karakter dan lingkungan dibuat oleh tim pengembang. Namun, kami ingin memberikan penghargaan penuh kepada kreator asli atas aset audio yang digunakan dalam game ini secara non-komersial/edukasional:

- **Menu Soundtrack (`menu.mp3`)**: Oleh Dire Dire Docks - Didapatkan dari Super Mario.
- **In-Game BGM (`piano.mp3`)**: Oleh Dreaming - Didapatkan dari Oak Studios.
- **Ending/Cutscene BGM (`cowpoke.mp3`)**: Oleh Cowpoke - Didapatkan dari Isaiah Sheffield.
- **Sound Effects (Jump & Item Pickup)**: Dibuat secara prosedural (sintesis) murni menggunakan kode *Web Audio API*.

*All copyrighted audio materials belong to their respective owners. Used here under Fair Use for an educational/non-commercial competition project.*