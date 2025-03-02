# 1️⃣ Pengenalan OOP

## 🔍 Apa itu OOP?
OOP (Object-Oriented Programming) adalah paradigma pemrograman yang berorientasi pada objek. Dalam OOP, program dibangun menggunakan objek yang memiliki atribut (data) dan metode (fungsi).

### 🎯 Contoh dalam kehidupan sehari-hari:
Bayangkan sebuah 🚗 mobil. Mobil memiliki **atribut** seperti warna, merk, dan kecepatan maksimum. Mobil juga memiliki **metode** seperti menghidupkan mesin, mengerem, dan mempercepat. Dalam OOP, mobil ini bisa direpresentasikan sebagai sebuah objek dari class `Mobil`.

## 🏗️ Konsep Class dan Object
- **Class** adalah blueprint atau template untuk membuat objek.
- **Object** adalah instance dari sebuah class yang memiliki atribut dan metode.

---

# 2️⃣ Membuat Class dan Object

## 🏛️ Contoh Class Sederhana
Sebuah class dapat dibuat dengan kata kunci `class`, dan objek dibuat dengan memanggil class tersebut.

## 📌 Menambahkan Atribut dan Metode
- **Atribut** adalah variabel yang melekat pada objek.
- **Metode** adalah fungsi yang didefinisikan di dalam class untuk memberikan perilaku kepada objek.

### 🎓 Contoh dalam kehidupan sehari-hari:
Misalnya, kita membuat class `Mahasiswa`. 🎓 Mahasiswa memiliki atribut seperti nama dan NIM serta metode seperti belajar dan mengikuti ujian.

---

# 3️⃣ Encapsulation (Enkapsulasi)

## 🔒 Public, Private, dan Protected Attributes
- **Public** ✅: Bisa diakses dari luar class.
- **Protected** 🛑: Ditandai dengan `_` dan sebaiknya tidak diakses langsung dari luar class.
- **Private** 🚫: Ditandai dengan `__` dan tidak bisa diakses langsung dari luar class.

## 🔑 Getter dan Setter
Digunakan untuk mengakses dan mengubah atribut private dengan cara yang aman.

### 🏢 Contoh dalam kehidupan sehari-hari:
Seorang karyawan memiliki 💰 gaji yang tidak boleh langsung diubah oleh siapa pun selain pihak HRD. Dalam OOP, atribut `gaji` bisa dibuat private, dan perubahan gaji hanya bisa dilakukan melalui metode yang telah disediakan.

---

# 4️⃣ Inheritance (Pewarisan)

## 🧬 Pewarisan Antar Kelas
Inheritance memungkinkan sebuah class (child) mewarisi atribut dan metode dari class lain (parent).

## 🔄 Override Method
Child class dapat mengganti (override) metode dari parent class untuk memberikan implementasi baru.

### 🚘 Contoh dalam kehidupan sehari-hari:
Sebuah **kendaraan** bisa memiliki banyak jenis, seperti **mobil 🚗 dan motor 🏍️**. Mobil dan motor sama-sama memiliki atribut seperti warna dan metode seperti bergerak. Namun, mobil bisa memiliki metode tambahan seperti menyalakan AC ❄️, sedangkan motor tidak.

---

# 5️⃣ Polymorphism (Polimorfisme)

## 🔁 Method Overriding
Subclass dapat memiliki metode yang sama dengan superclass tetapi dengan implementasi berbeda.

## 🔣 Method Overloading (Menggunakan *args & **kwargs)
Method overloading di Python bisa dilakukan dengan menggunakan *args dan **kwargs untuk menangani jumlah parameter yang berbeda.

### 👩‍🏫 Contoh dalam kehidupan sehari-hari:
Seorang **guru** 📚 mengajar berbagai mata pelajaran. Jika ia mengajar **matematika ➗**, ia akan menggunakan metode yang berbeda dibanding saat mengajar **sejarah 📜**. Ini adalah contoh polimorfisme di mana satu objek (`Guru`) bisa memiliki perilaku yang berbeda tergantung pada situasi.

---

# 6️⃣ Abstraction (Abstraksi)

## 🏛️ Kelas Abstrak dengan ABC (Abstract Base Class)
Kelas abstrak adalah kelas yang tidak bisa diinstansiasi dan hanya berfungsi sebagai kerangka bagi kelas turunannya. Digunakan dengan modul `abc`.

### 📺 Contoh dalam kehidupan sehari-hari:
Sebuah **perangkat elektronik** seperti **TV 📺 dan radio 📻** memiliki metode dasar seperti **menyala dan mati**, tetapi cara kerjanya berbeda. Dalam OOP, kita bisa membuat class abstrak `PerangkatElektronik` yang hanya mendefinisikan metode `nyalakan()` dan `matikan()`, lalu setiap perangkat seperti TV dan radio mengimplementasikan metode tersebut dengan caranya masing-masing.

---

# 7️⃣ Menggunakan __init__ (Constructor) dan __str__ (String Representation)

## ⚙️ Constructor (`__init__`)
Metode ini digunakan untuk menginisialisasi objek saat pertama kali dibuat.

## 📝 String Representation (`__str__`)
Metode ini digunakan untuk memberikan representasi string yang mudah dibaca ketika objek dicetak.

### 🧑‍💻 Contoh dalam kehidupan sehari-hari:
Ketika seseorang mendaftar ke dalam sebuah sistem, sistem akan langsung mengisi data dasar mereka seperti **nama dan tanggal lahir 📆** menggunakan constructor `__init__`. Jika kita ingin mencetak informasi pengguna tersebut, kita bisa menggunakan metode `__str__` agar data terlihat lebih rapi.


## 📚 **Referensi**  
1. Lutz, M. (2013). *Learning Python (5th Edition)*. O'Reilly Media.  
2. Sweigart, A. (2020). *Automate the Boring Stuff with Python (2nd Edition)*. No Starch Press.  
3. Beazley, D., & Jones, B. (2013). *Python Cookbook (3rd Edition)*. O'Reilly Media.  
4. Downey, A. B. (2012). *Think Python: How to Think Like a Computer Scientist*. O'Reilly Media.  
5. Grinberg, M. (2018). *Flask Web Development (2nd Edition)*. O'Reilly Media.  
6. Official Python Documentation. (2024). *Object-Oriented Programming in Python*. Diakses dari [https://docs.python.org/3/tutorial/classes.html](https://docs.python.org/3/tutorial/classes.html).  
7. GeeksforGeeks. (2024). *Python Object-Oriented Programming*. Diakses dari [https://www.geeksforgeeks.org/python-oops-concepts/](https://www.geeksforgeeks.org/python-oops-concepts/).  
