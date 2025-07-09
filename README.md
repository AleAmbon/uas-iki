<html lang="id">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   PinjamKuy - Laporan Analisis Kebutuhan Sistem
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: "Inter", sans-serif;
    }
  </style>
 </head>
 <body class="bg-gradient-to-b from-blue-100 to-white text-gray-800 leading-relaxed min-h-screen flex flex-col">
  <header class="bg-blue-800 text-white py-8 shadow-lg">
   <div class="max-w-6xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-4">
    <div class="flex items-center gap-3">
     <img alt="Logo PinjamKuy berupa ikon tangan saling meminjamkan barang berwarna biru dan putih" class="w-14 h-14 rounded-full shadow-md" height="60" src="IKI.jpeg" width="60"/> 
     <div>
      <h1 class="text-4xl font-extrabold tracking-wide">
       PinjamKuy
      </h1>
      <p class="text-sm font-light italic max-w-xs">
       Aplikasi Peminjaman Barang Antar Mahasiswa Berbasis Android
      </p>
     </div>
    </div>
    <nav class="space-x-6 hidden md:block font-semibold text-blue-200">
     <a class="hover:text-white transition" href="#ide">
      Ide Proyek
     </a>
     <a class="hover:text-white transition" href="#tujuan">
      Tujuan
     </a>
     <a class="hover:text-white transition" href="#masalah">
      Masalah
     </a>
     <a class="hover:text-white transition" href="#pengguna">
      Pengguna
     </a>
     <a class="hover:text-white transition" href="#kebutuhan">
      Kebutuhan
     </a>
     <a class="hover:text-white transition" href="#sdlc">
      Model SDLC
     </a>
     <a class="hover:text-white transition" href="#diagram">
      Diagram
     </a>
     <a class="hover:text-white transition" href="#wireframe">
      Wireframe
     </a>
    </nav>
   </div>
  </header>
  <main class="flex-grow max-w-6xl mx-auto px-6 py-10 space-y-16">
   <!-- Ide Proyek -->
   <section class="bg-white rounded-xl shadow-lg p-8" id="ide">
    <h2 class="text-3xl font-bold text-blue-800 mb-6 border-b-4 border-blue-600 pb-2">
     1. Ide Proyek
    </h2>
    <p class="text-lg text-justify leading-relaxed">
     PinjamKuy adalah aplikasi mobile inovatif berbasis Android yang
        dirancang untuk memudahkan mahasiswa dalam meminjam dan meminjamkan
        barang secara efisien di lingkungan kampus. Dengan PinjamKuy,
        mahasiswa dapat menemukan barang kebutuhan mendadak seperti charger,
        jas lab, alat tulis, kalkulator, atau buku dengan cepat dan aman,
        menghilangkan kerepotan bertanya secara manual dan memperkuat solidaritas
        antar civitas akademika.
    </p>
    <div class="mt-6 flex justify-center">
     <img alt="Ilustrasi mahasiswa saling meminjamkan barang seperti charger dan buku di lingkungan kampus dengan latar belakang gedung universitas dan suasana cerah" class="rounded-lg shadow-lg w-full max-w-3xl object-cover" height="300" src="IKI.jpeg" width="600"/>
    </div>
   </section>
   <!-- Tujuan -->
   <section class="bg-white rounded-xl shadow-lg p-8" id="tujuan">
    <h2 class="text-3xl font-bold text-blue-800 mb-6 border-b-4 border-blue-600 pb-2">
     2. Tujuan
    </h2>
    <ul class="list-disc list-inside space-y-3 text-lg text-justify">
     <li>
      <strong>
       Menyediakan Solusi Peminjaman Praktis dan Efisien:
      </strong>
      Memfasilitasi proses peminjaman barang antar mahasiswa secara
          digital yang mudah dan cepat.
     </li>
     <li>
      <strong>
       Mengurangi Waktu dan Usaha Pencarian Barang:
      </strong>
      Menyediakan katalog terpusat yang dapat diakses kapan saja tanpa
          perlu bertanya manual.
     </li>
     <li>
      <strong>
       Membangun Sistem Pencatatan yang Terstruktur:
      </strong>
      Mendokumentasikan setiap transaksi peminjaman untuk menghindari
          kehilangan dan kesalahpahaman.
     </li>
     <li>
      <strong>
       Meningkatkan Solidaritas dan Kerja Sama:
      </strong>
      Memperkuat ikatan sosial antar mahasiswa melalui kegiatan berbagi
          barang yang transparan dan terpercaya.
     </li>
    </ul>
   </section>
   <!-- Masalah -->
   <section class="bg-white rounded-xl shadow-lg p-8" id="masalah">
    <h2 class="text-3xl font-bold text-blue-800 mb-6 border-b-4 border-blue-600 pb-2">
     3. Masalah yang Ingin Diselesaikan
    </h2>
    <ul class="list-disc list-inside space-y-3 text-lg text-justify">
     <li>
      <strong>
       Kesulitan Mencari Barang dalam Waktu Singkat:
      </strong>
      Mahasiswa sering kesulitan menemukan barang penting secara cepat saat
          dibutuhkan.
     </li>
     <li>
      <strong>
       Ketiadaan Mekanisme Pencatatan yang Jelas:
      </strong>
      Peminjaman informal tanpa catatan menyebabkan risiko kehilangan dan
          kebingungan status barang.
     </li>
     <li>
      <strong>
       Proses Peminjaman Tidak Terstruktur dan Inefisien:
      </strong>
      Metode tradisional seperti grup chat tidak terorganisir dan membuang
          waktu.
     </li>
    </ul>
    <div class="mt-6 flex justify-center">
     <img alt="Ilustrasi mahasiswa bingung mencari barang di grup chat dan kehilangan barang karena tidak ada pencatatan" class="rounded-lg shadow-lg w-full max-w-3xl object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/cc1d71dd-6cee-41d9-a3c4-a68ba9e7ee5c.jpg" width="600"/>
    </div>
   </section>
   <!-- Pengguna -->
   <section class="bg-white rounded-xl shadow-lg p-8" id="pengguna">
    <h2 class="text-3xl font-bold text-blue-800 mb-6 border-b-4 border-blue-600 pb-2">
     4. Identifikasi Pengguna Utama Sistem
    </h2>
    <p class="text-lg text-justify mb-4">
     Pengguna utama PinjamKuy adalah mahasiswa yang dapat berperan sebagai:
    </p>
    <ul class="list-disc list-inside space-y-3 text-lg text-justify">
     <li>
      <strong>
       Peminjam Barang:
      </strong>
      Mahasiswa yang membutuhkan barang
          dan menggunakan aplikasi untuk mencari serta mengajukan permintaan
          peminjaman.
     </li>
     <li>
      <strong>
       Pemilik Barang:
      </strong>
      Mahasiswa yang memiliki barang dan
          bersedia meminjamkannya, mengelola informasi barang dan permintaan
          peminjaman.
     </li>
    </ul>
    <p class="text-lg text-justify mt-4">
     Peran ini bersifat dinamis, dimana seorang mahasiswa dapat berganti
        peran sesuai kebutuhan.
    </p>
   </section>
   <!-- Analisis Kebutuhan -->
   <section class="bg-white rounded-xl shadow-lg p-8" id="kebutuhan">
    <h2 class="text-3xl font-bold text-blue-800 mb-6 border-b-4 border-blue-600 pb-2">
     5. Analisis Kebutuhan Sistem
    </h2>
    <article class="mb-8">
     <h3 class="text-2xl font-semibold mb-4 text-blue-700">
      5.1. Kebutuhan Fungsional
     </h3>
     <p class="mb-4 text-lg text-justify">
      Kebutuhan fungsional menjelaskan fitur dan fungsi utama yang harus
          dimiliki aplikasi:
     </p>
     <ul class="list-disc list-inside space-y-3 text-lg text-justify">
      <li>
       <strong>
        Registrasi dan Login:
       </strong>
       Pengguna dapat membuat akun
            dan masuk ke aplikasi dengan aman.
      </li>
      <li>
       <strong>
        Manajemen Barang:
       </strong>
       Pemilik dapat menambahkan,
            mengubah status, dan menghapus barang yang dipinjamkan.
      </li>
      <li>
       <strong>
        Pencarian dan Filter:
       </strong>
       Pengguna dapat mencari barang
            berdasarkan kata kunci dan kategori.
      </li>
      <li>
       <strong>
        Proses Peminjaman:
       </strong>
       Peminjam dapat mengajukan
            permintaan, dan pemilik dapat menyetujui atau menolak.
      </li>
      <li>
       <strong>
        Konfirmasi Penyerahan dan Pengembalian:
       </strong>
       Kedua pihak
            dapat mengonfirmasi status barang.
      </li>
      <li>
       <strong>
        Riwayat Transaksi:
       </strong>
       Pengguna dapat melihat riwayat
            peminjaman dan peminjaman barang.
      </li>
      <li>
       <strong>
        Notifikasi Real-time:
       </strong>
       Sistem mengirimkan notifikasi
            terkait status peminjaman.
      </li>
     </ul>
    </article>
    <article>
     <h3 class="text-2xl font-semibold mb-4 text-blue-700">
      5.2. Kebutuhan Non-Fungsional
     </h3>
     <ul class="list-disc list-inside space-y-3 text-lg text-justify">
      <li>
       <strong>
        Kinerja:
       </strong>
       Aplikasi harus responsif dengan waktu
            respon di bawah 3 detik.
      </li>
      <li>
       <strong>
        Keamanan:
       </strong>
       Data pengguna dan transaksi harus
            dienkripsi dan dilindungi.
      </li>
      <li>
       <strong>
        Ketersediaan:
       </strong>
       Sistem harus memiliki uptime minimal
            99.9%.
      </li>
      <li>
       <strong>
        Usability:
       </strong>
       Antarmuka harus intuitif dan mudah
            digunakan.
      </li>
      <li>
       <strong>
        Skalabilitas:
       </strong>
       Mampu menangani ribuan pengguna dan
            data tanpa penurunan performa.
      </li>
      <li>
       <strong>
        Kompatibilitas:
       </strong>
       Mendukung perangkat Android 7.0 ke
            atas.
      </li>
     </ul>
    </article>
   </section>
   <!-- Model SDLC -->
   <section class="bg-white rounded-xl shadow-lg p-8" id="sdlc">
    <h2 class="text-3xl font-bold text-blue-800 mb-6 border-b-4 border-blue-600 pb-2">
     6. Model SDLC (Software Development Life Cycle)
    </h2>
    <p class="text-lg text-justify mb-4">
     Model yang dipilih untuk pengembangan PinjamKuy adalah
     <strong>
      Waterfall
     </strong>
     ,
        karena:
    </p>
    <ul class="list-disc list-inside space-y-3 text-lg text-justify mb-6">
     <li>
      Spesifikasi kebutuhan sudah jelas dan minim perubahan selama proyek.
     </li>
     <li>
      Proyek berlingkup menengah dengan fitur terdefinisi.
     </li>
     <li>
      Batas waktu pengerjaan yang ketat dan terstruktur sesuai fase.
     </li>
     <li>
      Penekanan pada dokumentasi lengkap untuk referensi dan serah terima.
     </li>
    </ul>
    <p class="text-lg text-justify">
     Fase Waterfall yang akan dijalankan:
    </p>
    <ol class="list-decimal list-inside space-y-2 text-lg text-justify">
     <li>
      Requirement Analysis
     </li>
     <li>
      System Design
     </li>
     <li>
      Implementation
     </li>
     <li>
      Testing
     </li>
     <li>
      Deployment
     </li>
     <li>
      Maintenance
     </li>
    </ol>
   </section>
   <!-- Diagram Sistem -->
   <section class="bg-white rounded-xl shadow-lg p-8" id="diagram">
    <h2 class="text-3xl font-bold text-blue-800 mb-6 border-b-4 border-blue-600 pb-2">
     7. Diagram Sistem
    </h2>
    <!-- Use Case Diagram -->
    <article class="mb-10">
     <h3 class="text-2xl font-semibold mb-4 text-blue-700">
      7.1. Use Case Diagram
     </h3>
     <div class="overflow-x-auto bg-gray-50 rounded-lg p-6 shadow-inner">
      <pre class="whitespace-pre-wrap font-mono text-sm text-gray-900">
