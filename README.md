# Lab2Web
Assalamualaikum, Ini adalah pratikum website saya untuk memenuhi tugas dalam mata kuliah Pemrograman Web

1. [MEMBUAT DOKUMEN] Ini adalah tampilan codingan awal untuk membuat dokumen HTML dengan menggunakan style css

   ![Screenshot (174)](https://user-images.githubusercontent.com/59770620/113690636-d46d0300-96f5-11eb-88e7-a578f55a0457.png)
  
2. Hasil/Tampilan ketika dijalankan dibrowser, maka terlihat adanya judul pada elemen head, judul pada heading 1, hyperlink dll pada bagian elemen body

   ![Screenshot (175)](https://user-images.githubusercontent.com/59770620/113690647-d8008a00-96f5-11eb-812e-139cee973f54.png)

3. [Mendeklarasikan CSS Internal] Ini adalah tampilan codingan jika ditambahkan deklarasi CSS internal pada bagian head dokumen dengan menambahkan property dan nilai dalam          elemenn body, header, h1 dan hi

   ![Screenshot (176)](https://user-images.githubusercontent.com/59770620/113690651-d931b700-96f5-11eb-9389-e13da8859da8.png)

4. Hasil/Tampilan ketika dijalankan dibrowser, maka hasilnya terlihat dokumen tersebut sudah terdeklarasikan pada bagian elemen body, header, dan heading

   ![Screenshot (177)](https://user-images.githubusercontent.com/59770620/113690659-d9ca4d80-96f5-11eb-9a01-f80cd3535833.png)

5. [Menambahkan Inline CSS] Ini adalah tampilan codingan jika ditambahkan deklarasi inline CSS pada tag p seperti berikut.

   ![Screenshot (178)](https://user-images.githubusercontent.com/59770620/113690664-dafb7a80-96f5-11eb-99ca-a3872087821b.png)

6. Hasil/Tampilan ketika dijalankan dibrowser, maka terlihat adanya perubahan warna text pada paragraf dan rata text menjadi rata tengah dengan menambahkan property text-align      nilai rata tengah, dan property color nilai warna abu-abu.

   ![Screenshot (179)](https://user-images.githubusercontent.com/59770620/113690666-db941100-96f5-11eb-991b-3d4dfd486b6f.png)

7. [Membuat CSS Eksternal] Ini adalah tampilan codingan jika ditambahkan deklarasi CSS dengan membuat file baru untuk CSS Eksternal dan menambahkan tag link pada bagian elemen      head didokumen HTML

   ![Screenshot (180)](https://user-images.githubusercontent.com/59770620/113690670-dcc53e00-96f5-11eb-82ef-c32b7bf8ad08.png)

8. Hasil/Tampilan ketika dijalankan dibrowser, maka terlihat perubahannya link tersebut menajadi berwarna, menandakan bahwa link tersebut sudah terdeklarasikan pada file CSS

   ![Screenshot (181)](https://user-images.githubusercontent.com/59770620/113690673-dd5dd480-96f5-11eb-9fc4-26f69a056b54.png)

9. [Menambahkan CSS Selector] Ini adalah tampilan codingan jika ditambahkan CSS Selector menggunakan ID dan Class Selector pada file CSS eksternal

   ![Screenshot (182)](https://user-images.githubusercontent.com/59770620/113690680-de8f0180-96f5-11eb-9a18-f720a443c75c.png)

10. Hasil/Tampilan ketika dijalankan dibrowser, maka perubahannya text tersebut menjadi berwarna dengan menambahkan property dan nilai berupa background untuk mengatur warna,       border, min-height, padding, text-align, color, display, margin dan text-decoration

   ![Screenshot (183)](https://user-images.githubusercontent.com/59770620/113690686-df279800-96f5-11eb-9b15-9c5a945676de.png)![Uploading Screenshot (184).png…]()




SOAL DAN JAWABAN

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
   dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
   jawaban :
   [1] Ini adalah tampilan codingan jika ditambahkan deklarasi CSS dengan mengubah/membuat property dan nilai pada kode css
   
   ![Screenshot (182)](https://user-images.githubusercontent.com/59770620/113704117-f078a080-9705-11eb-888a-39fb5d4463ee.png)
   
   [2] Hasil/Tampilan ketika dijalankan dibrowser, maka terlihat perubahannya dari yang sebelumnya, untuk heading 1 terlihat text tersebut berbayang dan berwarna biru, dan link    tersebut terlihat garis bawah pada text, heading 1 pada bagian elemen body text tersebut menjadi rata tengah, dan border menjadi lebih tebal

   ![Screenshot (185)](https://user-images.githubusercontent.com/59770620/113704168-fcfcf900-9705-11eb-8bda-2697c152193e.png)
   
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
   penjelasannya!
   jawaban : perbedaannya yaitu elemen h1 untuk mengubah nilai text pada dokumen html yg menggunakan tag h1 pada elemen-elemen dan intro h1 untuk mengubah nilai text yg ada pada    selector h1 di dokumen html agar property terlihat jauh lebih menarik difile css
   
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
   elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
   penjelasan dan contohnya!
   jawaban : hasilnya pun akan terlihat sama, 
   [1] Internal CSS adalah kode CSS yang ditulis di dalam tag style
   
   ![Screenshot (186)](https://user-images.githubusercontent.com/59770620/113871512-305e8700-97dd-11eb-9042-7d1f7b9c2e59.png)
   
   [2] Eksternal CSS adalah kode CSS yang ditulis terpisah dengan kode HTML
   
   ![Screenshot (187)](https://user-images.githubusercontent.com/59770620/113871835-7ddaf400-97dd-11eb-9b0a-9b4724a13926.png)
   
   [3] Inline CSS adalah kode CSS yang ditulis langsung pada atribut elemen HTML.
   
   ![image](https://user-images.githubusercontent.com/59770620/113872129-cb576100-97dd-11eb-8fd2-d98041346ac8.png)

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
   terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
   Berikan penjelasan dan contohnya!  [p id="paragraf-1" class="text-paragraf"] 
   jawaban :
   CSS Selector dapat berupa elemen HTML, selector class atau selector id. Penggunaan CSS selector
   disesuaikan dengan kebutuhannya. Elemen selector akan berlaku pada semua elemen tersebut.
   Untuk class dan id selector, akan berlaku pada elemen yang menggunakan class atau id tersebut.
   
   [1] Class Selector dideklarasikan dengan menambahkan tanda titk (.) sebelum nama class yang akan
    digunakan.
    
    ![Screenshot (189)](https://user-images.githubusercontent.com/59770620/113872860-79fba180-97de-11eb-8ae7-6a3257da1b8f.png)

   [2] ID Selector dideklarasikan dengan menambahkan tanda # sebelum nama id yang akan digunakan.
   
   ![Screenshot (190)](https://user-images.githubusercontent.com/59770620/113872986-9992ca00-97de-11eb-8fe1-b569e1b70b46.png)

   
   
