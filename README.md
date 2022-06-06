                                                                        LAPORAN PRAKTIKUM 11
                                                                           PHP FRAMEWORK
                                                                          PEMROGRAMAN WEB
Nama		: Rafi Hanif R.
NIM		: 312010358
Kelas		: TI.20.A.2
Mata Kuliah	: Pemrograman Web

PENDAHULUAN
Segala Puji bagi Tuhan Semesta Alam yang telah memberikan kita berbagai macam ni’mat yaitu Ni’mat Islam, Ni’mat Iman serta Ni’mat Sehat Wal ‘Afiat, sehingga saya bisa menyusun Laporan Praktikum 11 ini dengan baik. Dan tidak lupa pula Sholawat dan Salam selalu tercurah kepada junjungan kita Nabi Muhammad SAW. Yang telah membawa kita dari zaman Jahiliyah menuju zaman Terang Benderang seperti saat ini.
Pada Laporan Praktikum 11 ini saya akan menjelaskan tentang cara-cara bagaimana membuat program sederhana dengan menggunakan PHP Framework Code Igniter 4. Tidak lupa pula saya berterima kasih kepada Pak Agung Nugroho yang telah memberikan Materi serta Instruksi untuk Mahasiswa/i agar Mahasiswa/i dapat mempelajarinya dan mempraktikannya dengan baik.

TUJUAN
1.	Mahasiswa mampu memahami konsep dasar Framework 
2.	Mahasiswa mampu memahami konsep dasar MVC
3.	Mahasaswa mampu membuat program sederhana menggunakan Framework Codeigniter 4

LANDASAN TEORI
Materi yang telah diberikan oleh Dosen Pengampu dan Instruksi Praktikum sangatlah penting untuk pembelajaran Mahasiswa. Oleh karena itu, bahan ajar atau teori-teori yang telah diajarkan atau diberikan oleh Dosen Pengampu sangatlah bermanfaat untuk pembelajaran hari ini dan di kemudian hari.
BAHAN-BAHAN
-	Visual Studio Code
-	Xampp
-	Code Igniter 4 (yang sudah dimasukkan ke dalam file Xampp/htdocs/lab11_ci/ci4)
-	Google Chrome


CARA-CARA
1.	Pertama untuk mengaktifkan beberapa ekstensi yang dibutuhkan bisa melalui Xampp Control Panel dan pada bagian Apache klik Config->PHP(php.ini). seperti dibawah ini.
 ![image](https://user-images.githubusercontent.com/102600434/172154481-f8707c42-082e-4433-9078-3883ca2532b2.png)


2.	Pada bagian extension tersebut hialngkan tanda titik koma (;) untuk ekstensi yang akan diaktifkan. Lalu simpan kembali dengan menekan shortcut pada keyboard CTRL+S dan restart pada Apache Web Server seperti berikut.
 ![image](https://user-images.githubusercontent.com/102600434/172154498-33830835-51e1-49a6-8bf8-c8ff61156e87.png)

![image](https://user-images.githubusercontent.com/102600434/172154531-ebe897b8-55d8-4969-8fa3-16e0f0aebb0d.png)

![image](https://user-images.githubusercontent.com/102600434/172154548-38c53ad2-2884-49c1-9fe6-28b27621830b.png)

![image](https://user-images.githubusercontent.com/102600434/172154566-eb457c71-7a0c-445b-be04-762810191029.png)

 

3.	Untuk Instalasi Code Iginter 4 bisa dilakukan dengan mengklik link https://codeigniter.com/download lalu, ekstrak file WinRar Code Igniter 4 yang telah diunduh tadi ke dalam file direktori htdocs/Lab11_ci lalu ubah nama direktori framework Code Igniter nya menjadi ci4 seperti dibawah ini.
![image](https://user-images.githubusercontent.com/102600434/172154607-dfcffa61-fca9-44fc-b7bd-2cb8c4c689e7.png)
 

4.	Kemudian buka browser Chrome dan ketik dengan alamat http://localhost/lab11_ci/ci4/public maka hasilnya akan seperti dibawah ini.
![image](https://user-images.githubusercontent.com/102600434/172154640-48e57e54-068e-4ed2-af94-99fcae0d042b.png)
 

5.	Untuk menjalankan CLI pada Code Igniter melalui Xampp Control Panel->Shell, setelah terbuka maka ketikkan kata sesuai dengan direktori kerja project yang sedang dibuat seperti dibawah ini.
![image](https://user-images.githubusercontent.com/102600434/172154664-2614b51d-d473-4739-aac9-da48a569d7b1.png)

![image](https://user-images.githubusercontent.com/102600434/172154691-d87cfe8c-aefc-4acb-be49-14f5f0e5b260.png)

![image](https://user-images.githubusercontent.com/102600434/172154700-202d387b-e34a-4f56-b207-9b3327daed49.png)

![image](https://user-images.githubusercontent.com/102600434/172154712-25dbc528-9a75-49e9-a416-8ff6a82552be.png)
 

6.	Lalu ubah nama file env menjadi .env pada direktori htdocs/Lab11_ci/ci4 dan ubah CI_ENVIRONTMENT = production menjadi CI_ENVIRONTMENT = development seperti dibawah berikut.
![image](https://user-images.githubusercontent.com/102600434/172154783-f0d9e92b-282a-4247-8d54-fdd8a62d036b.png)

![image](https://user-images.githubusercontent.com/102600434/172154799-13ce7574-3c34-41cb-8c00-11584f7170ed.png)
 

7.	Untuk mencoba error maka buka file app/Controller/Home.php pada lalu hilangkan pada bagian titik koma berikut seperti ini.
![image](https://user-images.githubusercontent.com/102600434/172154831-5a206595-fc03-44d0-b9c6-7c8b6a4ec632.png)

![image](https://user-images.githubusercontent.com/102600434/172154853-dfcf3603-00d6-475a-8d18-8475d0777ee8.png)
 

8.	Simpan pada perubahan tersebut dengan menekan tombol shortcut CTRL+S lalu refersh pada halaman browser http://localhost/lab11_ci/ci4/public maka hasilnya akan seperti berikut.
 ![image](https://user-images.githubusercontent.com/102600434/172154884-30b70dc2-7b50-422f-b89b-06bde3c6fc45.png)


9.	Sekarang kita buka file Routes.php yang terletak pada file app/config/Routes.php lalu tambahkan kode seperti gambar dibawah ini.
![image](https://user-images.githubusercontent.com/102600434/172154912-a4b4077a-7dfd-418d-b624-9de37c0b76f9.png)

![image](https://user-images.githubusercontent.com/102600434/172154924-939e6cbd-b2c6-415e-b5c6-8717150eb16a.png)

 
10.	Lalu buka CLI lagi dengan melakukan cara yang sama yaitu dengan melalui Xampp Control Panel->Shell lalu ketikkan kata php spark routes maka hasilnya akan muncul seperti berikut.
![image](https://user-images.githubusercontent.com/102600434/172154957-c61f9e49-7f16-476a-960e-ed69eb7b6674.png)

![image](https://user-images.githubusercontent.com/102600434/172154975-4cfc80eb-b45c-43c1-9429-10a5c05321da.png)


11.	

KESIMPULAN 
Dari cara-cara dan serta Instruksi Praktikum di atas sangatlah penting untuk dipraktikkan bagi Mahasiswa/I supaya bisa dicontohkan sebagai tanda pemahaman semua Mahasiswa/I tergadap maeri yang telah diberikan oleh Dosen Pengampu.
