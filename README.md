### (3) Resume Materi KMFlutter – Basic Version and Branch Management (Git)

No_Urut     : 1_022FLC_34
Nama        : Sabda Adjie Saputra

Soal :
Tuliskan 3 poin yang dipelajari dari materi tersebut :

1. Apa itu versioning :
Versioning adalah melakukan sebuah pengaturan versi atau pelacakan perubahan dari setiap code program.
Contoh :
REVISI.DOC --> REFVISI FIX.DOC --> REVISI FIX FINAL.DOC --> REVIAI FIX FINAL LAST.DOC

didalam contoh tersebut nantinya kita bisa nge track perubahan perubahan apa saja dan siapa yang mengubah. Jika tidak ada implementasi versioning kita sulit meng identifikasi perubahan-perubahan yang terjadi dan siapa yang merubahnya pada program.

2. Untuk men-track sebuah revisi pada source code program terdapat tools antaralain :

* Version Control System (VCS)
* Source Code Manager (SCM)
* Revision Control System (RCS)

3. GIT adalah salah satu Version Control System (VCS) populer yang di gunakan para developer untuk mengembangkan aplikasi secara bersama-samadan juga untuk men track perubahan-perubahan yang terjadi pada saat pengembangan aplikasi secara bersama-sama.

4. Git commit adalah untuk menyimpan perubahan yang sudah dilakukan, namun tidak ada perubahan yang terjadi pada remote repository. Untuk menyimpa perubahan kita bisa menambahkan message perubahan apa yang sudah di lakukan dengan menggunakan git commit -m "isi perubahan apa yang sudah di lakukan"

5. Git stash adalah ketika kita melakukan penambahan code yang terdiri dari atau banyak line dan penambahan itu dilakukan pada branch yang salah dan nama programnya sama dengan nama program yang ingin ditambah pada branch lain.

contoh :
di branch featureA terdapat program dengan nama data_mahasiswa.dart dan di branch featureB juga terdapat program dengan nama data_mahasiswa.dart.
Kita sudah melakukan penulisan data hingga 100 line atau data pada program data_mahasiswa, tetapi kita menuliskan datanya di featureB sedangkan kita ingin menuliskan data nya branch featureA, disini kita bisa menggunakan perintah " git stash " pada featureB maka data yang kita tambahkan tadi akan hilang pada code featureB dan code tersebut akan di simpan di tempat lain, lalu kita apply data tadi yang sudah di stash dengan pindah ke branch yang ingin di tuju dengan perintah " git checkout featureA" lalu kita pindahkan datanya dengan perintah "git stash apply" maka data yang sudah kita ketikan di featureB akan terpindah di featureA.

I am editting the README file. Adding some more details about the project description.
