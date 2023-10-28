# Program Java Pengecekan Palindrome

Program Java ini adalah contoh sederhana untuk menentukan apakah sebuah kata atau kalimat yang dimasukkan oleh pengguna adalah palindrome atau tidak. Palindrome adalah kata atau kalimat yang dapat dibaca dari depan maupun dari belakang dengan hasil yang sama.

## Cara Penggunaan

1. **Menjalankan Program**: Pastikan Anda memiliki Java Runtime Environment (JRE) terinstal di komputer Anda. Anda dapat menjalankan program ini dengan mengikuti langkah-langkah berikut:

   ```bash
   javac Main.java  # Compile program
   java Main        # Jalankan program

Input Pengguna: Program akan meminta Anda untuk memasukkan kata atau kalimat. Masukkan teks yang ingin Anda cek apakah merupakan palindrome atau bukan.

Hasil: Setelah Anda memasukkan teks, program akan memberikan hasil berupa pesan yang mengindikasikan apakah teks tersebut adalah palindrome atau bukan.

## Cara Kerja

Program ini bekerja dengan langkah-langkah berikut:

   1. Menghapus spasi dari teks dan mengubah seluruh teks menjadi huruf kecil.
   2. Menghapus tanda baca dan karakter selain huruf atau angka dari teks.
   3. Mengecek apakah teks yang telah diolah adalah palindrome dengan menggunakan dua indeks, yaitu left dan right, yang berjalan dari depan dan belakang teks. Jika karakter yang ditemui tidak sama, maka program mengembalikan false. Jika kedua indeks bertemu tanpa adanya perbedaan karakter, maka program mengembalikan true.

### Contoh Penggunaan

Misalnya, jika Anda menjalankan program dan memasukkan teks "level," maka program akan mengeluarkan pesan:
    'level' adalah palindrome.

Sedangkan jika Anda memasukkan teks "hello," maka program akan mengeluarkan pesan:
    'hello' bukan palindrome.