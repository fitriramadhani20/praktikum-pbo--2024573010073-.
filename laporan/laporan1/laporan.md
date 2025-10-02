# Laporan Modul 2: Dasar Pemrograman Java
**Mata Kuliah:** Praktikum Pemrograman Berorientasi Objek   
**Nama:** [Fitri Ramadhani]  
**NIM:** [2024573010073]  
**Kelas:** [Teknik Informatika 2E]

---

## 1. Abstrak
Laporan ini berisi pembahasan mengenai penggunaan variabel, input-output, struktur kontrol (if-else, switch, nested if), serta perulangan (for, while, do-while, nested loop) dalam bahasa pemrograman Java. Setiap program yang ditampilkan pada laporan menunjukkan contoh penerapan dasar pemrograman, seperti perhitungan aritmatika, penentuan kondisi, pengolahan input dari pengguna, hingga pembuatan pola dengan perulangan. Laporan juga dilengkapi dengan penjelasan alur program agar lebih mudah dipahami.

Tujuan Pembuatan Laporan

Tujuan dibuatnya laporan ini adalah:

1. Untuk memahami dasar-dasar pemrograman Java, mulai dari penggunaan variabel hingga struktur kontrol dan perulangan.

2. Sebagai latihan dalam menganalisis alur kerja program dan hasil output yang dihasilkan.

3. Untuk memenuhi tugas praktikum mata kuliah Pemrograman Dasar dan mendokumentasikan hasil percobaan secara sistematis.

4. Sebagai bahan referensi agar lebih mudah mempelajari kembali konsep dasar pemrograman Java di kemudian hari.

---
##  Praktikum
### Praktikum 1 - Variabel dan Tipe Data
#### Dasar Teori
Dalam pemrograman Java, variabel adalah suatu tempat penyimpanan data yang memiliki nama dan tipe data tertentu. Variabel berfungsi untuk menyimpan nilai yang dapat digunakan dan diolah dalam program.

#### Langkah Praktikum
1. Buka IDE/Editor Java → bisa pakai NetBeans, IntelliJ, atau Notepad++ dengan CMD.

2. Buat file baru dengan nama VariabelDemo.java.

3. Ketik program sesuai kode yang sudah disalin (isi program VariabelDemo).

4. Simpan file dengan nama yang sama (VariabelDemo.java).

5. Kompilasi program dengan perintah javac VariabelDemo.java (kalau pakai CMD) atau klik Run/Build di IDE.

6. Jalankan program dengan perintah java VariabelDemo atau tombol Run di IDE.

7. Amati hasil output yang muncul di layar.

#### Screenshoot Hasil
![](laporan/laporan1/gambar/VariabelDemo.png)

#### Analisa dan Pembahasan
Analisa:

