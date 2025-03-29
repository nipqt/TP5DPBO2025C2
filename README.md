# Janji

Saya Hanif Ahmad Syauqi dengan NIM 2304330 mengerjakan soal Tugas Praktikum 5 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

# Desain Program

Di Program ini terdiri dari beberapa class :
- Class Mahasiswa :
    - Atribut:
        - nim (Nim Mahasiswa)
        - nama (Nama Mahasiswa)
        - jenisKelamin (Jenis Kelamin Mahasiswa)
        - jenisMusik (Jenis Musik Yang Disukai)
    - Metode:
        - setNim (untuk memasukkan data nim)
        - setNama (untuk memasukkan data nama)
        - setJenisKelamin (untuk memasukkan data jenisKelamin)
        - setJenisMusik (untuk memasukkan data jenisMusik)
        - getNim (untuk mendapatkan data nim)
        - getNama (untuk mendapatkan data nama)
        - getJenisKelamin (untuk mendapatkan data jenisKelamin)
        - getJenisMusik (untuk mendapatkan data jenisMusik)

- Class Menu :
    - Atribut:
        - selectedIndex (Untuk index baris yang di klik)
        - ArrayList<Mahasiswa> (Untuk menampung data mahasiswa)
        - mainPanel (Panel Utama Program)
        - nimField (Kolom Isian Untuk NIM)
        - namaField (Kolom Isian untuk Nama)
        - nahasiswaTable (Menampilkan data mahasiswa)
        - addUpdateButton (Tombol Add/Update)
        - cancelButton (Tombol Cancel)
        - titleLabel (Tulisan Judul)
        - nimLabel (Tulisan "NIM")
        - namaLabel (Tulisan "Nama")
        - jenisKelaminLabel (Tulisan "Jenis Kelamin")
        - jenisKelaminComboBox (Pilihan Dropdown Jenis Kelamin)
        - MusikComboBox (Pilihan Dropdown Jenis Musik)
    - Metode:
        - Menu (konstruktor/konfigurasi utama program)
        - main (window GUI program)
        - setTable (set Tabel data yang dimasukkan)
        - insertData (memasukkan data baru)
        - updateData (melakukan edit data)
        - deleteData (melakukan delete data)
        - clearForm (mereset ke posisi default)
        - populateList (Data default)

# Alur Program
- Program sudah diintegrasikan dengan database, diharapkan untuk memasukkan database tersebut sebelum menjalankannya
- Saat Di run, akan muncul GUI data Mahasiswa yang isinya terdapat:
  - NIM
  - Nama
  - Jenis Kelamin
  - Jenis Musik yang disukai
- Terdapat beberapa data yang sudah tersedia saat kita menjalankan program ini
- Di program ini, kita bisa menambahkan data dengan mengisi data kosong dan menekan tombol add setelahnya
- Jika masukkan ada yang kosong, akan muncul pesan error untuk mengisi data yang masih kosong
- Jika NIM yang dimasukkan sudah ada, akan muncul pesan error
- Bisa juga melakukan Update dan Delete dengan memilih data yang tersedia, setelah dipilih akan muncul data pada setiap kolom kosong yang dimana kita bisa melakukan edit terhadap data tersebut atau melakukan delete
- Saat melakukan Update, jika data yang di update ada masukkan yang kosong, akan muncul pesan error
- Saat kita melakukan delete, akan muncul konfirmasi apakah data ini ingin dihapus atau tidak

# Dokumentasi
![](https://github.com/nipqt/TP5DPBO2025C2/blob/main/Screenshots/record.gif)
