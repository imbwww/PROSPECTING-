# Aplikasi Absen

Aplikasi absensi sederhana berbasis web, satu file (`index.html`), tanpa server.

## Fitur
- **Absen hari ini**: tombol Masuk / Pulang dengan jam otomatis; status Telat jika lewat batas jam masuk.
- **Izin / Sakit / Alpa** dengan keterangan, serta reset absen per orang.
- **Anggota**: tambah/hapus anggota (ID, nama, kelas/divisi).
- **Rekap**: rekap per rentang tanggal dan per kelas/divisi, persentase kehadiran, unduh CSV (bisa dibuka di Excel).
- **Riwayat harian** untuk tanggal mana saja.
- **Pengaturan**: batas jam masuk, backup & pulihkan data (JSON), hapus semua data.

## Cara pakai
Buka `index.html` di browser. Data tersimpan di browser perangkat itu (localStorage),
jadi lakukan backup secara berkala lewat tab **Pengaturan**.
