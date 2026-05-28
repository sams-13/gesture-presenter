Gesture Presenter - Kontrol Presentasi dengan Gerakan Tangan

Gesture Presenter adalah aplikasi web inovatif yang memungkinkan pengguna mengontrol navigasi slide presentasi hanya menggunakan gerakan tangan di depan webcam. Dengan memanfaatkan teknologi computer vision modern, aplikasi ini menghadirkan pengalaman presentasi yang lebih natural, higienis, dan profesional tanpa perlu menyentuh perangkat apapun.

Tentang Proyek

Gesture Presenter hadir sebagai solusi presentasi hands-free yang memungkinkan pembicara bergerak bebas di atas panggung sambil tetap mengontrol alur presentasi. Cukup dengan membuka telapak tangan atau mengepalkan tangan di depan kamera, slide akan berpindah secara otomatis. Aplikasi ini sangat cocok digunakan dalam berbagai situasi seperti presentasi bisnis, seminar, workshop, pengajaran daring, hingga sesi pitching di depan investor.

Aplikasi ini dibangun dengan pendekatan client-side murni sehingga tidak memerlukan instalasi software tambahan, tidak mengirimkan data video ke server manapun, dan dapat berjalan secara real-time di browser modern dengan latensi yang sangat rendah.

Fitur Utama

Kontrol Slide Tanpa Sentuhan: Gunakan gerakan tangan sederhana untuk mengontrol navigasi slide. Telapak tangan terbuka untuk maju ke slide berikutnya. Kepalan tangan untuk mundur ke slide sebelumnya.

Webcam Real-Time: Aplikasi langsung mengakses kamera perangkat dan menampilkan umpan balik visual sehingga pengguna dapat melihat posisi tangan mereka saat melakukan gerakan.

Privasi Terjaga Penuh: Semua pemrosesan deteksi gerakan dilakukan langsung di browser menggunakan WebAssembly. Tidak ada satupun data video yang dikirim ke server eksternal.

Antarmuka Sederhana dan Intuitif: Dilengkapi dengan tombol Mulai Kamera untuk mengaktifkan deteksi dan navigasi slide bawaan yang sudah dimuat sehingga pengguna dapat langsung mencoba fitur tanpa persiapan slide sendiri.

Aksesibilitas Tinggi: Membantu penyandang disabilitas motorik atau kondisi yang mengharuskan presentasi tanpa menyentuh perangkat.

Teknologi yang Digunakan

MediaPipe Hands: Library Google untuk pendeteksian landmark tangan 21 titik secara real-time dengan akurasi tinggi

JavaScript (ES6+): Logika deteksi gerakan dan kontrol navigasi slide

HTML5 Canvas: Visualisasi umpan balik kamera dan overlay deteksi tangan

CSS3: Desain antarmuka pengguna yang responsif dan modern

GitHub Pages: Hosting dan deployment otomatis untuk akses publik

Cara Menjalankan Proyek Secara Lokal

Jika Anda ingin menjalankan proyek ini di komputer sendiri, ikuti langkah-langkah berikut:

Clone repositori ini:
git clone https://github.com/sams-13/gesture-presenter.git

Masuk ke direktori proyek:
cd gesture-presenter

Buka file index.html di browser favorit Anda. Disarankan menggunakan browser berbasis Chromium (Chrome, Edge, Brave) untuk kompatibilitas MediaPipe yang optimal.

Izinkan akses webcam ketika browser meminta izin.

Klik tombol Mulai Kamera dan coba lakukan gerakan telapak terbuka atau kepalan tangan di depan kamera.

Catatan: Proyek ini sepenuhnya bersifat statis dan tidak memerlukan server backend. Pastikan koneksi internet tersedia untuk mengunduh model MediaPipe dari CDN.

Demo Langsung

Lihat langsung hasil akhir proyek ini dalam aksi di sini: https://sams-13.github.io/gesture-presenter/

Kontribusi

Kami sangat terbuka terhadap kontribusi dari siapa pun. Apakah Anda ingin menambahkan gesture baru, meningkatkan akurasi deteksi, atau menambahkan fitur seperti kontrol pointer laser virtual atau menggambar di slide, silakan lakukan langkah-langkah berikut:

Fork repositori ini.

Buat branch baru untuk fitur atau perbaikan Anda (git checkout -b fitur-baru).

Lakukan commit pada perubahan Anda (git commit -m 'Menambahkan fitur baru').

Push ke branch Anda (git push origin fitur-baru).

Buka Pull Request dan jelaskan perubahan Anda secara rinci.

Lisensi

Proyek ini dilisensikan di bawah MIT License. Anda bebas menggunakan, menyalin, memodifikasi, dan mendistribusikan kode ini, selama menyertakan lisensi asli. Silakan lihat file LICENSE untuk informasi lebih lanjut.

Kontak

Jika ada pertanyaan, saran, atau sekadar ingin berkenalan, hubungi melalui email: alqassamamuhammad@gmail.com atau GitHub: sams-13.

Jangan lupa untuk memberi bintang (star) pada repositori ini jika Anda merasa proyek ini bermanfaat.
