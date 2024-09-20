# Crypto Tool

Crypto Tool adalah program yang menggunakan algoritma enkripsi Vigenere, Playfair, dan Hill dengan antarmuka pengguna grafis (GUI) menggunakan Tkinter.

## Cara Menjalankan Program

1. **Persiapan Lingkungan:**
   - Pastikan Python sudah terinstal di komputer Anda. Jika anda belum mengunduhnya, anda dapat mengunduhnya dari [python.org](https://www.python.org/).

2. **Instalasi Dependensi:**
   - Install library yang dibutuhkan dengan menjalankan perintah berikut di terminal:
     ```bash
     pip install numpy
     ```

3. **Menjalankan Program:**
   - Simpan kode program ke dalam file Python, misalnya `crypto_tool.py`.
   - Buka terminal atau command prompt, lalu navigasikan ke direktori tempat Anda menyimpan file tersebut.
   - Jalankan program dengan perintah:
     ```bash
     python crypto_tool.py
     ```

4. **Menggunakan Program:**
   - Setelah program berjalan, Anda akan melihat antarmuka pengguna.
   - Masukkan pesan yang ingin dienkripsi atau didekripsi di kolom "Input Message".
   - Masukkan kunci yang panjangnya minimal 12 karakter di kolom "Key".
   - Pilih jenis cipher yang ingin digunakan (Vigenere, Playfair, atau Hill) dari menu dropdown.
   - Klik tombol "Encrypt" untuk mengenkripsi pesan atau "Decrypt" untuk mendekripsinya.
   - Anda dapat meng-upload file .txt untuk mengisi pesan input dengan mengklik tombol "Upload File".
   - Hasil enkripsi atau dekripsi akan ditampilkan di bagian "Result".
   - Untuk menyimpan hasil ke dalam file .txt, klik tombol "Save to File".

## Catatan
- Pastikan kunci yang digunakan memenuhi syarat panjang yang ditentukan.
- Untuk cipher Playfair dan Hill, format kunci harus sesuai dengan aturan yang berlaku pada masing-masing algoritma.