graph TD
    A[Mahasiswa] --&gt; UC1(Mendaftar Akun)
    A --&gt; UC2(Login)
    A --&gt; UC3(Melihat Daftar Barang)
    A --&gt; UC4(Mencari Barang)
    A --&gt; UC5(Mengajukan Permintaan Peminjaman)
    A --&gt; UC6(Melihat Riwayat Peminjaman)
    
    subgraph Pengelola Barang
        A -- (menambahkan) --&gt; UC7(Menambahkan Barang)
        A -- (mengelola) --&gt; UC8(Mengelola Ketersediaan Barang)
        UC8 -- (memerlukan) --&gt; UC7
    end
    
    subgraph Proses Peminjaman
        A -- (memproses) --&gt; UC9(Menyetujui/Menolak Permintaan)
        A -- (memproses) --&gt; UC10(Konfirmasi Pengembalian Barang)
        UC9 -- (memerlukan) --&gt; UC5
        UC10 -- (memerlukan) --&gt; UC5
    end
    
    S(Sistem PinjamKuy)
    UC1 -- (berinteraksi dengan) --&gt; S
    UC2 -- (berinteraksi dengan) --&gt; S
    UC3 -- (berinteraksi dengan) --&gt; S
    UC4 -- (berinteraksi dengan) --&gt; S
    UC5 -- (berinteraksi dengan) --&gt; S
    UC6 -- (berinteraksi dengan) --&gt; S
    UC7 -- (berinteraksi dengan) --&gt; S
    UC8 -- (berinteraksi dengan) --&gt; S
    UC9 -- (berinteraksi dengan) --&gt; S
    UC10 -- (berinteraksi dengan) --&gt; S
    
    S -- (mengirim) --&gt; UC11(Mengirim Notifikasi)
    UC11 --&gt; A
          </pre>
     </div>
    </article>
    <!-- Activity Diagram -->
    <article class="mb-10">
     <h3 class="text-2xl font-semibold mb-4 text-blue-700">
      7.2. Activity Diagram: Alur Peminjaman Barang
     </h3>
     <div class="overflow-x-auto bg-gray-50 rounded-lg p-6 shadow-inner">
      <pre class="whitespace-pre-wrap font-mono text-sm text-gray-900">
