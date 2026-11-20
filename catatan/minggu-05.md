# Catatan Minggu 05: (abstraction)

Salin berkas ini menjadi `catatan/minggu-NN.md` (NN dua digit, misalnya `minggu-07.md`).

## Yang saya kerjakan
mengubah kelas Aset menjadi kelas abstrak serta menambahkan metode abstrak hitungDenda dan metode bisaDipinjam. Selain itu, saya juga mengimplementasikan interface AturanDenda pada kelas DendaFlat dan DendaProgresif.

## Keputusan desain
memakai tipe data long pada perhitungan denda. Untuk DendaProgresif, saya buat makin mahal secara bertahap (bervariasi) seiring bertambahnya hari keterlambatan.

## Kendala
Penyesuaian aturan denda progresif agar memenuhi semua kondisi tes. cara mengatasi Masalah ini diatasi dengan me-return tipe long secara konsisten di seluruh subclass dan membuat struktur pengali berjenjang yang monotonik naik.

## Penggunaan AI
- Alat yang dipakai: chatgpt
- Bagian yang dibantu AI: menjelaskan abstraction dan penerapan kode pada DendaFlat dan DendaProgresif.
- Prompt utama: bagaimana kalu denda progresif dibuat bertahap tapi masih memenuhi syarat test minimum yang ditentukan
- Yang saya ubah atau tolak dari saran AI, dan alasannya: -
- Satu hal yang saya pahami lebih baik sekarang:  Kelas abstrak digunakan umtuk fondasi umum yang tidak bisa di-instansiasi langsung, sedangkan interface AturanDenda memberikan fleksibilitas untuk menerapkan berbagai strategi perhitungan denda tanpa mengubah struktur kelas aset utama.
