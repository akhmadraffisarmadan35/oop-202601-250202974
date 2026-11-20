# Catatan Minggu 03: (inheritance)

Salin berkas ini menjadi `catatan/minggu-NN.md` (NN dua digit, misalnya `minggu-07.md`).

## Yang saya kerjakan
Saya membuat tiga class turunan, yaitu Ruang, Laptop, dan AlatLab yang mewarisi class Aset. Setiap class memiliki atribut, konstruktor, getter, dan method getJenis() sesuai jenis asetnya. Saya menggunakan super pada konstruktor untuk memanggil konstruktor dari class induk. Saya juga menambahkan validasi agar data yang dimasukkan sesuai dengan aturan yang telah ditentukan

## Keputusan desain
Saya menggunakan konsep inheritance agar class Ruang, Laptop, dan AlatLab dapat mewarisi atribut serta validasi dari class induk Aset. Setiap subclass memiliki atribut tambahan sesuai karakteristik masing-masing aset. Saya menggunakan super agar konstruktor induk tetap dijalankan dan validasi dari Aset tidak hilang. Dengan desain ini, kode menjadi lebih terstruktur dan mengurangi pengulangan kode.

## Kendala
Kendala yang saya alami adalah memahami cara menggunakan super pada konstruktor subclass dan memastikan validasi dari class induk tetap berjalan. Saya mengatasinya dengan mempelajari kembali konsep inheritance dan memastikan setiap konstruktor memanggil super sebelum melakukan validasi atribut tambahan

## Penggunaan AI
- Alat yang dipakai: (chatgpt")
- Bagian yang dibantu AI: (Memahami konsep inheritance, penggunaan super, konstruktor, getter, dan validasi pada class Ruang, Laptop, dan AlatLab)
- Prompt utama: (Jelaskan cara kerja inheritance pada Java, Bagaimana cara menggunakan super pada konstruktor subclass, Bagaimana memastikan validasi dari class induk tetap berlaku pada subclass)
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Saya menyesuaikan saran AI dengan ketentuan tugas dan struktur kode yang sudah diberikan agar tidak bertentangan dengan aturan program
- Satu hal yang saya pahami lebih baik sekarang: Saya lebih memahami bahwa inheritance memungkinkan class turunan menggunakan atribut dan method dari class induk tanpa harus menulis ulang kode yang sama
