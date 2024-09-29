# Heatmap Faktor Korelasi Diabetes

Data yang digunakan dalam Visualisasi:
[diabetes_null.csv](https://github.com/user-attachments/files/17179713/diabetes_null.csv)

Deskripsi Dataset:
- Di dataset ini terdapat beberapa atribut seperti:
  
  - pregnancies: jumlah kehamilan
  - glucose: level glukosa
  - blood pressure : pengukuran tekanan darah
  - skin thickness: ketebalan kulit
  - insulin : mengukur level insulin
  - BMI: body max index
  - diabetes pedigree function: riwayat diabetes
  - age: umut
  - outcome: hasil biner seorang dinyatakan diabetes atau tidak 

1. Tujuan memakai dataset ini: untuk merepresentasikan visual dari faktor-faktor kunci yang menyebabkan diabetes (terutama Glukosa, BMI, dan Usia) dan korelasinya dengan kejadian diabetes (Outcome).
2. User: seorang pakar kesehatan, data analyst, atau peneliti yang tertarik untuk meneliti faktor diabetes.
3. fungsi: agar user dapat mengidentifikasi pola antara faktor-faktor yang memperngaruhi kejadian diabetes seperti kadar glukosa, BMI, dll.
4. Tone: dalam visualisasi ini harus informatif, jelas, tidak ambigu, serta bernada netral dan profesional.

- Berikut kode untuk membuat heatmap dari dataset:
![Screenshot 2024-09-29 231011](https://github.com/user-attachments/assets/91818f04-bc44-4478-883e-22bcc7c595d4)

Sehingga menghasilkan Heatmap sebagai berikut:
![Screenshot 2024-09-29 223222](https://github.com/user-attachments/assets/8c8b0fab-b1bf-4fdf-856b-0adad7cba320)

Cara membaca Heatmap ini:
- warna: heatmap akan mengikuti skala dari merah ke biru (negatif) dan (positif) dengan nuansa lebih terang mendekati 0.
- kuantifikasi: setiap sel akan menujukkan nilai korelasi antara dua variabel. jika nilai mendekati 1 maka terdapat korelasi positif yang kuat, artinya ketika suatu variabel meningkat, maka yang lain akan juga cenderung meningkat. Begitu pula sebaliknya untuk yang mendekati -1. Jika mendekati 0 maka akan menunjukkan lemahnya hubungan linier yang kuat antara dua variabel.
- Titik Penting: fokuslah pada sel yang mendekati 1 atau -1. Dikarenakan hubungan antara dua variabel ini signifikan.

  * Contoh dari heatmap ini:
    - BMI vs Outcome: kedua variabel ini menujukkan korelasi positif yang signifikan artinya BMI yang meningkat itu berpengaruh signifikan terhadap meningkatnya resiko diabetes.

  * Contoh Insight yang dapat diambil:
    - hubungan variabel glucose dan outcome menunjukkan bahwa glukosa adalah indikator penting untuk gejala diabetes.
