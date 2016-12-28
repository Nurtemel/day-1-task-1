git --version  => Versiyon bilgisini basar ekrana
git config --global -l => Global seviyede tüm ayarları listelemek için
git config --global user.name "Tayfun Ateş"  => Kullanıcı Adı
git config --global user.email "martayfun@gmail.com" =>Mail Adresi# day-1-task-1

echo "# day-1-task-1" >> README.md
git init
git commit -m "first commit"
git remote add origin https://github.com/20141121034/day-1-task-1.git
git push -u origin master
