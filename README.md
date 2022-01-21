# BankingMicroservice
cd Banking
git init
git branch -m Main
git remote add origin git@github.com:ArlanGMZ/BankingMicroservice.git
git push
git push origin Main
git status
git add .
git commit
git push -u origin Main
git branch dev1
git branch dev2
git branch
git checkout dev1
vi src/main/java/com/App.java
git add .
git commit -m "App.java updated"
git branch
git push origin dev1
git checkout dev2
vi src/main/java/com/App.java
git add .
git commit -m "App.java updated by dev2"
git push origin dev2
git checkout Main
git merge dev1
git commit -m "dev1 merged"
git push origin Main
git log
