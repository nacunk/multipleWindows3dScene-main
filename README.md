# Belajar 3d multiple control Browser menggunakan Three.js

## Pendahuluan
Proyek ini memperlihatkan pendekatan unik dalam membuat dan mengelola sebuah adegan 3D melintasi beberapa jendela browser menggunakan Three.js dan localStorage. Proyek ini dirancang untuk para pengembang yang tertarik dalam grafis web lanjutan dan teknik pengelolaan jendela.

## Fitur
- Pembuatan dan rendering adegan 3D dengan Three.js.
- Sinkronisasi adegan 3D melintasi beberapa jendela browser.
- Pengelolaan jendela dinamis dan sinkronisasi status menggunakan localStorage.

## Instalasi
Klon repositori ini dan buka `index.html` di browser Anda untuk mulai menjelajahi adegan 3D.

```
git clone https://github.com/nacunk/multipleWindow3dScene
```
## Penggunaan
Logika aplikasi utama terdaopat dalam `main.js` dan `WindowManager.js`. Adegan 3D dirender dalam `index.html`,yang berfungsi sebagai titik masuk aplikasi.
## Struktur dan Komponen
- `index.html`: Titik masuk yang menyiapkan struktur HTML dan menyertakan pustaka Three.js dan skrip utama.
- `WindowManager.js`: Kelas inti yang mengelola pembuatan jendela, sinkronisasi, dan pengelolaan status melintasi beberapa jendela.
- `main.js`: Mengandung logika untuk menginisialisasi adegan 3D, menangani peristiwa ukuran jendela, dan merender adegan.
- `three.r124.min.js`: Versi terkompres dari pustaka Three.js yang digunakan untuk rendering grafis 3D.

## Fungsi Detail
- `WindowManager.js` menangani siklus hidup beberapa jendela browser, termasuk pembuatan, sinkronisasi, dan penghapusan. Ini menggunakan localStorage untuk mempertahankan status melintasi jendela.
- `main.js` menginisialisasi adegan 3D menggunakan Three.js, mengelola peristiwa perubahan ukuran jendela, dan memperbarui adegan berdasarkan interaksi jendela.

## Berkontribusi
Kontribusi untuk meningkatkan atau memperluas proyek ini sangat disambut. Silakan fork repositori, lakukan perubahan, dan kirim pull request.

## Lisensi
Proyek ini bersifat open source di bawah Lisensi MIT.

