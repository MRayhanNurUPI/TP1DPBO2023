# TUGAS PRAKTIKUM 1 PRAKTIKUM DPBO 2023

## Janji
Saya Muhammad Rayhan Nur [2100192] mengerjakan Tugas Praktikum 1 dalam mata kuliah Desain Pemrograman Beriorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Tujuan Program
Program ini dibuat dengan tujuan untuk mengimplementasikan konsep pewarisan, komposisi, dan bagaimana satu kelas dapat berinteraksi dengan kelas lain dengan adanya syarat dan batasan.

## Desain Program
![alt text](https://github.com/MRayhanNurUPI/LATIHAN4DPBO2023/blob/main/Latihan4DPBO_Muhammad%20Rayhan%20Nur_ClassDiagram.png)
Program ini menggunakan total 6 kelas yang terdiri dari:
1) Kelas Human
2) Kelas Mahasiswa
3) Kelas Dosen
4) Kelas AsistenDosen
5) Kelas AnggotaBEM
6) Kelas AnggotaDPM

## Syarat dan Batasan Interaksi
### Asisten Dosen - Dosen
Urutan langkah interaksi:
Dosen Mengajar -> Dosen Memberi Tugas kepada Asisten Dosen -> Asisten Dosen Menerima Tugas -> Asisten Dosen Mengajar -> Asisten Dosen Memberi Laporan kepada Dosen -> Dosen Menerima Laporan Tugas -> Dosen Menilai Tugas
Sehingga syarat dan batasannya sebagai berikut:
1) Dosen tidak dapat memberi tugas mengajar kepada Asisten Dosennya apabila Dosen tersebut belum mengajar di kelas.
2) Dosen tidak dapat memberikan nilai sebelum mendapat laporan dari Asisten Dosennya.
3) Asisten Dosen tidak dapat mengajar ke mahasiswa ajarnya apabila belum mendapat tugas dari Dosen.
4) Asisten Dosen tidak dapat memberikan laporan kepada Dosen apabila Asisten Dosen belum mengajar.

### Anggota BEM - Anggota DPM
Urutan langkah interaksi:
AnggotaBEM Berinovasi -> AnggotaBEM Melaksanakan Proker -> AnggotaBEM Memberi Laporan ke AnggotaDPM -> AnggotaDPM Menerima Laporan -> AnggotaDPM Membaca Laporan -> AnggotaDPM Mengapresiasi AnggotaBEM
Sehingga syarat dan batasannya sebagai berikut:
1) Anggota BEM tidak dapat melaksanakan proker jika belum berinovasi.
2) Anggota BEM tidak dapat memberi laporan apabila belum menjalankan prokernya.
3) Anggota DPM tidak dapat membaca laporan apabila Anggota BEM belum melaporkan hasil prokernya.
4) Anggota DPM tidak dapat memberikan apresiasi apabila belum membaca laporan dari Anggota BEM.

## Alur Program
1) Instansiasi Objek Dosen dan Asisten Dosen
2) Menjalankan fungsi-fungsi yang menggambarkan interaksi antara kelas Dosen dan AsistenDosen.
3) Instansiasi Objek AnggotaBEM dan AnggotaDPM
4) Menjalankan fungsi-fungsi yang menggambarkan interaksi antara kelas AnggotaBEM dan AnggotaDPM.
