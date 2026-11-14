# Milestone-SMP-Q8-Python


# Python Milestone Projects

## 1. Word Frequency Analyzer

**Materi:** File Handling + String + Dictionary

### Tujuan
Membuat fungsi yang bisa membaca file `.txt`, menghitung jumlah seluruh kata, dan menghitung jumlah kata yang berbeda.

### Requirements
Program harus melakukan beberapa hal:

1. Membuka file `medic_journal.txt`.
2. Membaca seluruh isi file.
3. Memisahkan teks menjadi kata-kata berdasarkan spasi.
4. Menghitung total semua kata.
5. Menghitung jumlah kata unik (kata yang berbeda).
6. Mengabaikan perbedaan huruf besar dan kecil.

---

## 2. Report Card Generator

**Materi:** File Handling + CSV + Dictionary + List

### Tujuan
Membuat program yang membaca nilai siswa dari file `.csv`, menghitung nilai rata-rata, kemudian menentukan grade masing-masing siswa.

### Apa yang harus dilakukan?

Program akan membaca file `student_grades.csv`.

**Isi file:**

```csv
Name,Maths,Science,English
Alice,85,90,92
Bob,78,75,80
Charlie,60,65,70
```

Setiap baris berisi:
- Nama siswa
- Nilai Maths
- Nilai Science
- Nilai English

Program harus menghitung rata-rata nilai ketiga mata pelajaran tersebut.

### Bagaimana bentuk dictionary-nya?

Program harus mengembalikan dictionary dengan:
- **Key** = nama siswa.
- **Value** = list yang berisi rata-rata nilai dan grade.

---

## 3. Common and Unique Elements

**Materi:** List + Set + Looping + Conditional

### Tujuan
Membuat fungsi yang membandingkan dua list angka dan mencari angka yang sama maupun angka yang hanya muncul di salah satu list.

### Apa yang harus dilakukan?

Misalnya terdapat dua list:

```python
list1 = [1, 2, 3, 4, 5]
list2 = [4, 5, 6, 7, 8]
```

Program harus mencari dua jenis data:

### 1. Common Elements

Angka yang terdapat di kedua list.

Dari contoh di atas:
- Angka 4 terdapat di list1 dan list2.
- Angka 5 terdapat di list1 dan list2.

**Hasilnya:**

```python
[4, 5]
```

### 2. Unique Elements

Angka yang hanya terdapat di salah satu list, bukan keduanya.

Dari contoh di atas:
- Angka 1, 2, 3 hanya ada di list1.
- Angka 6, 7, 8 hanya ada di list2.

**Hasilnya:**

```python
{1, 2, 3, 6, 7, 8}
```

### Mengapa menggunakan `{}`?

Karena hasil kedua harus berupa Set, bukan List.

Set merupakan tipe data Python yang menyimpan elemen unik dan tidak mempertahankan urutan tertentu.

---

## 4. Debugging Test: War Deaths Chart Generator

**Materi:** Debugging + File Handling + Pygal

### Tujuan
Memperbaiki kode Python yang sudah diberikan karena terdapat beberapa kesalahan sehingga program tidak dapat berjalan sebagaimana mestinya.

Berbeda dengan tiga soal sebelumnya, di sini siswa tidak diminta membuat program dari awal.

Siswa diberikan kode yang belum benar dan harus menemukan serta memperbaiki kesalahannya.

### Apa yang harus dilakukan?

Program tersebut memiliki tujuan untuk:

1. Membaca file `war_deaths.txt`.
2. Mengambil nama perang dan jumlah kematian dari setiap baris.
3. Mengubah jumlah kematian menjadi integer.
4. Memasukkan data ke dalam grafik menggunakan library Pygal.
5. Menghasilkan grafik dalam format SVG.

### Contoh isi file

```text
World War I: 16500000
World War II: 70000000
Korean War: 2500000
Vietnam War: 3000000
Gulf War: 294000
```

Program harus memahami bahwa:
- `World War I` adalah nama perang.
- `16500000` adalah jumlah kematian.

Kemudian data tersebut dimasukkan ke dalam bar chart.


----------------------------------------------------------------------------------------


### 1. Word Frequency Analyzer

"Halo semuanya! Pada project ini, saya membuat program Word Frequency Analyzer menggunakan Python. Program ini berfungsi untuk membaca sebuah file teks, kemudian menghitung jumlah seluruh kata dan jumlah kata unik atau kata yang tidak berulang. Saya menggunakan function, file handling, string, dan set untuk mengolah data teks tersebut."

### 2. Report Card Generator

"Pada project kedua, saya membuat Report Card Generator. Program ini membaca data nama dan nilai siswa dari file CSV. Kemudian, program menghitung nilai rata-rata dari tiga mata pelajaran, yaitu Maths, Science, dan English, lalu menentukan grade berdasarkan hasil rata-rata tersebut. Saya menggunakan function, looping, dictionary, dan conditional statements."

### 3. Common and Unique Elements

"Pada project ketiga, saya membuat function untuk membandingkan dua list angka. Program ini mencari angka yang muncul di kedua list dan angka yang hanya muncul di salah satu list. Untuk menyelesaikannya, saya menggunakan konsep list, set, dan operasi perbandingan data."

### 4. War Deaths Chart Generator

"Pada project terakhir, saya mengerjakan sebuah tantangan debugging bernama War Deaths Chart Generator. Saya diberikan kode Python yang memiliki beberapa kesalahan, kemudian saya harus menemukan dan memperbaiki kesalahan tersebut. Program ini membaca data nama perang dan jumlah kematian dari file teks, kemudian menggunakan library Pygal untuk membuat grafik batang atau bar chart."

### Penutup Presentasi

"Melalui keempat project ini, saya belajar lebih banyak tentang penggunaan function, pengolahan file, dictionary, list, set, serta debugging. Saya juga belajar bagaimana mengolah data dan menampilkannya dalam bentuk grafik menggunakan Python. Terima kasih!"
