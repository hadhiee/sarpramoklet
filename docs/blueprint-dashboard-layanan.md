# Blueprint Aplikasi Dashboard Layanan Sarpras, IT, dan Laboratorium

## 1. Tujuan Aplikasi
Aplikasi ini menjadi pusat kendali layanan **Sarana Prasarana (Sarpras)**, **IT**, dan **Laboratorium**. Seluruh pekerjaan unit dicatat end-to-end dari:

1. usulan,
2. analisis kebutuhan,
3. perencanaan,
4. pelaksanaan,
5. monitoring,
6. evaluasi.

Setiap aktivitas memiliki atribut standar: **PIC**, target waktu, indikator keberhasilan, bukti pelaksanaan, dan status progres. Dengan pendekatan ini, pimpinan dan pelaksana dapat memantau capaian secara real-time, mengidentifikasi hambatan lebih awal, dan memastikan layanan terukur serta akuntabel.

---

## 2. Struktur Proses Inti per Unit

## 2.1 IT
Ruang lingkup:
- Development Software (aplikasi, database)
- Infrastruktur (network, IT support)
- IT Policy (platform, security, PDP)

Objek kerja: tiket operasional dan proyek pengembangan.

Metrik utama:
- jumlah permintaan masuk,
- jenis layanan,
- progres pengerjaan,
- waktu respon,
- waktu selesai,
- jumlah gangguan berulang,
- kepatuhan keamanan & PDP.

## 2.2 Laboratorium
Ruang lingkup:
- Praktikum & Perangkat (analisis kebutuhan, pengembangan, pengelolaan, perbaikan)
- Digitalisasi Pembelajaran (pra produksi, produksi, pasca produksi)
- Riset dan Inovasi (ideasi, inkubasi, HKI)

Metrik utama:
- kesiapan perangkat praktikum,
- keterpakaian lab,
- jumlah konten pembelajaran diproduksi,
- jumlah inovasi dalam pipeline,
- progres HKI,
- kepuasan guru/siswa.

## 2.3 Sarpras
Ruang lingkup:
- Manajemen Gedung & Bangunan
- Fixed Asset Management

Metrik utama:
- kondisi gedung/ruang,
- utilisasi ruang,
- laporan kerusakan,
- progres perbaikan,
- inventaris aset,
- umur aset,
- jadwal preventive maintenance,
- kebutuhan pengadaan.

---

## 3. Fitur Inti Aplikasi

### 3.1 Dashboard Utama
Menampilkan ringkasan lintas unit:
- total pekerjaan aktif,
- pekerjaan selesai bulan ini,
- pekerjaan overdue,
- rata-rata waktu respon,
- rata-rata waktu penyelesaian,
- tingkat ketercapaian target per unit,
- grafik permintaan layanan bulanan,
- distribusi pekerjaan per kategori,
- top 10 isu berulang,
- notifikasi prioritas tinggi.

### 3.2 Master Proses Bisnis
Kamus proses yang menjadi referensi seluruh tiket/proyek:
- unit,
- subproses level 3,
- aktivitas level 4,
- PIC utama/pendukung,
- SLA,
- indikator capaian,
- SOP,
- template checklist.

### 3.3 Manajemen Tiket / Work Order
Seluruh permintaan masuk via sistem.

Field inti:
- nomor tiket,
- tanggal masuk,
- unit tujuan,
- kategori & subkategori,
- pemohon,
- lokasi,
- deskripsi masalah/kebutuhan,
- prioritas,
- PIC,
- target selesai,
- status,
- bukti file/foto,
- catatan tindak lanjut.

Status tiket:
- diajukan,
- diverifikasi,
- direncanakan,
- dikerjakan,
- menunggu vendor/approval,
- selesai,
- ditutup,
- direvisi.

### 3.4 Monitoring KPI dan SLA
KPI per unit dan SLA per tahapan:
- respon awal,
- verifikasi,
- pelaksanaan,
- penyelesaian,
- approval.

### 3.5 Task Breakdown & Checklist
Setiap proses besar dipecah menjadi tahapan kecil agar tidak ada lompatan kerja dan progres dapat diukur per tahap.

### 3.6 Preventive Maintenance Scheduler
Mendukung pekerjaan berkala (AC, listrik, jaringan, server, komputer lab, proyektor, bangunan, toilet, pompa air, CCTV):
- jadwal rutin,
- reminder otomatis,
- checklist,
- bukti foto,
- histori,
- status layak/tindak lanjut.

### 3.7 Asset Management
Data aset terstandar:
- kode, nama, kategori,
- lokasi, kondisi,
- tanggal perolehan,
- sumber dana, nilai aset,
- penanggung jawab,
- jadwal maintenance,
- histori perbaikan,
- status aktif/nonaktif/dihapus.

### 3.8 Room & Facility Management
Monitoring ruang/fasilitas:
- daftar ruang,
- kapasitas,
- fungsi,
- status kelayakan,
- jadwal penggunaan,
- histori gangguan,
- kebutuhan renovasi,
- skor kebersihan/kelayakan.

### 3.9 Project Monitoring
Untuk pekerjaan non-harian yang bersifat proyek.

Field inti:
- nama proyek,
- tujuan,
- output,
- timeline,
- anggaran,
- progres %,
- risiko,
- PIC,
- milestone,
- kendala,
- dokumen.

