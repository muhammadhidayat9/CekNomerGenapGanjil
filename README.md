# Aplikasi Cek Nomor Genap/Ganjil

## Deskripsi Program
Aplikasi ini adalah program GUI sederhana menggunakan Java Swing yang dapat memeriksa apakah input angka adalah bilangan **Genap** atau **Ganjil**. Program memiliki antarmuka yang terdiri dari:

- **JTextField**: Untuk input angka.
- **JButton**: Tombol untuk memulai pengecekan.
- **JLabel**: Menampilkan hasil pengecekan.

Saat tombol ditekan, program akan memvalidasi input angka dan menampilkan hasilnya pada JLabel.

## Komponen GUI
Aplikasi ini menggunakan komponen berikut:

- `JFrame`: Jendela utama aplikasi.
- `JPanel`: Panel untuk menata komponen GUI.
- `JLabel`: Menampilkan hasil atau pesan kepada pengguna.
- `JTextField`: Input angka dari pengguna.
- `JButton`: Tombol untuk melakukan pengecekan angka.

## Logika Program
Logika program menggunakan:

- **Kondisional (if-else)**: Untuk memeriksa apakah angka adalah Genap atau Ganjil.
- **Validasi input**: Memastikan input hanya berisi angka dan tidak kosong.

## Events
Aplikasi ini menggunakan event handling sebagai berikut:

- **ActionListener**: Untuk mendeteksi klik pada tombol Cek.
- **KeyAdapter**: Untuk membatasi input pada JTextField agar hanya menerima angka.

## Fitur Tambahan
- Memeriksa apakah angka adalah **bilangan prima**.
- Menggunakan **JOptionPane** untuk menampilkan pesan hasil dan pesan kesalahan.
- Implementasi **FocusListener** untuk membersihkan JTextField saat mendapatkan fokus.

## Cara Menggunakan
1. Masukkan angka ke dalam JTextField.
2. Klik tombol "Cek".
3. Hasil akan ditampilkan di JLabel.
   - Jika input tidak valid, pesan error akan muncul menggunakan JOptionPane.

## Variasi Pengembangan
- Anda bisa menambahkan fitur pengecekan bilangan negatif atau bilangan nol.
- Menambahkan logika tambahan untuk menampilkan pesan khusus jika angka adalah bilangan prima.

## Teknologi yang Digunakan
- **Java Swing**: Untuk pembuatan antarmuka GUI.
- **NetBeans IDE**: Pengembangan proyek menggunakan NetBeans.

## Penulis
Dikembangkan oleh [Muhammad Hidayat(2210010354)].