graph TD
    start((Start)) --&gt; A[Mahasiswa Peminjam: Membuka Aplikasi]
    A --&gt; B{Apakah Ada Kebutuhan Barang?}
    B -- Ya --&gt; C[Mahasiswa Peminjam: Mencari dan Memilih Barang]
    C --&gt; D[Mahasiswa Peminjam: Mengajukan Permintaan Peminjaman]
    D --&gt; E[Sistem: Mencatat Permintaan &amp; Mengirim Notifikasi ke Pemilik]
    E --&gt; F[Mahasiswa Pemilik: Menerima Notifikasi]
    F --&gt; G{Mahasiswa Pemilik: Meninjau Permintaan?}
    G -- Ya --&gt; H[Mahasiswa Pemilik: Menyetujui atau Menolak Permintaan]
    H -- Disetujui --&gt; I[Sistem: Mengubah Status Barang &amp; Mengirim Notifikasi Konfirmasi ke Peminjam]
    I --&gt; J[Peminjam &amp; Pemilik: Berkoordinasi Penyerahan Barang (Offline)]
    J --&gt; K[Mahasiswa Peminjam: Menerima Barang]
    K --&gt; L[Mahasiswa Peminjam: Menggunakan Barang]
    L --&gt; M[Mahasiswa Peminjam: Mengembalikan Barang]
    M --&gt; N[Mahasiswa Pemilik: Menerima Barang &amp; Mengkonfirmasi Pengembalian di Aplikasi]
    N --&gt; O[Sistem: Memperbarui Status Barang (Tersedia Kembali) &amp; Riwayat Peminjaman]
    H -- Ditolak --&gt; P[Sistem: Mengirim Notifikasi Penolakan ke Peminjam]
    P --&gt; Q[Sistem: Memperbarui Riwayat Peminjaman (Ditolak)]
    Q --&gt; end((End))
    O --&gt; end
    B -- Tidak --&gt; end
          </pre>
     </div>
    </article>
    <!-- Class Diagram -->
    <article class="mb-10">
     <h3 class="text-2xl font-semibold mb-4 text-blue-700">
      7.3. Class Diagram
     </h3>
     <div class="overflow-x-auto bg-gray-50 rounded-lg p-6 shadow-inner">
      <pre class="whitespace-pre-wrap font-mono text-sm text-gray-900">
