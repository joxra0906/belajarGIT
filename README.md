Daftar tugas / branch
  1.  Tugas-git
  2.  Tugas-html
  3.  Tugas-css
  4.  Tugas-js
  5.  Tugas-midProject
  6.  Tugas-php
  7.  Tugas-finalProject

Daftar perintah GIT
...
Clone repositori ke lokal
git clone https://github.com/joxra0906/belajarGIT.git
cd belajarGIT

Membuat branch 
git checkout -b Tugas-git

Menambahkan file kosong dan mengisi 
touch Tugas-Git.txt
echo "Ini tugas pertama tentang Git" > Tugas-Git.txt

Menyimpan Perubahan
git add Tugas-Git.txt
git commit -m "Menambahkan file Tugas-Git.txt"

Merge branch ke branch main
git checkout main
git merge Tugas-git

Sinkronisasi ke github
git push origin main