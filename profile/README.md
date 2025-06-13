# BOROBUDUR TALES | DBS X DICODING CODING CAMP 2025

---

## 💎 **Deskripsi Proyek** 
Borobudur Tales adalah sebuah platform edukatif digital yang dikembangkan untuk membantu wisatawan memahami cerita di balik relief Candi Borobudur dengan cara mandiri dan interaktif. Proyek ini hadir karena adanya permasalahan wisatawan yang berkunjung hanya asyik berswafoto tanpa memahami nilai sejarah dan budaya dari candi tersebut. Dirancang untuk siapa saja, baik pelajar, wisatawan lokal maupun mancanegara, aplikasi ini memungkinkan pengguna mengunggah gambar relief untuk mendapatkan penjelasan otomatis tentang maknanya melalui teknologi Machine Learning berbasis ResNet50 dan Content-Based Image Retrieval. Borobudur Tales dikembangkan oleh tim Capstone project CC25-CF247 dalam program inovasi teknologi budaya, sebagai upaya nyata pelestarian warisan sejarah di era digital

![image](https://github.com/user-attachments/assets/728dcef0-ff30-4e45-84fa-79c64f2031e7)

## 🎥**Demo**
[Video Demo Website Borobudur Tales](https://drive.google.com/file/d/1uY6jDRPIOldnMpexxEdgvkDmDdap-vNP/view?usp=sharing)

---

## 🚀 **Fitur Utama** 
1. **User**
    - Explore : Menyajikan **sejarah singkat Candi Borobudur** untuk memperkenalkan latar belakang, struktur, dan filosofi candi kepada pengguna.
    - Pustaka : Berisi **kumpulan cerita-cerita relief** yang terdiri dari 160 data. Pengguna dapat membaca dan mempelajari kisah-kisah yang tergambar pada relief candi.
    - Scan Relief : Fitur interaktif yang memungkinkan pengguna untuk **mengunggah atau memindai gambar relief**, kemudian sistem akan menampilkan jenis relief dan isi cerita yang terkandung di dalamnya.
2. **Admin**
   - Data Cerita : Fitur yang memungkinkan admin untuk mengelola **database cerita-cerita relief**, termasuk menambah, mengubah, atau menghapus cerita.

---

## 👥 **Role**

| **👩‍💻Name**                          | **🆔Student ID**     | **🎓Learning Path**    | **Contribution/Task**                                                                                                                                                                                |
|-----------------------------------|--------------------|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Reza Nagita Nurhazizah**   | MC179D5X1628        | Machine Learning     | Mengumpulkan dan membersihkan dataset, Mengelompokkan gambar berdasarkan narasi yang sesuai, membangun model dengan ResNet50, serta mengintegrasikan hasil prediksi dengan narasi cerita relief.  |
| **Muhammad Solihin**               | MC223D5Y1069       | Machine Learning     | Mengumpulkan dataset, Mencari referensi dari dataset,Mengelompokkan gambar berdasarkan narasi yang sesuai, deploy model menggunakan huggingface|
| **Andreas Adi Prasetyo**      | MC615D5Y1588       | Machine Learning     | Mengumpulkan dataset, Mengelompokkan gambar berdasarkan narasi yang sesuai, Visualisasi dan evaluasi model, membuat API ML menggunakan Fast API|
| **Siti Fatimah Nur Cahya**          | FC179D5X2260       | FEBE   | Membuat database, input data cerita dan gambar, membuat tampilan halaman (User: Explore dan Detail Pustaka; Admin : Dashboard dan Daftar Pengguna) |
| **Maya Putri Nur Fajri**           | FC613D5X0961       | FEBE   | Membuat Rest API, membuat tampilan halaman (User: Daftar, Masuk, Unggah Gambar; Admin : Dashboard dan data cerita)|
| **Firdy Dwi Aryani**                 | FC223D5X0935       | FEBE     | Integrasi AI/ML ke Back-End, membuat tampilan halaman (User:  Beranda, Pustaka; Admin : Dashboard, riwayat pengguna, profil) |

---

## 🕵️‍♂️ **Informasi Repository**

1. 🧩 **Front_End Back_End** 

| Teknologi/Library      | Fungsi                                                             |
| ---------------------- | ------------------------------------------------------------------ |
| **Laravel**            | Framework utama untuk backend, routing, dan logika aplikasi        |
| **Tailwind CSS**       | Library CSS utility-first untuk styling antarmuka secara responsif |
| **Laravel Breeze**     | Starter kit untuk fitur autentikasi dasar (login & register)       |
| **Auth Sanctum**       | Autentikasi token berbasis API untuk keamanan akses pengguna       |
| **RestAPI**            | Menghubungkan antarmuka pengguna dengan server                     |
| **MySQL**              | Database utama untuk menyimpan data pengguna, cerita, dan pustaka  |
| **Figma**              | Mendesain UI/UX aplikasi sebelum pengembangan                      |
| **Visual Studio Code** | Editor kode utama dalam proses pengembangan frontend dan backend   |

2. 🧩 **Machine Learning** Pengembangan AI
    [Repository ML](https://github.com/BorobudurTales/BorobudurTales-ML-Model)
                                                                     
| Teknologi/Library              | Fungsi                                                                             |
| ------------------------------ | ---------------------------------------------------------------------------------- |
| **TensorFlow**                 | Framework utama untuk membangun model deep learning                                |
| **ResNet50** (tanpa top layer) | Model pretrained CNN untuk ekstraksi ciri visual dari gambar relief                |
| **Cosine Similarity**          | Algoritma untuk menghitung tingkat kemiripan antar gambar berdasarkan vektor fitur |
| **Google Colab**               | Lingkungan cloud untuk pelatihan dan pengujian model ML                            |
| **FastAPI**                    | Web framework Python untuk membungkus model ML ke dalam API yang cepat dan ringan  |
| **H5 (.h5 file)**              | Format file untuk menyimpan fitur gambar dan metadata dalam proses retrieval       |
| **Hugging Face Spaces**        | Platform deployment agar API ML dapat diakses online oleh backend/frontend         |
