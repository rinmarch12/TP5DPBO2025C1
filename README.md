Janji
---
Saya Ririn Marchelina dengan NIM 2303662 mengerjakan Tugas Praktikum 5 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

---
Dokumentasi
---
![Screenshot](https://github.com/user-attachments/assets/5b4c2d4c-3a02-4ea9-8729-f7562e48189e)

Alur Program
---
1. Tampilan Awal
---
Saat aplikasi dijalankan, pengguna akan melihat tampilan utama yang berisi:
- Form input untuk mengisi NIM, Nama, Jenis Kelamin, dan Fakultas.
- Tabel daftar mahasiswa yang menampilkan data mahasiswa yang sudah ada.
---
Tombol-tombol interaksi:
- Add (atau Update jika memilih data).
- Delete (tersembunyi hingga data dipilih).
- Cancel untuk mengosongkan form.

2. Menambah Data (Add Data)
- Pengguna mengisi NIM, Nama, Jenis Kelamin, dan Fakultas di form input.
- Menekan tombol "Add".
- Memeriksa apakah semua field sudah diisi.
- Mengecek apakah NIM sudah ada di database.
- Jika valid, data ditambahkan ke database dan tabel diperbarui.
- Form input dikosongkan kembali setelah data ditambahkan.
- Muncul notifikasi "Data berhasil ditambahkan!".

3. Mengubah Data (Update Data)
- Pengguna mengklik salah satu baris di tabel.
- Data dari baris yang dipilih akan otomatis muncul di form input.
- Tombol "Add" berubah menjadi "Update", dan tombol Delete muncul.
- Pengguna bisa mengedit data di form input.
- Menekan tombol "Update" untuk menyimpan perubahan.
- Memeriksa apakah semua field sudah diisi.
- Mengupdate data dalam database.
- Memperbarui tabel dengan data terbaru.
- Form input dikosongkan kembali setelah update selesai.
- Muncul notifikasi "Data berhasil diubah!".

4. Menghapus Data (Delete Data)
- Pengguna mengklik salah satu baris di tabel untuk memilih data yang akan dihapus.
- Tombol Delete akan muncul.
- Saat tombol "Delete" ditekan, muncul konfirmasi penghapusan.
- Jika pengguna memilih "Yes", data akan dihapus dari tabel.
- Form input dikosongkan kembali setelah data dihapus.
- Muncul notifikasi "Data berhasil dihapus!".

5. Mengosongkan Form (Cancel Button)
- Jika pengguna ingin membatalkan atau mengosongkan form, tombol Cancel bisa ditekan.
- Semua input akan dikosongkan, tombol Update kembali menjadi Add, dan tombol Delete disembunyikan.

