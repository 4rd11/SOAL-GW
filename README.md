<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio - SMK Telkom Jakarta</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome untuk social media icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="# ">My Portfolio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About Me</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#education">Education</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#findme">Find Me</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Me Section -->
    <section id="about" class="py-5 mt-5">
        <div class="container">
            <div class="row">
                <div class="col-md-4 text-center">
                    <img src="FotoProfile.jpeg" alt="Profile Photo" class="img-fluid rounded-circle mb-3" style="width: 200px; height: 200px; object-fit: cover;">
                </div>
                <div class="col-md-8">
                    <h1>Ardi Dzarghifari</h1>
                    <h3>XI XI 12</h3>
                    <div class="ratio ratio-16x9 mt-4">
                        <video controls src = "ResepNasiGoreng.mp4">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">Education & Experience</h2>
            
            <!-- Organizational Experience -->
            <h3>Organizational Experience</h3>
            <div class="table-responsive mb-5">
                <table class="table table-striped">
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
                        <!-- Add more rows as needed -->
                    </tbody>
                </table>
            </div>

            <!-- Educational Background -->
            <h3>Educational Background</h3>
            <div class="table-responsive">
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
                            <td>2022-Present</td>
                            <td>Jurusan Rekayasa Perangkat Lunak</td>
                        </tr>
                        <!-- Add more rows as needed -->
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
                Email: your.email@example.com<br>
                Phone: +62 123 4567 890
            </p>
            <div class="social-icons">
                <a href="https://instagram.com/youraccount" target="_blank" class="mx-2">
                    <i class="fab fa-instagram fa-2x"></i>
                </a>
                <a href="https://facebook.com/youraccount" target="_blank" class="mx-2">
                    <i class="fab fa-facebook fa-2x"></i>
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
                <div class="col-md-6">
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label">Nama</label>
                            <input type="text" class="form-control" id="name" required>
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" required>
                        </div>
                        <div class="mb-3">
                            <label for="message" class="form-label">Pesan</label>
                            <textarea class="form-control" id="message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p class="mb-0">&copy; 2024 My Portfolio. All rights reserved.</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