### 3.10 Knowledge Base / SOP Center
Pusat referensi kerja dan template operasional lintas unit.

### 3.11 Laporan dan Evaluasi
Laporan otomatis:
- bulanan per unit,
- rekap kategori,
- overdue,
- performa PIC,
- aset rusak,
- utilisasi ruang/lab,
- preventive maintenance,
- progres proyek,
- insiden keamanan/PDP.

Output:
- PDF,
- Excel,
- ringkasan presentasi.

### 3.12 Notifikasi dan Eskalasi
Notifikasi untuk tiket baru, deadline, overdue, approval tertunda, maintenance, aset kritis, dan gangguan prioritas tinggi.

Eskalasi:
- lewat SLA → naik ke koordinator,
- vendor terlambat → hambatan eksternal,
- isu berulang → problem sistemik.

---

## 4. Pegangan Kerja per Unit

## 4.1 IT
Menu kerja:
- Helpdesk IT,
- infrastruktur jaringan,
- apps & database,
- support,
- security & PDP,
- inventaris perangkat,
- maintenance server/network,
- monitoring gangguan.

Indikator harian:
- tiket baru/selesai/kritis,
- uptime jaringan,
- perangkat bermasalah,
- backup terakhir,
- insiden keamanan.

## 4.2 Laboratorium
Menu kerja:
- kesiapan lab,
- praktikum & perangkat,
- jadwal penggunaan,
- kerusakan alat,
- digitalisasi pembelajaran,
- produksi konten,
- riset inovasi,
- HKI tracker.

Indikator harian:
- lab siap pakai,
- perangkat bermasalah,
- jadwal bentrok,
- konten diproduksi,
- ide inovasi masuk,
- progres inkubasi,
- capaian HKI.

## 4.3 Sarpras
Menu kerja:
- gedung & bangunan,
- ruang & fasilitas,
- pengadaan,
- inventaris aset,
- maintenance,
- laporan kerusakan,
- utilitas,
- vendor monitoring.

Indikator harian:
- kerusakan baru,
- perbaikan aktif,
- ruang tidak layak,
- maintenance hari ini,
- aset rusak,
- progres pengadaan,
- kondisi utilitas.

---

## 5. Standarisasi Progres
Mapping progress lintas unit:
- 0% = diajukan,
- 20% = diverifikasi,
- 40% = direncanakan,
- 60% = dikerjakan,
- 80% = uji hasil / menunggu validasi,
- 100% = selesai.

Status ringkas tambahan:
- pending,
- on track,
- at risk,
- overdue,
- completed.

---

## 6. Formula Ketercapaian Dashboard
- **Ketercapaian unit** = (pekerjaan selesai tepat waktu / total pekerjaan jatuh tempo) x 100%
- **Ketercapaian proses** = (tahap checklist selesai / total tahap) x 100%
- **Ketercapaian program** = (milestone tercapai / total milestone) x 100%
- **Ketercapaian aset** = (aset kondisi baik / total aset) x 100%
- **Ketercapaian layanan** = (permintaan tuntas / total permintaan masuk) x 100%

---

## 7. Persona Dashboard

### 7.1 Dashboard Pimpinan
Fokus pada performa unit, capaian KPI, isu kritis, overdue, progres proyek besar, anggaran ringkas, dan kondisi aset/gedung.

### 7.2 Dashboard Koordinator
Fokus pada beban kerja PIC, SLA, approval tertunda, tindak lanjut vendor, isu berulang, dan rencana mingguan.

### 7.3 Dashboard Staf Pelaksana
Fokus pada tugas hari ini, checklist, deadline, bukti kerja, riwayat tugas, dan notifikasi tindak lanjut.

---

## 8. Hak Akses Pengguna
Role minimum:
- Admin Sistem,
- Pimpinan,
- Koordinator Unit,
- Staf IT,
- Staf Lab,
- Staf Sarpras,
- Pelapor/Guru,
- Viewer/Auditor.

Contoh kontrol akses:
- guru/pelapor: membuat tiket dan melihat tiket milik sendiri,
- staf: melaksanakan pekerjaan dan update progres,
- koordinator: verifikasi, distribusi tugas, penilaian capaian,
- pimpinan: pemantauan dashboard strategis lintas unit.

---

## 9. Struktur Menu Aplikasi (Usulan)
1. Dashboard
2. Permintaan Layanan
3. Proses Bisnis
4. KPI & SLA
5. Jadwal Maintenance
6. Aset & Inventaris
7. Gedung & Ruang
8. Laboratorium
9. IT Services
10. Proyek & Pengembangan
11. SOP & Dokumen
12. Laporan
13. Pengaturan Pengguna

---

## 10. Backlog Prioritas Implementasi (MVP → Lanjutan)

### Tahap 1 (MVP)
- autentikasi & role dasar,
- manajemen tiket/work order,
- master proses bisnis,
- dashboard ringkas (aktif, selesai, overdue, SLA dasar),
- notifikasi deadline,
- laporan bulanan sederhana.

### Tahap 2
- KPI & SLA mendalam per unit,
- task breakdown checklist,
- preventive maintenance scheduler,
- asset management inti.

### Tahap 3
- room & facility management,
- project monitoring,
- knowledge base & SOP center,
- eskalasi otomatis berbasis aturan.

### Tahap 4
- analitik isu berulang,
- prediksi risiko overdue,
- insight untuk optimalisasi beban kerja lintas unit.
