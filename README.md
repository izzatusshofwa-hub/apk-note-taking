# apk-note-taking

Program sederhana aplikasi note-taking menggunakan Python yang mendukung:
- Multiple tags pada note
- Tampilan chronological dan alphabetical
- Recent changes menggunakan circular buffer

---


## 📊 Analisis Program

Program ini menunjukkan cara kerja struktur data pada aplikasi note-taking sederhana. Data note disimpan menggunakan list dan dictionary sehingga setiap note dapat memiliki beberapa tag sekaligus. Program juga dapat menampilkan note berdasarkan urutan data dibuat (chronological) dan berdasarkan abjad (alphabetical). Selain itu, digunakan deque sebagai circular buffer untuk menyimpan riwayat perubahan terbaru. Jika kapasitas penuh, data lama akan otomatis diganti dengan data baru sehingga penyimpanan lebih efisien.
