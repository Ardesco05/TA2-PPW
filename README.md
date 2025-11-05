**GIT SETUP & INISIALISASI**
git config --global user.name "Arlen Destico"
git config --global user.email "arlendestico@gmail.com"

mkdir TA2-PPW
cd TA2-PPW
git init

**STEP ADD FILE & COMMIT PERTAMA**
git add index.html
git commit -m "add index.html"

git add .
git commit -m "add style.css"

**STEP TAMBAH FITUR (HOBI) & COMMIT**
git add index.html
git commit -m "add hobi to index.html"

**STEP HUBUNGKAN KE GITHUB**
git remote add origin https://github.com/Ardesco05/TA2-PPW.git
git push -u origin master

**STEP MERGE FITUR KE MASTER**
git merge feature-hobi
git branch -d feature-hobi
git push -u origin master
