Git on Github


Create a new repository on the command line

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:zwindy/ztest.git
git push -u origin master


Push an existing repository from the command line

git remote add origin git@github.com:zwindy/ztest.git
git push -u origin master


Update the existing repository

git add .
git commit -m "Do some updaet"
git push -u origin master
