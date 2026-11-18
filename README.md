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


<!-- RUANG LINGKUP -->
<h2>Ruang Lingkup Proyek</h2>

<table>
  <thead>
    <tr>
      <th align="center" width="16%">ASPEK</th>
      <th width="38%">YANG DIPANTAU</th>
      <th width="46%">MANFAAT BAGI WARUNG</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong>Produksi</strong></td>
      <td>Jumlah produksi harian per menu</td>
      <td>Produksi lebih terencana dan tidak berlebih</td>
    </tr>
    <tr>
      <td align="center"><strong>Persediaan</strong></td>
      <td>Stok bahan baku dan barang jadi</td>
      <td>Stok menipis diketahui lebih awal</td>
    </tr>
    <tr>
      <td align="center"><strong>Penjualan</strong></td>
      <td>Jumlah terjual per menu</td>
      <td>Menu yang laris dan yang sepi mudah terlihat</td>
    </tr>
  </tbody>
</table>

<br/>

<!-- RENCANA PENGEMBANGAN -->
<h2>Rencana Pengembangan</h2>

<table>
  <thead>
    <tr>
      <th align="center" width="8%">NO.</th>
      <th width="21%">TAHAP</th>
      <th width="43%">KEGIATAN</th>
      <th width="28%">KELUARAN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">01</td>
      <td><strong>Perencanaan</strong></td>
      <td>Menyusun ruang lingkup, pihak terkait, dan rincian pekerjaan</td>
      <td>Project Charter, Stakeholder Register, WBS</td>
    </tr>
    <tr>
      <td align="center">02</td>
      <td><strong>Analisis Kebutuhan</strong></td>
      <td>Mengamati alur kerja warung dan mengumpulkan data produksi, stok, dan penjualan</td>
      <td>Daftar kebutuhan dan alur proses</td>
    </tr>
    <tr>
      <td align="center">03</td>
      <td><strong>Perancangan</strong></td>
      <td>Merancang model Digital Twin untuk tiga aspek yang dipantau</td>
      <td>Rancangan model dan struktur data</td>
    </tr>
    <tr>
      <td align="center">04</td>
      <td><strong>Pengembangan</strong></td>
      <td>Membangun pencatatan data dan tampilan monitoring</td>
      <td>Prototipe sistem</td>
    </tr>
    <tr>
      <td align="center">05</td>
      <td><strong>Pengujian</strong></td>
      <td>Mencoba prototipe dengan data nyata dari warung</td>
      <td>Hasil uji dan catatan perbaikan</td>
    </tr>
    <tr>
      <td align="center">06</td>
      <td><strong>Evaluasi</strong></td>
      <td>Menilai manfaat sistem bagi pemilik dan menyusun laporan akhir</td>
      <td>Laporan proyek</td>
    </tr>
  </tbody>
</table>

<br/>

<!-- STATUS PROGRES -->
<h2>Status Progres</h2>

<table>
  <thead>
    <tr>
      <th align="center" width="8%">NO.</th>
      <th width="23%">TAHAP</th>
      <th align="center" width="19%">STATUS</th>
      <th width="50%">KETERANGAN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">01</td>
      <td>Perencanaan</td>
      <td align="center">
        <img src="https://img.shields.io/badge/SELESAI-238636?style=flat-square" />
      </td>
      <td>Project Charter, Stakeholder Register, WBS, dan Function Point sudah tersedia</td>
    </tr>
    <tr>
      <td align="center">02</td>
      <td>Analisis Kebutuhan</td>
      <td align="center">
        <img src="https://img.shields.io/badge/SELESAI-238636?style=flat-square" />
      </td>
      <td>Pengumpulan data produksi, stok, dan penjualan dari warung</td>
    </tr>
    <tr>
      <td align="center">03</td>
      <td>Perancangan</td>
      <td align="center">
        <img src="https://img.shields.io/badge/SELESAI-238636?style=flat-square" />
      </td>
      <td>Rancangan model Digital Twin dan struktur data</td>
    </tr>
    <tr>
      <td align="center">04</td>
      <td>Pengembangan</td>
      <td align="center">
        <img src="https://img.shields.io/badge/BERJALAN-E3A008?style=flat-square" />
      </td>
      <td>Model 3D, pencatatan data, dan tampilan monitoring</td>
    </tr>
    <tr>
      <td align="center">05</td>
      <td>Pengujian</td>
      <td align="center">
        <img src="https://img.shields.io/badge/BELUM_DIMULAI-64748B?style=flat-square" />
      </td>
      <td>Uji prototipe dengan data nyata</td>
    </tr>
    <tr>
      <td align="center">06</td>
      <td>Evaluasi</td>
      <td align="center">
        <img src="https://img.shields.io/badge/BELUM_DIMULAI-64748B?style=flat-square" />
      </td>
      <td>Penilaian manfaat dan laporan akhir</td>
    </tr>
  </tbody>
</table>

<br/>

<!-- RENCANA FITUR -->
<h2>Rencana Fitur</h2>

<table>
  <thead>
    <tr>
      <th align="center" width="8%">NO.</th>
      <th width="72%">FITUR YANG DIRENCANAKAN</th>
      <th align="center" width="20%">KATEGORI</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">01</td>
      <td>Model 3D warung dengan area produksi, persediaan, dan penjualan</td>
      <td align="center">Visualisasi</td>
    </tr>
    <tr>
      <td align="center">02</td>
      <td>Form pencatatan produksi, stok bahan, dan penjualan harian</td>
      <td align="center">Pencatatan</td>
    </tr>
    <tr>
      <td align="center">03</td>
      <td>Tampilan 3D yang berubah mengikuti data</td>
      <td align="center">Monitoring</td>
    </tr>
    <tr>
      <td align="center">04</td>
      <td>Grafik produksi dan penjualan per menu</td>
      <td align="center">Analitik</td>
    </tr>
    <tr>
      <td align="center">05</td>
      <td>Peringatan saat stok bahan menipis</td>
      <td align="center">Notifikasi</td>
    </tr>
    <tr>
      <td align="center">06</td>
      <td>Prediksi stok habis dan rekomendasi jumlah produksi</td>
      <td align="center">Prediksi</td>
    </tr>
    <tr>
      <td align="center">07</td>
      <td>Pengembangan lanjutan: data dari sensor atau kasir digital</td>
      <td align="center">Ekspansi</td>
    </tr>
  </tbody>
</table>

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
