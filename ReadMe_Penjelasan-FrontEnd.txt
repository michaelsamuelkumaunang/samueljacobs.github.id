Catatan Front-End Website BeHealthy

*catatan:
- Sebagian caption/tulisan masih perlu diubah dan ada yang masih berbentuk text lorem
- Sebagian gambar dan video akan diubah sesuai kontennya ketika sudah dispesifikasi
- Logo akan diperbaiki
- Semua halaman sudah responsif
- untuk styling css dibuat langsung dalam html nya

Halaman yang sudah di buat
-- Home (index)
-- Exercises
-- Exercise Detail (akan bertambah sesuai banyaknya latihan)
-- Trainers
-- Trainer Detail (akan bertambah sesuai banyaknya trainer)
-- about
-- login & register
-- user profile
-- ROOM (chatroom)
-- Membership

<=== Header(navbar) & Footer ===>
- Section yang selalu ada di setiap page
- navbar menggunakan kelas bootstrap dengan logo di sebelah kiri, navigasi di tengah dan button link untuk room dan sign-in di sebelah kanan
- footer memiliki kolom Our Company untuk link ke about us, kolom useful links untuk link-link ke halaman lain, kolom sosial media dan kolom logo di paling kanan

<=== Home ===>
----- Carousel Hero -----
- Section pertama ketika website dibuka
- punya 3 sliders yang berisi background image dan caption
problem : penambahan link <a> tidak bisa berfungsi di dalam container carouselnya

----- Features -----
- Section yang menunjukkan keuntungan ketika menggunakan website BeHealthy
- Ada call to action button di bagian terakhir dari section Features yang mengarahkan user ke halaman membership

----- Exercises and Trainers Overview -----
- Section ini diberi dua carousel, yang pertama dengan slide beberapa gambar latihan dan yang kedua dengan slide beberapa gambar trainer
- Call to action button di samping masing-masing slide untuk ke halaman masing-masing


<=== Exercises ===>
----- Intro -----
- section pertama di halaman exercises
- memiliki background image fixed dan caption

----- Main -----
- section yang memberikan daftar latihan yang bisa dipilih user
- nama latihan, deskripsi dan gambar akan diganti sesuai dengan latihan spesifik
- button link di bawah deskripsi latihan untuk ke halaman detail latihan tersebut


<=== Exercise Detail ===>
- nama latihan di sebelah kanan
- video intro latihan (hanya introduksi saja bukan full latihannya)
- deskripsi latihan
- button untuk membuka modal pilihan trainer jika user berminat pada exercise ini
- dalam modal trainer ada list pilihan trainer dengan gambar, nama, dan link button. Know more untuk ke halaman detail trainer yang bersangkutan dan Choose untuk ke halaman Room untuk mulai latihan dengan trainer yang sudah dipilih


<=== Trainers ===>
----- Intro -----
- section pertama di halaman trainers
- memiliki background image fixed dan caption

----- Main -----
- section yang memberikan daftar trainer yang bisa dipilih user
- nama trainer, deskripsi dan gambar akan diganti sesuai dengan trainer spesifik
- button link di bawah deskripsi latihan untuk ke halaman detail trainer tersebut


<=== Trainer Detail ===>
- nama trainer di sebelah kanan
- video intro trainer (hanya introduksi saja)
- deskripsi trainer
- button untuk membuka modal pilihan latihan jika user ingin dilatih trainer ini
- dalam modal exercise ada list pilihan exercise dengan gambar, nama, dan link button. Know more untuk ke halaman detail exercise yang bersangkutan dan Choose untuk ke halaman Room untuk mulai latihan dengan exercise yang sudah dipilih


<=== About Us ===>
- halaman yang memberi deskripsi tentang apa itu BeHealthy
- terdapat form jika user ingin memberi pesan pada admin


<=== Log-in & Register ===>
- diakses ketika user klik button sign-in di sebelah kanan navbar
- page sign-in user memasukan email dan password untuk masuk
- jika belum punya akun klik link 'Don't have an account yet?' di bawah tombol Log-In
- halaman register memiliki form yang meminta data user untuk dimasukan untuk bisa daftar


<=== User Profile ===>
- untuk sementara halaman user profile diakses melalui footer dalam kolom 'Useful Links' dengan link 'Your Profile'. Link akan mengarahkan ke halaman sign-in jika user belum melakukan sign-in
- dalam halaman user profile terdapat dua kontainer utama, yang pertama menunjukkan detail profil user beserta foto profil dan yang kedua menunjukan detail membership


<=== ROOM ===>
- Room adalah fitur chat-room untuk memudahkan interaksi antara user dengan trainer
- Room hanya bisa diakses oleh member saja
- Ketika user sudah memilih jenis latihan dan pelatih, akan dinavigasikan ke halaman room dimana pelatih/trainer akan memberikan video detail latihan dan mengarahkan user untuk bisa mengikuti latihan tersebut

----- Room Main -----
- Di bagian utama halaman Room terdapat container yang berisi foto dan nama trainer di sebelah kiri dan dropdown di sebelah kanan untuk mengganti trainer jika user memiliki latihan dengan trainer lain
- Terdapat container yang berisi chat user dengan trainer dan form dimana user memasukan message yang ingin dikirimkan


<=== Membership ===>
- untuk sementara halaman membership hanya bisa diakses dari halaman home dalam section features
- halaman membership berisi benefit yang didapatkan seorang member (akan diperjelas) dan 3 pilihan pricing card di bawahnya