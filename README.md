<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio - SMK Telkom Jakarta</title>
    <!-- Bootstrap CSS untuk styling -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome untuk ikon media sosial -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css">
</head>
<body>
  
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand navbar-dark bg-dark fixed-top"> 
        <!-- .navbar: Elemen navigasi, .navbar-expand-lg: membuat navbar responsif di layar besar, 
        .navbar-dark: navbar dengan teks terang di atas latar gelap, bg-dark: background warna gelap, 
        .fixed-top: membuat navbar tetap berada di atas saat di-scroll -->
        <div class="container">
            <!-- .container: Membuat konten berada di tengah dan diberi margin di kiri-kanan -->
            <a class="navbar-brand" >My Portfolio</a>
             <!-- .navbar-brand: Untuk nama/logo website -->
            <div>
                <ul class="navbar-nav ">
                    <!-- .navbar-nav: Daftar menu navigasi, -->                   
                    <li><a class="nav-link" href="#about">About Me</a></li>
                    <!-- .nav-link: Gaya untuk link -->
                    <li ><a class="nav-link" href="#education">Education</a></li>
                    <li ><a class="nav-link" href="#findme">Find Me</a></li>
                    <li ><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Me -->
    <section id="about" class="py-5 mt-5">
        <!-- py-5: Padding vertikal (top dan bottom) sebesar 3rem, mt-5: Margin top sebesar 3rem -->
        <div class="container">
            <div class="row">

                <div class="col-3 text-center">
                    <!-- .col-3: Kolom sebesar 4 grid untuk medium screen, 
                    .text-center: Teks rata tengah -->
                    <img src="FotoProfile.jpeg" alt="Profile Photo" class="rounded-circle " style="width: 200px; height: 200px; object-fit: cover;">
                    <!-- .rounded-circle: Gambar berbentuk lingkaran, -->
                </div>
                <div class="col-8">
                    <!-- .col-8: Kolom sebesar 8 grid -->
                    <h1>Ardi Dzarghifari</h1>
                    <h3>XI Tel 12</h3>
                    <div class="ratio ratio-16x9 mt-4">
                        <!-- .ratio: Membuat kontainer dengan aspek rasio tertentu, 
                        .ratio-16x9: Rasio aspek 16:9 -->
                        <video controls src="ResepNasiGoreng.mp4"></video>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="py-5 bg-light">
        <!-- bg-light: Background warna terang -->
        <div class="container">
            <h2 class="text-center mb-4">Education & Experience</h2>
            <!-- .text-center: Teks rata tengah, .mb-4: Margin bawah sebesar 1.5rem -->

            <h3>Organizational Experience</h3>
            <div class="mb-5">
                <!-- mb-5: Margin bawah sebesar 3rem -->
                <table class="table table-striped">
                    <!-- .table: Gaya tabel Bootstrap, .table-striped: Baris bergaris -->
                    <thead>
                        <tr>
                            <th>Tahun</th>
                            <th>Peran/Posisi</th>
                            <th>Deskripsi</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>2023-2024</td>
                            <td>Ketua OSIS</td>
                            <td>Memimpin organisasi siswa intra sekolah</td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <h3>Educational Background</h3>
            <div class="mb-5">
                <table class="table table-striped">
                    <thead>
                        <tr>
                            <th>Sekolah</th>
                            <th>Tahun</th>
                            <th>Deskripsi</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>SMK Telkom Jakarta</td>
                            <td>2023-2025</td>
                            <td>Jurusan Rekayasa Perangkat Lunak</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </section>

    <!-- Find Me Section -->
    <section id="findme" class="py-5">
        <div class="container text-center">
            <h2 class="mb-4">Find Me</h2>
            <p class="mb-4">
                Email: ardidzarghifari@gmail.com<br>
                Phone: +62 8569 7700 019
            </p>
            <div class="social-icons">
                <!-- Ikon media sosial menggunakan Font Awesome -->
                <a href="https://instagram.com/youraccount" target="_blank" class="mx-2 ">
                    <!-- .mx-2: Margin horizontal sebesar 0.5rem -->
                    <h1 class="fab fa-instagram fa-2x"></h1>  
                    <!-- .fa-2x: Ukuran ikon dua kali lipat dari ukuran dasar -->
                </a>
                <a href="https://facebook.com/youraccount" target="_blank" class="mx-2">
                    <h1 class="fab fa-facebook fa-2x"></h1>
                </a>
                <a href="https://tiktok.com/@youraccount" target="_blank" class="mx-2">
                    <i class="fab fa-tiktok fa-2x"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Contact Form -->
    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">Contact Me</h2>
            <div class="row justify-content-center">
                <!-- .row: Membagi area menjadi baris, 
                .justify-content-center: Memusatkan kolom -->
                <div class="col-md-6">
                    <!-- .col-md-6: Kolom dengan lebar 6 grid -->
                    <form>
                        <div class="mb-3">
                            <label class="form-label">Nama</label>
                            <!-- .form-label: Gaya label untuk form -->
                            <input type="text" class="form-control" id="name" required>
                            <!-- .form-control: Gaya input teks -->
                        </div>
                        <div class="mb-3">
                            <label class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" required>
                        </div>
                        <div class="mb-3">
                            <label class="form-label">Pesan</label>
                            <textarea class="form-control" id="message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                        <!-- .btn: Tombol Bootstrap, .btn-primary: Warna biru -->
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-white bg-dark text-center py-3">
        <!-- .text-white: Teks putih, .py-3: Padding vertikal sebesar 1rem -->
        <p class="mb-0">&copy; 2024 My Portfolio. Seluruh hak cipta.</p>
        <!-- .mb-0: Margin bawah nol -->
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
