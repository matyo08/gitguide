# Version control - git
## local repo létrehozása

- initialization, creates local repo
    >git init
- ellenörzés mi modosult?
    > git status
- minden fájlt amiben történt modosulás szertenék az új verzióban elmenteni
    >git add.

- az előkészitett adatokat (commit elött) ellenörzöm (a stage-n)
    >git status
- user name and email set:
    > git config user.name/user.email
- új verzió megszületése 
    >git commit -m "note"
- ellenörzés
    >git status
## Cloud repo

- make new repo on github
- connect repo:
    >git remote add origin https://token@github.com/matyo08/gitguide.git
- first push:
    > git push -u origin master
- following pushes:
    > git push