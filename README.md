<p align="center">
  <img src="assets/spanduk.png" alt="Warung Bu Pita - Aneka Jajanan" width="100%">
</p>

<h1 align="center">Pengembangan Digital Twin UMKM Warung Bu Pita</h1>

<p align="center">
  Monitoring produksi, persediaan, dan penjualan untuk usaha jajanan skala kecil
</p>

<p align="center">
  <a href="#tentang-proyek"><img src="https://img.shields.io/badge/TENTANG-b91c1c?style=for-the-badge" alt="Tentang"></a>
  <a href="#ruang-lingkup"><img src="https://img.shields.io/badge/RUANG%20LINGKUP-d97706?style=for-the-badge" alt="Ruang Lingkup"></a>
  <a href="#rencana-pengembangan"><img src="https://img.shields.io/badge/RENCANA-b91c1c?style=for-the-badge" alt="Rencana"></a>
  <a href="#status-progres"><img src="https://img.shields.io/badge/PROGRES-d97706?style=for-the-badge" alt="Progres"></a>
  <a href="#rencana-fitur"><img src="https://img.shields.io/badge/FITUR-b91c1c?style=for-the-badge" alt="Fitur"></a>
  <a href="#teknologi-dan-tools"><img src="https://img.shields.io/badge/TEKNOLOGI-d97706?style=for-the-badge" alt="Teknologi"></a>
  <a href="#anggota-kelompok"><img src="https://img.shields.io/badge/ANGGOTA-b91c1c?style=for-the-badge" alt="Anggota"></a>
  <a href="#dokumentasi"><img src="https://img.shields.io/badge/DOKUMENTASI-d97706?style=for-the-badge" alt="Dokumentasi"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PROJECT-MPPL%202026-374151?style=for-the-badge" alt="Project">
  <img src="https://img.shields.io/badge/KELOMPOK-13-374151?style=for-the-badge" alt="Kelompok">
  <img src="https://img.shields.io/badge/STATUS-DEVELOPMENT-15803d?style=for-the-badge" alt="Status">
</p>

---

## Tentang Proyek

Repository ini berisi dokumentasi dan hasil pengerjaan proyek Digital Twin untuk **Warung Bu Pita**, UMKM yang menjual aneka jajanan seperti tahu isi, risol sayur, pisang coklat, dan bakso goreng, serta menyediakan frozen food.

Pencatatan produksi, stok bahan, dan penjualan di warung masih dilakukan secara manual, sehingga pemilik sulit melihat kondisi usaha secara utuh. Digital Twin dipakai sebagai representasi digital dari kondisi warung yang diperbarui dengan data aktual, agar aktivitas usaha bisa dipantau lebih terstruktur.

<p align="center">
  <img src="assets/alur.svg" alt="Alur Digital Twin: data dari warung masuk ke Digital Twin, diolah menjadi informasi untuk pemilik, lalu menjadi keputusan yang kembali ke warung" width="100%">
</p>

## Ruang Lingkup

| Aspek | Yang dipantau | Manfaat bagi warung |
|-------|---------------|---------------------|
| Produksi | Jumlah produksi harian per menu | Produksi lebih terencana dan tidak berlebih |
| Persediaan | Stok bahan baku dan barang jadi | Stok menipis diketahui lebih awal |
| Penjualan | Jumlah terjual per menu | Menu yang laris dan yang sepi mudah terlihat |

## Rencana Pengembangan

| Tahap | Kegiatan | Keluaran |
|-------|----------|----------|
| 1. Perencanaan | Menyusun ruang lingkup, pihak terkait, dan rincian pekerjaan | Project Charter, Stakeholder Register, WBS |
| 2. Analisis kebutuhan | Mengamati alur kerja warung dan mengumpulkan data produksi, stok, dan penjualan | Daftar kebutuhan dan alur proses |
| 3. Perancangan | Merancang model Digital Twin untuk tiga aspek yang dipantau | Rancangan model dan struktur data |
| 4. Pengembangan | Membangun pencatatan data dan tampilan monitoring | Prototipe sistem |
| 5. Pengujian | Mencoba prototipe dengan data nyata dari warung | Hasil uji dan catatan perbaikan |
| 6. Evaluasi | Menilai manfaat sistem bagi pemilik dan menyusun laporan akhir | Laporan proyek |

## Status Progres