1. public class VariabelDemo {
→ Mendefinisikan kelas utama bernama VariabelDemo. Nama kelas harus sama dengan nama file.

2. public static void main(String[] args) {
→ Method utama, tempat program mulai dijalankan.

3. int angka1 = 10;
→ Membuat variabel angka1 bertipe int (bilangan bulat) dengan nilai awal 10.

4. int angka2 = 20;
→ Membuat variabel angka2 bertipe int dengan nilai 20.

5. int jumlah = angka1 + angka2;
→ Variabel jumlah menyimpan hasil penjumlahan angka1 + angka2 (hasilnya 30).

6. System.out.println("Angka pertama: " + angka1);
→ Menampilkan teks dan nilai angka1. Output: Angka pertama: 10.

7. System.out.println("Angka kedua: " + angka2);
→ Menampilkan teks dan nilai angka2. Output: Angka kedua: 20.

8. System.out.println("Hasil penjumlahan: " + jumlah);
→ Menampilkan teks dan nilai hasil penjumlahan. Output: Hasil penjumlahan: 30.

Pembahasan:
Program ini bertujuan untuk memperkenalkan penggunaan variabel dalam Java.

 - Variabel adalah wadah untuk menyimpan data (dalam kasus ini, angka bulat int).

 - Dengan variabel, kita bisa melakukan operasi matematika seperti penjumlahan.

 - Program ini menampilkan hasil ke layar agar kita tahu nilai dari variabel yang sudah dihitung.

### Praktikum 2: Input, Output dan Scanner

#### Dasar Teori
 - Input adalah data yang dimasukkan user ke program, sedangkan Output adalah data yang ditampilkan program ke layar.

 - Di Java, output ditampilkan dengan System.out.print() atau System.out.println().

 - Input menggunakan kelas Scanner dari java.util, dengan metode seperti:

      - nextLine() untuk teks

      - nextInt() untuk bilangan bulat

 - Data input disimpan dalam variabel, lalu dapat diolah dan ditampilkan kembali.

 - Tujuan program ini adalah memperkenalkan interaksi dasar antara komputer dan pengguna melalui input-output sederhana.

#### Langkah Praktikum

1. Buka editor Java/IDE (misalnya NetBeans, IntelliJ, atau bisa juga pakai Notepad + CMD).

2. Buat file baru dengan nama InputOutputDemo.java.

3. Ketikkan kode program sesuai yang sudah kamu salin.

4. Simpan file dengan nama InputOutputDemo.java.

5. Kompilasi program

     - Jika pakai CMD: ketik javac InputOutputDemo.java.

     - Jika pakai IDE: klik tombol Build/Run.

6. Jalankan program

     - CMD: ketik java InputOutputDemo.

     - IDE: klik tombol Run.

7. Masukkan input sesuai instruksi di layar (nama dan umur).

8. Amati output yang muncul, yaitu sapaan berisi nama dan umur yang tadi dimasukkan.

#### Screenshoot Hasil
![](laporan/laporan1/gambar/inputoutputdemo.png)

#### Analisa dan Pembahasan

Analisa:
1. Program mengimpor Scanner untuk membaca input dari keyboard.

2. Di dalam main(), dibuat objek Scanner bernama input.

3. Program menampilkan teks untuk meminta nama lalu menyimpannya dalam variabel nama.

4. Program menampilkan teks untuk meminta umur lalu menyimpannya dalam variabel umur.

5. Program mencetak output berupa sapaan yang menggabungkan nama dan umur.

Pembahasan:

 - Program ini memperlihatkan cara mengambil input dari user dan menampilkannya kembali ke layar.

 - Variabel digunakan untuk menyimpan data yang dimasukkan user.

 - Output berupa teks yang sudah digabung dengan data input, sehingga program terlihat interaktif.

### Praktikum 3: Struktur Control: Percabangan

### Dasar Teori
Percabangan adalah struktur kontrol untuk mengambil keputusan dalam program.

 - Program akan memilih perintah tertentu berdasarkan kondisi (benar/salah).

 - Jenis percabangan di Java:

     - if → satu kondisi.

     - if...else → dua kondisi (benar/salah).

     - if...else if...else → banyak kondisi.

     - switch → pilihan kondisi berdasarkan nilai tertentu.
 - Percabangan membuat program lebih dinamis dan interaktif.

### Langkah Praktikum
1. Buka editor Java/IDE (misalnya NetBeans, IntelliJ, atau Notepad + CMD).

2. Buat file baru dengan nama GradeDemo.java.

3. Ketikkan kode program GradeDemo sesuai yang sudah kamu salin.

4. Simpan file dengan nama GradeDemo.java.

5. Kompilasi program

     - CMD: ketik javac GradeDemo.java.

     - IDE: klik Build/Compile.

6. Jalankan program

     - CMD: ketik java GradeDemo.
     - IDE: klik Run.

7. Masukkan nilai sesuai instruksi yang diminta program.

8. Amati hasil output berupa grade (A, B, C, dll.) yang ditampilkan sesuai nilai yang dimasukkan.

### Screenshoot Hasil
![](laporan/laporan1/gambar/GradeDemo.png)

### Analisa dan Pembahasan
1. Program mengimpor Scanner untuk membaca input dari user.

2. Objek Scanner dibuat untuk menerima nilai (angka) dari keyboard.

3. User diminta memasukkan nilai angka (misalnya 80, 65, 50, dll.).

4. Program menggunakan percabangan if–else if–else untuk mengecek:

     - Jika nilai ≥ 80 → Grade A

     - Jika nilai ≥ 70 → Grade B

     - Jika nilai ≥ 60 → Grade C

     - Jika nilai ≥ 50 → Grade D

     - Jika di bawah 50 → Grade E

5. Hasil grade ditampilkan ke layar dengan System.out.println().

Pembahasan:

Program GradeDemo menggunakan percabangan if–else if–else untuk menentukan grade berdasarkan nilai yang dimasukkan user. Nilai angka diklasifikasikan menjadi A–E, lalu hasilnya ditampilkan. Program ini menunjukkan cara pengambilan keputusan sederhana dengan percabangan.

### Langkah Praktikum MenuDemo

1. Buka editor Java/IDE (NetBeans, IntelliJ, atau Notepad + CMD).

2. Buat file baru dengan nama MenuDemo.java.

3. Ketikkan kode program MenuDemo sesuai yang sudah kamu salin.

4. Simpan file dengan nama MenuDemo.java.

5. Kompilasi program

     - CMD: ketik javac MenuDemo.java.

     - IDE: klik Build/Compile.

6. Jalankan program

     - CMD: ketik java MenuDemo.

     - IDE: klik Run.

7. Pilih menu dengan memasukkan angka sesuai instruksi yang tampil (misalnya 1 untuk pilihan pertama, 2 untuk pilihan kedua, dst).

8. Amati hasil output dari menu yang dipilih.

#### Screenshoot Hasil
![](laporan/laporan1/gambar/MenuDemo.png)

### Analisa dan Pembahasan
Analisa:

1. Fungsi Program
    Program ini adalah program menu sederhana untuk menghitung luas bangun datar:

     - Persegi

     - Lingkaran

     - Segitiga

     - Atau keluar dari program

2. Input

     - User diminta memilih menu (1–4).

     - Jika memilih salah satu perhitungan, user diminta memasukkan nilai (sisi, jari-jari, alas, tinggi).

3. Proses

     - Menggunakan switch-case untuk menentukan perhitungan berdasarkan pilihan user.

     - Rumus yang dipakai:

        - Persegi → sisi × sisi

        - Lingkaran → π × r²

        - Segitiga → ½ × alas × tinggi

4. Output

    - Menampilkan hasil luas sesuai bangun datar yang dipilih.

    - Jika user memilih 4 → keluar dengan pesan “Terima kasih!”.

    - Jika user memasukkan pilihan selain 1–4 → muncul pesan “Pilihan tidak valid!”.

Pembahasan:

Program MenuDemo menggunakan switch-case untuk membuat menu perhitungan luas bangun datar. User memilih opsi, lalu memasukkan nilai sesuai kebutuhan, dan program menghitung serta menampilkan hasilnya. Jika memilih keluar, muncul pesan penutup, sedangkan input yang salah akan menampilkan pesan “Pilihan tidak valid”. Program ini menunjukkan penggunaan switch-case agar kode lebih sederhana dan mudah dipahami.

### Langkah Praktikum NestedIfDemo.java

1. Buka editor Java dan buat file NestedIfDemo.java.

2. Import Scanner untuk input.

3. Deklarasikan class NestedIfDemo dan method main.

4. Buat objek Scanner untuk baca nilai dari user.

5. Simpan input ke variabel nilai.

6. Gunakan nested if untuk menentukan grade:

     - ≥ 80 → A

     - ≥ 70 → B

     - ≥ 60 → C

     - < 60 → D

7. Tampilkan hasil ke layar.

8. Simpan, compile (javac), dan jalankan (java).

#### Screenshoot Hasil
![](laporan/laporan1/gambar/NestedifDemo.png)

### Analisa dan Pembahasan

Analisa:
 - Program meminta input umur dari user.

 - Menggunakan nested if-else untuk mengelompokkan umur:

     - 0–2 → Bayi

     - 3–5 → Balita

     - 6–12 → Anak-anak

     - 13–17 → Remaja

     - 18–59 → Dewasa

     - ≥ 60 → Lansia

 - Jika umur ≤ 0 → muncul pesan "Umur tidak valid!".

Pembahasan:

Nested if digunakan untuk membandingkan satu variabel dengan beberapa kondisi berurutan. Program ini menunjukkan cara pengelompokan data (umur) ke dalam kategori tertentu dengan percabangan bersarang.

### Praktikum 4: Struktur Control: Perulangan

### Dasar Teori
Perulangan adalah proses menjalankan perintah berulang kali selama kondisi terpenuhi.
Jenis perulangan di Java:

  - for → jumlah perulangan sudah pasti.

  - while → perulangan berdasarkan kondisi.

  - do...while → perulangan minimal dijalankan sekali.

Fungsinya untuk menghemat kode dan mempermudah pengolahan data berulang.

 ### Langkah Praktikum
1. Buka editor Java dan buat file DoWhileDemo.java.

2. Deklarasikan class dan method main.

3. Buat variabel awal (misalnya angka).

4. Gunakan struktur do...while untuk mengulang perintah.

5. Simpan file lalu compile.

6. Jalankan program.

7. Amati hasil perulangan, perintah dijalankan minimal sekali.

#### Screenshoot Hasil ForLoopDemo.java
![](laporan/laporan1/gambar/Forloopdemo.png)

### Analisa dan Pembahasan

Analisa:

Program menggunakan perulangan do...while.

Variabel diberi nilai awal.

Bagian do menjalankan perintah terlebih dahulu.

Setelah itu kondisi while dicek → jika benar, perulangan berlanjut; jika salah, perulangan berhenti.

Pembahasan:

Program ini menunjukkan bahwa do...while selalu mengeksekusi perintah minimal satu kali, meskipun kondisi salah.
Hal ini berbeda dengan while, yang akan langsung berhenti jika kondisi awal salah.

### Langkah Praktikum

1. Buka editor Java dan buat file WhileLoopDemo.java.

2. Deklarasikan class dan method main.

3. Siapkan variabel awal sebagai penghitung.

4. Gunakan struktur while loop untuk mengulang perintah selama kondisi terpenuhi.

5. Simpan file dengan nama WhileLoopDemo.java.

6. Compile program dengan javac.

7. Jalankan program dengan java.

8. Amati hasil perulangan yang tampil di layar.

#### Screenshoot Hasil ForLoopDemo.java
![](laporan/laporan1/gambar/whileloopdemo.png)

### Analisa dan Pembahasan

Analisa:

 - Program menggunakan struktur while loop.

 - Variabel penghitung diberi nilai awal.

 - Kondisi diperiksa di awal → jika benar, perulangan dijalankan; jika salah, perulangan langsung berhenti.

 - Setiap perulangan, nilai ditampilkan lalu variabel ditambah.

Pembahasan:

Program ini menunjukkan cara kerja while loop, yaitu perintah diulang selama kondisi masih benar. Jika kondisi awal salah, perulangan tidak akan dijalankan sama sekali.
Output berupa urutan nilai sesuai kondisi yang diberikan.

### Langkah Praktikum NestedLoopDemo.java
1. Buka editor Java dan buat file baru NestedLoopDemo.java.

2. Deklarasikan class dan method main.

3. Siapkan dua variabel sebagai penghitung (misalnya untuk baris dan kolom).

4. Gunakan perulangan for di dalam for (nested loop) untuk mencetak pola atau tabel.

5. Simpan file dengan nama NestedLoopDemo.java.

6. Compile program dengan javac NestedLoopDemo.java.

7. Jalankan program dengan java NestedLoopDemo.

8. Amati hasil output berupa pola yang terbentuk dari nested loop.

#### Screenshoot Hasil NestedLoopDemo.java
![](laporan/laporan1/gambar/Nestedloopdemo.png)

### Analisa dan Pembahasan

Analisa:
Program NestedLoopDemo menggunakan nested loop (perulangan bersarang), di mana ada loop luar untuk mengatur baris dan loop dalam untuk mengatur isi tiap baris. Biasanya dipakai untuk mencetak pola (bintang/angka) atau mengakses data 2 dimensi.

Pembahasan:

 - Loop luar = jumlah baris.

 - Loop dalam = isi tiap baris.

 - Hasilnya bisa berupa pola segitiga, kotak, atau tabel.

---

## 3. Kesimpulan

Berdasarkan rangkaian praktikum yang telah dilakukan, dapat disimpulkan bahwa:

1. Variabel dan tipe data menjadi dasar penting dalam pemrograman Java karena berfungsi untuk menyimpan serta mengolah data.

2. Input-output memungkinkan adanya interaksi antara program dan pengguna, sehingga program dapat menerima masukan dan menampilkan hasil secara dinamis.

3. Struktur kontrol percabangan (if-else, switch, nested if) digunakan untuk menentukan alur program berdasarkan kondisi tertentu, sehingga program dapat mengambil keputusan yang tepat.

4. Struktur kontrol perulangan (for, while, do-while, nested loop) mempermudah penulisan kode yang membutuhkan pengulangan, serta dapat digunakan untuk membuat pola maupun mengolah data secara berulang.

5. Setiap konsep saling berkaitan dan menjadi pondasi utama untuk memahami serta mengembangkan program Java yang lebih kompleks di kemudian hari.

---

## 5. Referensi
1. Java™ Tutorials — https://docs.oracle.com/javase/tutorial/
2. Wahana Komputer. Pemrograman Java untuk Pemula. ANDI, 2019.
3. GeeksforGeeks: Java Programming Basics — https://www.geeksforgeeks.org/java/
4. 
---
