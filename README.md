# Pengenalan Wajah Menggunakan SVM dan Ekstraksi Fitur dari Citra Berwarna

## Deskripsi Proyek

Proyek ini bertujuan untuk membangun sistem pengenalan wajah menggunakan algoritma Support Vector Machine (SVM) dan teknik ekstraksi fitur dari citra berwarna. SVM dipilih karena kemampuannya dalam klasifikasi dan generalisasi yang baik, sedangkan ekstraksi fitur bertujuan untuk mendapatkan representasi numerik yang efektif dari wajah.

## Fitur Utama

- **Ekstraksi Fitur:**
  - Menggunakan metode ekstraksi fitur seperti Histogram of Oriented Gradients (HOG), Local Binary Patterns (LBP), atau metode lainnya.
  - Mengubah citra wajah berwarna menjadi representasi fitur yang sesuai untuk model SVM.
- **Pelatihan Model SVM:**
  - Melatih model SVM menggunakan dataset wajah yang telah dilabeli.
  - Optimasi parameter SVM untuk meningkatkan akurasi pengenalan.
- **Pengenalan Wajah:**
  - Menerima citra wajah baru sebagai input.
  - Melakukan ekstraksi fitur pada citra input.
  - Menggunakan model SVM yang telah dilatih untuk mengidentifikasi identitas wajah.
