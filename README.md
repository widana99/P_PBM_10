# Destini App - Flutter Interactive Story Game
---
Destini adalah aplikasi cerita interaktif (choose-your-own-adventure) berbasis Flutter, di mana pengguna dapat membaca cerita dan memilih alur ceritanya sendiri berdasarkan dua pilihan yang tersedia di setiap langkah.

---
# Fitur Utama
---
- Cerita interaktif dengan dua pilihan per bagian.
- UI sederhana dengan tema gelap dan latar gambar.
- Logika cerita terpisah dalam file modular (story_brain.dart).
- Tampilan responsif dan dinamis berdasarkan pilihan user.
- Dukungan untuk menyembunyikan tombol pilihan kedua saat tidak diperlukan.
---
Screenshot
---
## Halaman utama
---
![image](https://github.com/user-attachments/assets/d9ced3b1-2abb-4253-ba80-80165b721895)
## Halaman Isi
---
![image](https://github.com/user-attachments/assets/c7a5827c-492a-43dd-9e6e-ed72006e7f37)
![image](https://github.com/user-attachments/assets/794da4b0-fbe8-4c2d-95cc-6fb79ca961ab)
![image](https://github.com/user-attachments/assets/38fca660-f2db-408f-9f36-dafdef841528)
![image](https://github.com/user-attachments/assets/7fff4b7a-dd2b-434a-9572-12398865776f)
---
# Alur Program
---
Setelah aplikasi dijalankan, main.dart akan memuat widget utama DestiniApp yang langsung menampilkan halaman StoryPage. Di halaman ini, cerita pertama ditampilkan bersama dua tombol pilihan. Ketika pengguna menekan salah satu tombol, fungsi nextStory() pada objek storyBrain dipanggil untuk menentukan kelanjutan cerita berdasarkan pilihan tersebut. Fungsi ini juga mengatur apakah tombol pilihan kedua perlu ditampilkan atau disembunyikan. Selanjutnya, setState() akan memperbarui tampilan UI dengan bagian cerita yang baru sesuai dengan alur yang dipilih oleh pengguna. Proses ini terus berulang hingga cerita berakhir.