classDiagram
    class User {
        +String userId
        +String nim
        +String nama
        +String email
        +String passwordHash
        +register(nama, nim, email, password): void
        +login(email, password): boolean
        +logout(): void
        +updateProfile(nama, email): void
    }

    class Barang {
        +String barangId
        +String namaBarang
        +String deskripsi
        +String kondisi
        +String fotoUrl
        +String pemilikId
        +Boolean isAvailable
        +tambahBarang(nama, deskripsi, kondisi, foto, pemilikId): void
        +hapusBarang(barangId): void
        +ubahStatusKetersediaan(barangId, status): void
        +getBarangDetails(barangId): Barang
    }

    class Peminjaman {
        +String peminjamanId
        +String barangId
        +String peminjamId
        +String tanggalPeminjaman
        +String tanggalPengembalianDijanjikan
        +String tanggalPengembalianAktual
        +String status
        +String catatanPeminjam
        +String catatanPemilik
        +ajukanPeminjaman(barangId, peminjamId, tanggalDijanjikan): void
        +konfirmasiPeminjaman(peminjamanId): void
        +tolakPeminjaman(peminjamanId, alasan): void
        +konfirmasiPengembalian(peminjamanId): void
    }

    class Notifikasi {
        +String notifikasiId
        +String userIdPenerima
        +String pesan
        +String tipeNotifikasi
        +String tanggalWaktu
        +boolean isRead
        +kirimNotifikasi(userId, pesan, tipe): void
        +markAsRead(notifikasiId): void
    }

    User "1" -- "*" Barang : memiliki
    User "1" -- "*" Peminjaman : melakukan/terlibat
    Barang "1" -- "*" Peminjaman : terkait dengan
    User "1" -- "*" Notifikasi : menerima
          </pre>
     </div>
    </article>
    <!-- Sequence Diagram -->
    <article>
     <h3 class="text-2xl font-semibold mb-4 text-blue-700">
      7.4. Sequence Diagram: Alur Login Pengguna
     </h3>
     <div class="overflow-x-auto bg-gray-50 rounded-lg p-6 shadow-inner">
      <pre class="whitespace-pre-wrap font-mono text-sm text-gray-900">
