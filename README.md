# Aplikasi Absen

Aplikasi absensi sederhana berbasis web, satu file (`index.html`), tanpa server.

## Fitur
- **Absen hari ini**: tombol Masuk / Pulang dengan jam otomatis; status Telat jika lewat batas jam masuk.
- **Izin / Sakit / Alpa** dengan keterangan, serta reset absen per orang.
- **Anggota**: tambah/hapus anggota (ID, nama, kelas/divisi).
- **Periode gaji 26–25**: setiap periode berjalan dari tanggal 26 sampai tanggal 25 bulan berikutnya
  (dinamai sesuai bulan tanggal 25-nya, mis. 26 Nov–25 Des = periode Desember).
- **Lembur otomatis**: lembur = jam pulang aktual − jam pulang normal (default 17:00). Saldo lembur
  per orang dijumlahkan per periode dan otomatis mulai dari 0 lagi setiap tanggal 26.
- **Rekap**: rekap per periode 26–25 (atau rentang manual) dan per kelas/divisi, persentase kehadiran, total lembur, unduh CSV (bisa dibuka di Excel).
- **Riwayat harian** untuk tanggal mana saja.
- **Pengaturan**: batas jam masuk, jam pulang normal, backup & pulihkan data (JSON), hapus semua data.

## Cara pakai
Buka `index.html` di browser. Data tersimpan di browser perangkat itu (localStorage),
jadi lakukan backup secara berkala lewat tab **Pengaturan**.
