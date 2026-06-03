# 🎮 Fortune-Fall 

Game 2D sederhana berbasis Phaser.js di mana pemain harus mengumpulkan aset untuk mendapatkan skor sebanyak mungkin dan menghindari meteor yang dapat mengakhiri permainan.

 📌 Deskripsi

Fortune Fall adalah game arcade sederhana yang dibuat menggunakan Phaser 3. Pemain mengendalikan karakter yang dapat bergerak ke kiri, kanan, dan melompat untuk menangkap aset yang jatuh.

Sebelum bermain, pemain harus memasukkan ID User terlebih dahulu. Skor akan bertambah setiap kali berhasil menangkap aset dan permainan berakhir jika pemain terkena meteor.

---

✨ Fitur

* Sistem Login User menggunakan Local Storage
* Menyimpan ID User secara otomatis
* Efek suara dan musik latar
* Sistem skor
* Objek aset dengan nilai berbeda
* Efek visual animasi pada objek
* Tampilan Game Over
* Tombol Restart Game
* Responsive menggunakan Phaser Scale FIT

---

🎯 Cara Bermain

 Kontrol

| Tombol | Fungsi            |
| ------ | ----------------- |
| ←      | Bergerak ke kiri  |
| →      | Bergerak ke kanan |
| ↑      | Melompat          |
| SPACE  | Memulai permainan |

Aturan Permainan

* Tangkap aset **Kaya** untuk mendapatkan **10 poin**.
* Tangkap aset **Rumah** untuk mendapatkan **50 poin**.
* Hindari **Meteor**.
* Jika terkena meteor, permainan akan berakhir.

---

🛠️ Teknologi

* HTML5
* CSS3
* JavaScript
* Phaser 3.60.0

---
 📂 Struktur Folder

```text
Beauty_Bone/
│
├── assets/
├── Index.html
├── bg.png
├── player.png
├── kaya.png
├── Rumah2.png
├── meteor.png
├── bg.mp3
├── bom.mp3
├── gameover.mp3
├── money.mp3
└── rumah.wav
```

## 🚀 Menjalankan Game

1. Clone repository:

```bash
git clone https://github.com/username/Beauty_Bone.git
```

2. Masuk ke folder project:

```bash
cd Beauty_Bone
```

3. Jalankan menggunakan Live Server atau browser.

---

 📊 Sistem Skor

| Objek  | Poin      |
| ------ | --------- |
| Kaya   | +10       |
| Rumah  | +50       |
| Meteor | Game Over |

---

👨‍💻 Pengembang

Dibuat menggunakan Phaser.js sebagai proyek pembelajaran pengembangan game 2D berbasis web.

 📄 Lisensi

Project ini dibuat untuk tujuan pembelajaran dan pengembangan portofolio.
