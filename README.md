## BELAJAR GIT 

1. membuat inisialisasi repo di local

        git init

2. cara commit
        
        git commit -m "pesan"

3. melihat status di local

        git status

4. melihat log file

        git log
        git log --oneline

5. melihat perbedaan antar commit

        git diff
        git diff versiId1..versiId2

6. mendaftarkan remote repo

        git remote add [nama-alias] [sumber]

7. mengambil remote repo ke local

        git clone [nama-repo]

8. mengupload repo local ke remote

        git push -u [nama-alias] [nama-branch]