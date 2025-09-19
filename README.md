Jadi gini, struktur web yang dibikin ini ada beberapa bagian penting. Di bagian paling atas ada head, nah di situ dipanggil alat tempur kayak Bootstrap, Tailwind, sama Bootstrap Icons.
Nah, Bootstrap itu di ibaratkan seperti toolkit serba ada, fungsinya bootstrap ini hanya tinggal memanggil class kayak btn atau container, udah langsung jadi tombol atau layout yang rapi.
Kalau Tailwind beda lagi, tailwind ini seperti lego, bisa diatur detailnya sendiri misalnya warna background, jarak antar elemen, ukuran font semua bisa diatur pake class pendek.
Jadi kalau Bootstrap itu barang yang sudah jadi sedangkan tailwind lebih ke bahan mentahan yang bisa dirakit sesuai selera. Terus ada Bootstrap mempunyai icons buat nambahin ikon ikon biar tampilannya mirip
aplikasi seperti yang ada di sosmed.

Masuk ke body, tampilannya dibikin dark mode gitu, background hitam sama teks putih. Trus ada container utama, fungsinya biar isi web nggak terlalu mepet pinggir layar,
ini bantuan dari Bootstrap juga. Bagian headernya ada pada foto profil, nama akun, tombol edit profil sama arsip, terus ada bio singkat. Foto profil dibuletin pake class Tailwind,
sedangkan ukuran fix nya diatur manual lewat CSS custom.

Bagian berikutnya ada stats jumlah postingan, followers, sama following. Layout-nya dibuat pake sistem flexbox dari Tailwind, jadi tiap kotak sejajar dan ada jaraknya.
Tombol tombolnya masih menggunakan Bootstrap biar gampang dan tampilannya udah rapi tanpa ribet bikin style baru.

Di bawahnya ada navigasi, ada ikon grid yang diambil dari Bootstrap Icons. Supaya lebih kece, ukurannya dibesarin pake class dari Tailwind.

Terakhir, ada grid postingan. Nah, bagian ini pake grid system dari Tailwind: dibikin 3 kolom, tiap kotak bentuknya persegi.
Gambarnya otomatis pas dan tidak acak acakan saat layar diperlebar/diperkecil karena diatur object-fit.
Terus ada efek hover yang bikin gambar agak transparan pas kursor menyentuh gambar yang membuat feel interaktif seperti Instagram beneran.

Kesimpulannya, kdoe ini adalah hasil gabungan antara Bootstrap sama Tailwind. Bootstrap dipake buat elemen-elemen yang udah jadi (tombol, container, ikon),
sedangkan Tailwind dipake buat kontrol detail styling (warna, jarak, ukuran, hover, dsb). Analogi gampangnya: Bootstrap = beli meja kursi langsung jadi di IKEA, Tailwind = beli kayu, cat, paku,
terus juga bisa bikin meja kursi sesuai desain sendiri. Kombinasi dua duanya bikin web ini jadi rapi, fleksibel, tapi tetap gampang diatur.
