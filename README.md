# 🪖 Operasi Garuda 3D: Pasukan TNI Menjaga Nusantara

Game 3D petualangan bergaya Roblox. Pemain menjadi **prajurit TNI** yang melindungi warga **Pulau Rajawali** (pulau fiktif) dari **Pasukan Bayangan** (kelompok pengacau keamanan fiktif).

- Terdiri dari **5 misi bertingkat** dengan **kondisi alam** yang berbeda dan **dukungan alutsista**.
- Tersedia dalam **5 bahasa**.
- Dibuat untuk **Kuttab Raudhah Nabawiyah (KRN)**.
- Semua isi game ada dalam satu file `index.html`.

> 🕊️ **Aman untuk semua umur:** tidak ada darah dan tidak ada yang tewas. Musuh yang dilumpuhkan akan **menyerah (angkat tangan) lalu ditangkap ⛓️**. Granat yang dipakai adalah *granat kejut* yang membuat musuh pusing. Pulau dan musuhnya fiktif, tidak terkait daerah, suku, atau agama mana pun.

## 5 Misi (level)

| # | Misi | Kondisi alam | Alutsista / dukungan | Tugas utama |
|---|---|---|---|---|
| 1 | 🌴 Hutan Hujan Tropis | hutan lebat, gerimis, sungai | terjun payung dari **Hercules**, drone, helikopter | foto kamp, lumpuhkan penjaga, bebaskan 3 warga, dijemput heli |
| 2 | 🌋 Lereng Gunung Berapi | gunung berapi berasap, hujan abu, gempa kecil | helikopter, drone, jet tempur | naik punggung bukit, foto markas, lumpuhkan penjaga menara, matikan alarm, ambil data rahasia |
| 3 | 🌊 Pantai & Pelabuhan | ombak laut, senja | kapal perang **KRI**, helikopter | amankan dermaga, ledakkan gudang senjata, hancurkan **panser** musuh, kabur naik kapal cepat |
| 4 | 🌙 Markas Komando Malam | malam, hujan petir, lampu sorot | **kacamata malam**, senter, drone, heli | susupi kota latihan, naik lift menara kontrol, **retas komputer dengan kode matematika**, kabur dari panser |
| 5 | 🏙️ Kota Pesisir: Operasi Final | fajar | **Tank Harimau** (bisa dikendarai), jet tempur | hancurkan barikade, bebaskan sandera, kalahkan Komandan Bayangan, **jinakkan bom (soal matematika)**, kibarkan **Sang Merah Putih** |

Misi berikutnya terbuka setelah misi sebelumnya selesai. Bintang ⭐ dihitung begini:

| Bintang | Syarat |
|---|---|
| ⭐ | misi selesai |
| ⭐⭐ | terluka paling banyak 1 kali |
| ⭐⭐⭐ | menemukan kedua kartu intel 📁 |

Misi 5 ditutup dengan upacara bendera, pesawat jet berasap merah-putih, kembang api, dan **Piagam Pahlawan Nusantara** (PNG) berlogo KRN.

## Fitur

- **Pilihan prajurit:**
  - putra atau putri (berjilbab);
  - matra **TNI AD / AL / AU** dengan warna loreng yang berbeda.
- **Tingkat kesulitan:**
  - 🧒 **Anak:** bidikan sangat dibantu dan musuh lemah. Cocok untuk anak kecil, semua bisa menang.
  - 🧑 **Remaja:** sedang.
  - 🎖️ **Komando:** sulit.
- **Rekan Sertu Bima:** ikut bertempur, melempar granat kejut, dan menolong saat kamu terluka. Tidak ada "game over"; kamu selalu bangkit lagi.
- **Dukungan (tombol 1–4):** dibayar dengan poin ⭐ dari menangkap musuh dan menyelesaikan tugas.
  - 🚁 **Helikopter Garuda:** menembaki musuh dan panser.
  - 🛸 **Drone intai:** menandai semua musuh.
  - 📦 **Suplai:** menambah kesehatan dan granat.
  - ✈️ **Jet tempur:** membuat semua musuh terkejut.
