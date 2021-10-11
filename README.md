# Git - version control system

- https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet
- https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html
- https://medium.com/@erdem6uzel/versiyon-kontrol-sistemi-nedir-fc4a7ce566ce
- https://www.hostinger.com/tutorials/basic-git-commands


# Bash basic commands

- ls - show all items in current directory
- touch {fileName} - create new file
- pwd - show current directory
- mkdir {directoryName}- create new directory
- cd {directoryName} - change directory
- cd .. - change directory 
- rm {fileName} - remove file
- rm -m {DirecotoryName} - remove directory


# Basic Git commands

- git init - folderi repository-e donusdurmek
- git add - deyisiklikleri commitlemeden evvel nezere almaq (git add <fayladi> yazdiqda adini yazdigimiz fayl secilir, git add .  yazdiqda butun fayllar)
- git commit -m "your commit message" - deyisikliyin versiya kii yadda saxlanilmasi, bu zaman dirnaq icerisinde commitdeki deyisiklikde ne bas veridyi qisaca ifade olunur
- git remote add origin <url> - burada remote repository-e birinci defe push edilmezden evvel origin elave edilir ve <url> yerine hemin githubdaki repositoryin linki elave edilir, bu emeliiyyat yalnizca ilk push emeliyyatindan evvel edilir, daha sonra eyni yerden eyni repositoryde push edilmek istenildikde yazilmir
- git push origin master - bu emeliyyat var olan local repositorydeki en son deyisiklikleri remote repositorye elave edir,bu zaman yazilan master sozu branchi ifade edir
  
# Tapsiriq:
   - Oz github hesabinizda public bir repo yaradirsiniz , adi git-homework olsun. O reponun icine bu repodaki gitcommands.txt faylini yerlesdirisiniz git commandlari vasitesiyle ve o reponun linkini mene oz code.edu.az emaillarinizden gonderirsiniz
  - Butun kecdiyimiz kommandlari oyrenin, kecmediyimiz kommandlari BAXMAYIN umumiyyetle.
