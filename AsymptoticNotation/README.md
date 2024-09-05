# Asymptotic Notation

Asymptotic Notation adalah penulisan fungsi untuk mempelajari suatu algoritma terhadap input atau masukan yang diberikan. Contoh kasus pada Bubble Sort di mana susunan input sudah diurutkan dengan waktu yang diperlukan yaitu linear (atau kasus terbaik). Tetapi, ketika array input dalam kondisi terbalik, algoritma membutuhkan waktu maksimal untuk mengurutkan elemen yaitu kasus terburuk.

Jenis-jenis:

<ol>
  <li>Big-O (O)</li>
  <p>Big-O menunjukan batas waktu berjalankan suatu algoritma, sehingga memberikan kompleksitas terburuk suatu algoritma. Terburuk yang dimaksud yaitu tidak mungkin dieksekusi dengan kompleksitas waktu lebih.
  Contoh: Quick Sort kasus terburuknya adalah O(n^2) yaitu terjadi elemen sudah hampir terurutkan (yang merupakan bilangan terbesar/terkecil).</p>
  <li>Big-Omega (Ω)</li>
  <p>Big-Omega menunjukan batas bawah dalam waktu berjalankan suatu algoritma, sehingga memberikan kompleksitas terbaik suatu algoritma. Terbaik yang dimaksud yaitu tidak mungkin dieksekusi dengan kompleksitas waktu kurang.
  Contoh: Insertion Sort, kasus terbaiknya adalah &omega;(1). Karena sudah terurutkan secara keseluruhan.</p>
  <li>Big-Theta (Θ)</li>
  <p>Big-Theta menunjukan batas atas dan bawah dalam waktu berjalankan suatu algoritma, sehingga memberikan kompleksitas rata-rata suatu algoritma. 
  Contoh: Quick Sort kasus rata-rata yaitu &theta;(n ^a log n). A bukan merupakan bilangan bulat dan nilainya memdekati 2. Untuk menganalisis average case dari quick sort ini dapat dilakukan partisi berupa rasio.</p>
</ol>

# Referensi

["Programiz, 04 September 2024"](https://www.programiz.com/dsa/asymptotic-notations)

["'Asymptotic Notation, Best Case, Average Case, dan Worst Case', 04 September 2024 di Medium"](https://medium.com/@atb1161/asymptotic-notation-best-case-average-case-dan-worst-case-2457e579d9d)
