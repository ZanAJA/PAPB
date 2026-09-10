## Penjelasan Singkat Kode

Aplikasi dibuat menggunakan Jetpack Compose untuk menampilkan halaman profil.

Fungsi Profile() menggunakan Column untuk menyusun foto profil, nama, NIM, deskripsi, dan tombol secara vertikal. Semua komponen diletakkan di tengah layar menggunakan Alignment.CenterHorizontally dan Arrangement.Center.

Foto profil diambil dari folder drawable menggunakan painterResource. Modifier digunakan untuk mengatur ukuran foto, membuat foto berbentuk lingkaran, memberikan warna latar abu-abu, dan membuat padding antar komponen.

Fungsi FollowButton() membuat tombol interaktif. Status tombol disimpan menggunakan remember { mutableStateOf(false) }. Saat tombol ditekan tulisan **Follow** berubah menjadi **Unfollow**, Jika ditekan kembali tulisan berubah menjadi **Follow**.

## Keuntungan Compose Dibandingkan XML Layout

Pada XML tradisional tampilan dibuat di file XML, sedangkan fungsi aplikasi dibuat di file Kotlin atau Java. Kedua bagian tersebut kemudian harus dihubungkan.

Pada Jetpack Compose tampilan dan fungsi aplikasi dapat dibuat langsung menggunakan Kotlin. Ketika data atau state berubah, tampilan akan diperbarui secara otomatis.

Keuntungan lain dari Compose:
- Kode lebih singkat dan mudah dibaca.
- Tampilan dan fungsi dapat ditulis dalam satu tempat.
- Komponen mudah dibuat dan digunakan kembali.
