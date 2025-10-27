Nama   : Navyta Budi Yulia

NIM    : 312410184

Kelas  : TI.24.A2

# Lab6Web

<img width="1920" height="1008" alt="Image" src="https://github.com/user-attachments/assets/bc5e1554-6680-48ce-aca9-1c831d9a156f" />


<img width="1920" height="1008" alt="Image" src="https://github.com/user-attachments/assets/fca8bbfb-59cd-4f03-893d-fc9d9febeb03" />


<img width="1920" height="1008" alt="Image" src="https://github.com/user-attachments/assets/e33c06e5-659e-40fc-90c3-5b6e6169cc8c" />


<img width="1920" height="1008" alt="Image" src="https://github.com/user-attachments/assets/c013b7d0-898e-4a96-bece-4336f5da877e" />

#Penjelasan

1. Membuat Struktur Dasar HTML

Buka file index.html, lalu tuliskan struktur dasar HTML berikut:

'''<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Praktikum 6 - Web Framework</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-center mt-5">Praktikum 6 - Web Framework (Bootstrap)</h1>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>'''



2. Membuat Layout Sederhana

Tambahkan struktur layout menggunakan Grid System Bootstrap (Header, Navbar, Konten, Sidebar, dan Footer).

📄 Navbar:

<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <div class="container">
    <a class="navbar-brand" href="index.html">MyWebsite</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="index.html">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="services.html">Services</a></li>
        <li class="nav-item"><a class="nav-link" href="portfolio.html">Portfolio</a></li>
        <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>



3. Membuat Section “Tentang Kami”

Tambahkan bagian “Tentang Kami” pada halaman utama dengan background gradasi:

<section class="py-5 text-center" 
  style="background: linear-gradient(135deg, #89f7fe, #66a6ff);">
  <div class="container">
    <h2 class="mb-4">Tentang Kami</h2>
    <p class="lead mb-4">Kami adalah tim profesional di bidang teknologi informasi yang berfokus pada inovasi digital.</p>
    <a href="contact.html" class="btn btn-primary">Hubungi Kami</a>
  </div>
</section>



4. Menambahkan Sidebar dan Widget

Gunakan Card Component Bootstrap untuk membuat sidebar seperti berikut:

<div class="card mb-3">
  <div class="card-header bg-primary text-white">Widget Header</div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item"><a href="#">Widget Link</a></li>
    <li class="list-group-item"><a href="#">Widget Link</a></li>
    <li class="list-group-item"><a href="#">Widget Link</a></li>
  </ul>
</div>



5. Membuat Halaman Lain

Buat halaman tambahan dan hubungkan melalui navbar:

Halaman	File	Deskripsi
Home	index.html	Halaman utama
Services	services.html	Menampilkan daftar layanan
Portfolio	portfolio.html	Menampilkan galeri proyek
Contact	contact.html	Formulir kontak


6. Halaman Portfolio

Tambahkan gambar dan efek hover:

<div class="portfolio-item">
  <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?w=400&h=300&fit=crop" class="img-fluid rounded shadow-sm">
</div>


7. Halaman Contact

Gunakan Form Bootstrap:

<form>
  <div class="mb-3">
    <label class="form-label">Nama</label>
    <input type="text" class="form-control" placeholder="Masukkan nama Anda">
  </div>
  <div class="mb-3">
    <label class="form-label">Email</label>
    <input type="email" class="form-control" placeholder="Masukkan email Anda">
  </div>
  <div class="mb-3">
    <label class="form-label">Pesan</label>
    <textarea class="form-control" rows="4" placeholder="Tulis pesan Anda"></textarea>
  </div>
  <button class="btn btn-primary w-100">Kirim Pesan</button>
</form>


8. Footer

Tambahkan footer ke setiap halaman:

<footer class="text-center bg-dark text-white py-3 mt-4">
  <p>© 2025 - MyWebsite</p>
</footer>