- **Radio:** dialog dibacakan (Kapten Sari di Markas, Sertu Bima, pilot), dan ada minimap.
- **Puzzle matematika:** kode sandi komputer dan kabel bom. Soalnya menyesuaikan tingkat kesulitan:

  | Tingkat | Jenis soal |
  |---|---|
  | Anak | penjumlahan |
  | Remaja | perkalian |
  | Komando | persamaan |

- **Kartu Intel 📁:** 10 fakta (TNI, Pindad, KRI, Bhinneka Tunggal Ika, Cincin Api, dan lain-lain) yang terkumpul di menu 📚.
- **Nilai Prajurit:** pesan karakter setiap selesai misi, yaitu kerja sama, melindungi rakyat, disiplin, adil, dan cinta tanah air.

## Bahasa

Bahasa dipilih di menu atau di menu ⏸ Jeda:

- Bahasa Indonesia
- Basa Jawa
- Basa Sunda
- English
- العربية (tampilan kanan-ke-kiri)

> Catatan:
> - Terjemahan Jawa, Sunda, dan Arab sebaiknya dicek oleh guru penutur asli. Semua teks ada di bagian `const TX = {...}` dalam `index.html`, dengan urutan `[Indonesia, Jawa, Sunda, English, Arab]`.
> - Suara radio memakai suara bawaan perangkat. Untuk Jawa dan Sunda, biasanya yang terdengar adalah suara bahasa Indonesia.

## Kontrol

| Aksi | Laptop | HP / Tablet |
|---|---|---|
| Mulai kendali mouse | **klik layar** (Esc untuk melepas) | — |
| Berjalan / lari | W A S D, Shift | jempol kiri (geser jauh = lari) |
| Melihat | gerakkan mouse | geser layar kanan |
| Tembak / bidik | klik kiri / klik kanan | 🔫 / 🎯 |
| Lompat / jongkok | Spasi / C | ⤒ / 🧎 |
| Isi peluru / granat kejut | R / G | 🔄 / 💣 |
| Interaksi, naik/turun tank | tahan **E** | ✋ |
| Foto drone | F | 📸 |
| Dukungan | 1 2 3 4 | tombol di layar |
| Kacamata malam | N | 🥽 |
| Jeda | P | ⏸ |

Di dalam tank: W/S untuk maju/mundur, A/D untuk belok, mouse untuk mengarahkan meriam, klik untuk menembak, dan E untuk turun.

## Upload ke GitHub Pages

1. Buka [github.com](https://github.com) → **New repository** → beri nama, misalnya `operasi-garuda-3d` → **Public** → **Create repository**.
2. Klik **uploading an existing file**, seret `index.html` dan `README.md`, lalu klik **Commit changes**.
3. Buka **Settings → Pages** → pilih **Deploy from a branch** → **main** / **(root)** → **Save**.
4. Setelah 1–2 menit, buka `https://NAMA-AKUN.github.io/operasi-garuda-3d/`.

Game perlu internet saat pertama dibuka (untuk mesin 3D three.js dan font). Progres, bintang, dan kartu intel tersimpan otomatis di perangkat. Untuk laptop, disarankan memakai Chrome atau Edge.

## Hubungan dengan film

Alur misi meniru struktur misi pada video gameplay yang diberikan (mendekati markas dari balik bukit, memotret markas, melumpuhkan penjaga di atas dan di bawah, mematikan alarm perimeter, masuk ke gedung utama, "latihan tembak langsung" di kota latihan, naik lift ke menara kontrol, meretas komputer dengan sandi dari catatan di meja, dikejar panser, menerobos ke pintu keluar, lalu dijemput). Semua tokoh, tempat, dan grafisnya dibuat ulang secara orisinal untuk konteks TNI dan pendidikan, tanpa memakai aset atau cerita dari game aslinya.

---
Kuttab Raudhah Nabawiyah · Jl. Bima Raya Ujung No. 31, Cibuluh, Bogor Utara, Kota Bogor, Jawa Barat
Mesin 3D: three.js · Font: Fredoka & Cairo (Google Fonts)