sequenceDiagram
    participant Pengguna as U
    participant AplikasiPinjamKuy as APP
    participant FirebaseAuthentication as FA
    participant FirebaseDatabase as FD

    U-&gt;&gt;APP: Membuka Aplikasi
    APP-&gt;&gt;U: Tampilkan Halaman Login (UI)
    U-&gt;&gt;APP: Memasukkan Email &amp; Kata Sandi, lalu klik "Login"
    APP-&gt;&gt;FA: Kirim email &amp; kata sandi untuk autentikasi
    FA--&gt;&gt;APP: Hasil Autentikasi (Sukses/Gagal, User ID jika sukses)
    alt Jika Autentikasi Sukses
        APP-&gt;&gt;FD: Permintaan Data Profil Pengguna (menggunakan User ID)
        FD--&gt;&gt;APP: Kirim Data Profil Pengguna (Nama, NIM, dll.)
        APP-&gt;&gt;U: Tampilkan Halaman Dashboard dengan Data Profil
    else Jika Autentikasi Gagal
        APP-&gt;&gt;U: Tampilkan Pesan Error: "Email atau kata sandi salah."
    end
          </pre>
     </div>
    </article>
   </section>
   <!-- Wireframe -->
   <section class="bg-white rounded-xl shadow-lg p-8" id="wireframe">
    <h2 class="text-3xl font-bold text-blue-800 mb-6 border-b-4 border-blue-600 pb-2">
     8. Wireframe Sistem: Desain Antarmuka Pengguna
    </h2>
    <!-- Halaman Login -->
    <article class="mb-12 max-w-md mx-auto bg-gradient-to-br from-blue-50 to-white rounded-xl shadow-lg p-8">
     <h3 class="text-2xl font-semibold mb-6 text-blue-700 text-center">
      8.1. Halaman Login
     </h3>
     <div class="flex justify-center mb-6">
      <img alt="Logo PinjamKuy berupa ikon tangan saling meminjamkan barang berwarna biru dan putih" class="w-24 h-24 rounded-full shadow-md" height="100" src="https://storage.googleapis.com/a1aa/image/7eeb4c4b-be31-4082-5d2d-2dc3ea8fa080.jpg" width="100"/>
     </div>
     <form class="space-y-6">
      <input autocomplete="username" class="w-full px-5 py-3 rounded-lg border border-blue-300 focus:outline-none focus:ring-4 focus:ring-blue-400 transition" placeholder="Alamat Email / NIM" type="text"/>
      <input autocomplete="current-password" class="w-full px-5 py-3 rounded-lg border border-blue-300 focus:outline-none focus:ring-4 focus:ring-blue-400 transition" placeholder="Kata Sandi" type="password"/>
      <button class="w-full bg-blue-700 text-white py-3 rounded-lg font-semibold hover:bg-blue-800 transition" type="submit">
       LOGIN
      </button>
     </form>
     <div class="mt-5 text-center text-sm text-blue-700 space-y-2">
      <button class="underline hover:text-blue-900" type="button">
       Lupa Kata Sandi?
      </button>
      <p>
       Belum punya akun?
       <button class="underline hover:text-blue-900" type="button">
        Daftar di sini
       </button>
      </p>
     </div>
    </article>
    <!-- Halaman Dashboard -->
    <article class="mb-12 max-w-4xl mx-auto bg-white rounded-xl shadow-lg p-8 flex flex-col min-h-[600px]">
     <header class="flex items-center justify-between mb-6">
      <button aria-label="Kembali" class="text-blue-700 hover:text-blue-900" type="button">
       <i class="fas fa-arrow-left fa-lg">
       </i>
      </button>
      <h1 class="text-2xl font-bold text-center flex-grow text-blue-700">
       PinjamKuy
      </h1>
      <button aria-label="Profil Pengguna" class="text-blue-700 hover:text-blue-900" type="button">
       <i class="fas fa-user-circle fa-lg">
       </i>
      </button>
     </header>
     <input aria-label="Kolom pencarian barang" class="mb-6 px-5 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-4 focus:ring-blue-400 transition" placeholder="Cari barang..." type="search"/>
     <div class="flex flex-wrap gap-3 mb-8 text-sm">
      <button class="px-4 py-2 rounded-full bg-blue-700 text-white font-semibold hover:bg-blue-800 transition" type="button">
       Semua
      </button>
      <button class="px-4 py-2 rounded-full border border-blue-700 text-blue-700 hover:bg-blue-100 transition" type="button">
       Elektronik
      </button>
      <button class="px-4 py-2 rounded-full border border-blue-700 text-blue-700 hover:bg-blue-100 transition" type="button">
       Buku
      </button>
      <button class="px-4 py-2 rounded-full border border-blue-700 text-blue-700 hover:bg-blue-100 transition" type="button">
       Alat Tulis
      </button>
      <button class="px-4 py-2 rounded-full border border-blue-700 text-blue-700 hover:bg-blue-100 transition" type="button">
       Lainnya
      </button>
     </div>
     <div class="flex-grow overflow-y-auto space-y-8">
      <article class="flex gap-5 items-center border border-gray-200 rounded-xl p-4 shadow hover:shadow-lg transition bg-white">
       <img alt="Foto charger laptop hitam dengan kabel rapi di atas meja kayu" class="w-20 h-20 object-cover rounded-xl" height="80" src="https://storage.googleapis.com/a1aa/image/55c23f42-53f4-4def-d361-cd31a47979c9.jpg" width="80"/>
       <div class="flex flex-col flex-grow">
        <h3 class="font-semibold text-xl text-blue-700">
         Charger Laptop
        </h3>
        <p class="text-gray-600">
         Kondisi: Baik
        </p>
        <p class="text-gray-600">
         Pemilik: Budi
        </p>
        <p class="text-green-600 font-semibold">
         Status: Tersedia
        </p>
       </div>
       <button class="bg-blue-700 text-white px-4 py-2 rounded-lg font-semibold hover:bg-blue-800 transition" type="button">
        Pinjam
       </button>
      </article>
      <article class="flex gap-5 items-center border border-gray-200 rounded-xl p-4 shadow hover:shadow-lg transition bg-white">
       <img alt="Foto jas lab putih tergantung di hanger dengan latar belakang laboratorium" class="w-20 h-20 object-cover rounded-xl" height="80" src="https://storage.googleapis.com/a1aa/image/622219e5-a878-4e9d-ddfd-e9e5b9731157.jpg" width="80"/>
       <div class="flex flex-col flex-grow">
        <h3 class="font-semibold text-xl text-blue-700">
         Jas Lab
        </h3>
        <p class="text-gray-600">
         Kondisi: Cukup Baik
        </p>
        <p class="text-gray-600">
         Pemilik: Ani
        </p>
        <p class="text-green-600 font-semibold">
         Status: Tersedia
        </p>
       </div>
       <button class="bg-blue-700 text-white px-4 py-2 rounded-lg font-semibold hover:bg-blue-800 transition" type="button">
        Pinjam
       </button>
      </article>
      <article class="flex gap-5 items-center border border-gray-200 rounded-xl p-4 shadow hover:shadow-lg transition bg-white">
       <img alt="Foto kalkulator ilmiah FX-991ES abu-abu dengan layar dan tombol lengkap" class="w-20 h-20 object-cover rounded-xl" height="80" src="https://storage.googleapis.com/a1aa/image/cdec05e1-79d5-494e-da4d-75ec012fa0cd.jpg" width="80"/>
       <div class="flex flex-col flex-grow">
        <h3 class="font-semibold text-xl text-blue-700">
         Kalkulator FX-991ES
        </h3>
        <p class="text-gray-600">
         Kondisi: Baik
        </p>
        <p class="text-gray-600">
         Pemilik: Gilang
        </p>
        <p class="text-green-600 font-semibold">
         Status: Tersedia
        </p>
       </div>
       <button class="bg-blue-700 text-white px-4 py-2 rounded-lg font-semibold hover:bg-blue-800 transition" type="button">
        Pinjam
       </button>
      </article>
     </div>
     <button aria-label="Tambah Barang" class="fixed bottom-28 right-8 bg-blue-700 text-white rounded-full w-16 h-16 flex items-center justify-center shadow-xl hover:bg-blue-800 transition" type="button">
      <i class="fas fa-plus fa-lg">
      </i>
     </button>
     <nav aria-label="Navigasi bawah" class="fixed bottom-0 left-0 w-full bg-white border-t border-gray-300 flex justify-around py-4 shadow-inner">
      <button aria-label="Beranda" class="text-blue-700 hover:text-blue-900" type="button">
       <i class="fas fa-home fa-lg">
       </i>
      </button>
      <button aria-label="Riwayat" class="text-gray-600 hover:text-blue-700" type="button">
       <i class="fas fa-history fa-lg">
       </i>
      </button>
      <button aria-label="Tambah Barang" class="text-gray-600 hover:text-blue-700" type="button">
       <i class="fas fa-plus-circle fa-lg">
       </i>
      </button>
      <button aria-label="Notifikasi" class="text-gray-600 hover:text-blue-700" type="button">
       <i class="fas fa-bell fa-lg">
       </i>
      </button>
     </nav>
    </article>
    <!-- Halaman Detail Barang -->
    <article class="mb-12 max-w-md mx-auto bg-white rounded-xl shadow-lg p-8">
     <header class="flex items-center mb-6">
      <button aria-label="Kembali" class="text-blue-700 hover:text-blue-900 mr-4" type="button">
       <i class="fas fa-arrow-left fa-lg">
       </i>
      </button>
      <h1 class="text-2xl font-bold text-blue-700">
       Detail Barang
      </h1>
     </header>
     <img alt="Foto besar charger laptop hitam dengan kabel rapi di atas meja kayu, menampilkan detail fisik barang" class="w-full rounded-xl mb-6 object-cover" height="240" src="https://storage.googleapis.com/a1aa/image/e9e75154-4f29-45e7-94b1-b5c3c5c079c6.jpg" width="320"/>
     <div class="space-y-3 text-lg">
      <p>
       <strong>
        Nama Barang:
       </strong>
       Charger Laptop
      </p>
      <p>
       <strong>
        Deskripsi:
       </strong>
       Charger laptop Acer kompatibel dengan
            berbagai model, kabel panjang dan kondisi baik.
      </p>
      <p>
       <strong>
        Kondisi:
       </strong>
       Baik
      </p>
      <p>
       <strong>
        Pemilik:
       </strong>
       Rifqi Putra A.
      </p>
     </div>
     <button class="mt-8 w-full bg-blue-700 text-white py-3 rounded-lg font-semibold hover:bg-blue-800 transition" type="button">
      PINJAM SEKARANG
     </button>
    </article>
    <!-- Halaman Riwayat Peminjaman -->
    <article class="max-w-4xl mx-auto bg-white rounded-xl shadow-lg p-8 flex flex-col min-h-[500px]">
     <header class="flex items-center mb-6">
      <button aria-label="Kembali" class="text-blue-700 hover:text-blue-900 mr-4" type="button">
       <i class="fas fa-arrow-left fa-lg">
       </i>
      </button>
      <h1 class="text-2xl font-bold text-blue-700">
       Riwayat Peminjaman
      </h1>
     </header>
     <nav class="flex space-x-6 mb-8 text-sm font-semibold text-blue-700">
      <button class="border-b-4 border-blue-700 pb-2" type="button">
       Dipinjamkan
      </button>
      <button class="text-gray-500 hover:text-blue-700" type="button">
       Dipinjam
      </button>
     </nav>
     <div class="flex-grow overflow-y-auto space-y-8">
      <article class="border border-gray-200 rounded-xl p-6 shadow bg-white">
       <p>
        <strong>
         Barang:
        </strong>
        Jas Lab
       </p>
       <p>
        <strong>
         Peminjam/Pemilik:
        </strong>
        Adira A.
       </p>
       <p>
        <strong>
         Tanggal Pinjam:
        </strong>
        01/07/2025
       </p>
       <p class="text-green-600 font-semibold">
        <strong>
         Status:
        </strong>
        Sudah Dikembalikan
       </p>
      </article>
      <article class="border border-gray-200 rounded-xl p-6 shadow bg-white">
       <p>
        <strong>
         Barang:
        </strong>
        Kalkulator FX-991ES
       </p>
       <p>
        <strong>
         Peminjam/Pemilik:
        </strong>
        Gilang P.
       </p>
       <p>
        <strong>
         Tanggal Pinjam:
        </strong>
        03/07/2025
       </p>
       <p class="text-yellow-600 font-semibold">
        <strong>
         Status:
        </strong>
        Sedang Dipinjam
       </p>
      </article>
      <article class="border border-gray-200 rounded-xl p-6 shadow bg-white">
       <p>
        <strong>
         Barang:
        </strong>
        Buku Fisika
       </p>
       <p>
        <strong>
         Peminjam/Pemilik:
        </strong>
        Sari W.
       </p>
       <p>
        <strong>
         Tanggal Pinjam:
        </strong>
        10/06/2025
       </p>
       <p class="text-green-600 font-semibold">
        <strong>
         Status:
        </strong>
        Sudah Dikembalikan
       </p>
      </article>
      <article class="border border-gray-200 rounded-xl p-6 shadow bg-white">
       <p>
        <strong>
         Barang:
        </strong>
        Pulpen Hitam
       </p>
       <p>
        <strong>
         Peminjam/Pemilik:
        </strong>
        Dedi R.
       </p>
       <p>
        <strong>
         Tanggal Pinjam:
        </strong>
        15/06/2025
       </p>
       <p class="text-yellow-600 font-semibold">
        <strong>
         Status:
        </strong>
        Sedang Dipinjam
       </p>
      </article>
     </div>
    </article>
   </section>
  </main>
  <footer class="bg-blue-800 text-white py-6 mt-12 shadow-inner">
   <div class="max-w-6xl mx-auto px-6 text-center text-sm font-light">
    © 2025 PinjamKuy - Aplikasi Peminjaman Barang Antar Mahasiswa
   </div>
  </footer>
 </body>
</html>