| Tahap | Status | Keterangan |
|-------|:------:|------------|
| 1. Perencanaan | ![Selesai](https://img.shields.io/badge/-Selesai-15803d?style=flat-square) | Project Charter, Stakeholder Register, WBS, dan Function Point sudah tersedia |
| 2. Analisis kebutuhan | ![Selesai](https://img.shields.io/badge/-Selesai-15803d?style=flat-square) | Pengumpulan data produksi, stok, dan penjualan dari warung |
| 3. Perancangan | ![Selesai](https://img.shields.io/badge/-Selesai-15803d?style=flat-square) | Rancangan model Digital Twin dan struktur data |
| 4. Pengembangan | ![Sedang dikerjakan](https://img.shields.io/badge/-Sedang%20dikerjakan-d97706?style=flat-square) | Model 3D, pencatatan data, dan tampilan monitoring |
| 5. Pengujian | ![Belum dimulai](https://img.shields.io/badge/-Belum%20dimulai-6b7280?style=flat-square) | Uji prototipe dengan data nyata |
| 6. Evaluasi | ![Belum dimulai](https://img.shields.io/badge/-Belum%20dimulai-6b7280?style=flat-square) | Penilaian manfaat dan laporan akhir |

## Rencana Fitur

- [ ] Model 3D warung dengan area produksi, persediaan, dan penjualan
- [ ] Form pencatatan produksi, stok bahan, dan penjualan harian
- [ ] Tampilan 3D yang berubah mengikuti data
- [ ] Grafik produksi dan penjualan per menu
- [ ] Peringatan saat stok bahan menipis
- [ ] Prediksi stok habis dan rekomendasi jumlah produksi
- [ ] Pengembangan lanjutan: data dari sensor atau kasir digital

## Teknologi dan Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,md,nodejs,blender,threejs,react,vite,supabase" alt="Teknologi dan Tools">
</p>

| Kategori | Nama | Penggunaan dalam proyek | Status |
|----------|------|-------------------------|:------:|
| Version Control | [Git](https://git-scm.com/) dan [GitHub](https://github.com/) | Menyimpan dokumen, mencatat perubahan, dan kolaborasi tim | Digunakan |
| Desain Visual | [Canva](https://www.canva.com/) | Membuat spanduk dan materi visual proyek | Digunakan |
| Kolaborasi Tim | [Lark](https://www.larksuite.com/) | Koordinasi tim, pembagian tugas, dan catatan pekerjaan | Digunakan |
| Backend | [Node.js](https://nodejs.org/) | Menjalankan JavaScript di sisi server dan alat pengembangan web | Direncanakan |
| Pemodelan 3D | [Blender](https://www.blender.org/) | Membuat model 3D warung dan produk | Direncanakan |
| Tampilan Web | [Three.js](https://threejs.org/) dan [React](https://react.dev/) | Menampilkan model 3D dan grafik di browser | Direncanakan |
| Database | [Supabase](https://supabase.com/) | Menyimpan data produksi, stok, dan penjualan | Direncanakan |

## Anggota Kelompok

<p align="center">
  <img src="assets/anggota.svg" alt="Anggota Kelompok 13: Chika Dena (Project Manager), M. Firdausyah, Nazwa Dara Musyaraf, dan Irma Suraya" width="100%">
</p>

<p align="center">
  <a href="https://github.com/chikadena">@chikadena</a> ·
  <a href="https://github.com/Mfirdaus809">@Mfirdaus809</a> ·
  <a href="https://github.com/nazwa-daraa">@nazwa-daraa</a> ·
  <a href="https://github.com/irmalgs048-coder">@irmalgs048-coder</a>
</p>

## Dokumentasi

| Dokumen | Lokasi |
|---------|--------|
| Project Charter | [Digital Twin UMKM Warung Bu Pita](<./Digital Twin UMKM Warung Bu Pita>) |
| Stakeholder Register | [Digital Twin UMKM Warung Bu Pita](<./Digital Twin UMKM Warung Bu Pita>) |
| Work Breakdown Structure (WBS) | [Digital Twin UMKM Warung Bu Pita](<./Digital Twin UMKM Warung Bu Pita>) |
| Function Point | [Digital Twin UMKM Warung Bu Pita](<./Digital Twin UMKM Warung Bu Pita>) |

---

<p align="center">
  Repository ini dibuat untuk keperluan tugas perkuliahan MPPL 2026.
</p>
