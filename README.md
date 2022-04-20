Work with git.

Setup git git.com

Enter to dir and open command line.
git init
echo "info about this project" >> README.md
Add file index.html
git status
Add file script.js
git add . ( add 2 file )
git status
cls
Change index.html
git status
git add index.html (or git add.)
git status
git commit -m "new index script"
Add file errors.txt
git status
Add file .gitignore
To file add line errors.txt
git add .
Add dir logs and file logs.txt
Change .gitignore add \logs
git add .
git commit -m "added .gitignore"


git status
git branch
git branch test
git branch -D test
git branch readme
git branch
git checkout readme
git checkout master
git checkout -b new (creation and transition to the branch)
git checkout readme
git branch -D new
Add to dir file readme.md
git status
git add .
git commit -m "created readme.md"
git checkout master ( we do not see readme.md )
git checkout readme ( we see readme.md ) 
git checkout master
git status
git branch
git merge readme
git branch -D readme


On GitHub add repository TestDoc
git config --global user.name "***"
git config --global user.email "em@em.ua"
git remote add origin https://github.com/AlexFromKiyv/TestDoc.git
git push -u origin master
Change file script.js
git commit -m "updated script.js"
git push
Change file script.js
git add script.js
git commit -m "updated script.js"
git push

Create dir NewProject
cd NewProject
git clone https://github.com/AlexFromKiyv/TestDoc.git
open in VSC folder
change script.js
git add .
git commit -m "change script.js"

Open dir in console
git pull



