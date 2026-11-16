# Website Profil UMKM — Toko Sadam

Proyek UTS mata kuliah Pemrograman Web Dasar. Website statis multi-halaman untuk memperkenalkan Toko Sadam, usaha toko kelontong di Desa Sarang Mandi, Kecamatan Sungai Selan.

## 1. Identitas proyek

- **Nama proyek:** Website Profil Toko Sadam
- **Tema:** Profil UMKM
- **Objek:** Toko Sadam
- **Pemilik:** Bapak Sadam
- **Mulai beroperasi:** Tahun 2024
- **Lokasi:** Desa Sarang Mandi, Kecamatan Sungai Selan
- **Teknologi:** HTML5 dan CSS3
- **JavaScript:** Tidak digunakan karena bersifat opsional pada soal UTS.

## 2. Daftar halaman dan fitur

1. `index.html` — Beranda, hero section, tombol ajakan, ringkasan, dan tiga produk unggulan.
2. `tentang.html` — Sejarah singkat, visi dan misi, serta tiga orang yang diketahui membantu mengelola toko.
3. `katalog.html` — Enam produk dengan gambar ilustrasi, deskripsi, satuan, dan harga.
4. `kontak.html` — Lokasi umum, jam operasional, tabel, peta area, dan formulir kontak dengan validasi HTML5.

Semua halaman memakai navigasi yang sama dan terhubung satu sama lain.

## 3. Data toko yang digunakan

| Produk | Harga |
|---|---:|
| Beras | Rp16.000/kg |
| Gula pasir | Rp10.000/kg |
| Minyak goreng | Rp18.000/liter |
| Telur | Rp2.000/butir |
| Mi instan | Rp4.000/bungkus |
| Sabun mandi | Rp3.000/batang |

Jam operasional: setiap hari, 06.00–22.00 WIB.

Pengelola yang diketahui:
- Bapak Sadam — pemilik toko.
- Okta — anak Bapak Sadam, terkadang membantu menjaga toko.
- Bik Aisun — terkadang membantu menjaga toko.

## 4. Struktur folder

```text
toko-sadam-uts/
├── index.html
├── tentang.html
├── katalog.html
├── kontak.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── img/
│   ├── toko-placeholder.svg
│   ├── profil-placeholder.svg
│   ├── beras.svg
│   ├── gula.svg
│   ├── minyak.svg
│   ├── telur.svg
│   ├── mie.svg
│   └── sabun.svg
├── bukti/
│   └── README.txt
└── README.md
```

## 5. Cara menjalankan website

1. Ekstrak file ZIP.
2. Buka folder `toko-sadam-uts` menggunakan Visual Studio Code.
3. Buka file `index.html` di browser (atau gunakan ekstensi Live Server jika tersedia).
4. Coba semua menu: Beranda, Tentang, Katalog, dan Kontak.
5. Uji formulir dengan data yang valid dan tidak valid untuk melihat validasi bawaan browser.

Website ini adalah website statis. Formulir kontak hanya menguji validasi HTML5 dan belum mengirim pesan ke pemilik toko karena belum memakai backend.

## 6. Catatan data yang belum tersedia

Informasi berikut belum diberikan, sehingga tidak dibuat-buat:
- Alamat jalan dan nomor bangunan secara lengkap.
- Nomor telepon toko.
- Akun media sosial toko.
- Foto asli toko dan foto asli pengelola/anggota keluarga.

Gambar SVG dalam folder `img` adalah ilustrasi sementara yang dibuat untuk proyek ini, bukan foto asli. Peta pada halaman Kontak menunjukkan area Desa Sarang Mandi secara umum, bukan titik persis toko.

Visi dan misi pada halaman Tentang merupakan rumusan untuk kebutuhan website/proyek, bukan kutipan pernyataan resmi pemilik.

## 7. Sumber gambar

Seluruh gambar pada folder `img` dibuat sebagai ilustrasi SVG sederhana untuk proyek ini. Tidak mengambil foto dari situs pihak ketiga.

## 8. Pemeriksaan sesuai instruksi UTS

- [x] Empat halaman HTML yang saling terhubung.
- [x] Elemen semantik HTML: header, nav, main, section, article, footer.
- [x] Tabel menggunakan thead dan tbody.
- [x] Gambar memiliki atribut alt.
- [x] Formulir memiliki label yang terhubung dengan input.
- [x] Validasi HTML5: required, email, tel + pattern, minlength, maxlength.
- [x] CSS eksternal pada `css/style.css`.
- [x] Flexbox untuk navigasi.
- [x] CSS Grid untuk kartu katalog.
- [x] Media query untuk HP (maksimal 600px) dan desktop (minimal 992px).
- [x] Lebih dari lima variabel CSS di `:root`.
- [x] Efek hover, transition, dan keyframes.

**Catatan:** Kotak centang di atas adalah daftar pemeriksaan struktur kode, bukan bukti bahwa validasi W3C sudah dilakukan. Jalankan setiap file HTML melalui https://validator.w3.org/ dan simpan tangkapan layar hasil validasinya ke folder `bukti/`.

## 9. Persiapan pengumpulan GitHub/GitLab

Sebelum dikumpulkan:
1. Ganti nama folder/repository menjadi `NIM-Nama-UTS` sesuai identitas mahasiswa.
2. Lengkapi README dengan nama dan NIM.
3. Jalankan validasi W3C untuk keempat halaman.
4. Simpan empat screenshot validasi ke folder `bukti/`.
5. Buat minimal lima commit secara bertahap sesuai proses pengerjaan, bukan satu commit di akhir.
6. Kumpulkan tautan repository melalui Google Classroom sesuai instruksi dosen.
