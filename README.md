Create a new repository on the command line

echo "# TestRepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/codizant/TestRepo.git
git push -u origin main

------------------------------------------------
or push an existing repository from the command line
------------------------------------------------
git remote add origin https://github.com/codizant/TestRepo.git
git branch -M main
git push -u origin main



----------------------------------------------------------------
How to push you code changes
----------------------------------------------------------------
DELL@DESKTOP-LLRI2L1 MINGW64 /d/GitRepository/ReactJs (DEV)
$ git add .

DELL@DESKTOP-LLRI2L1 MINGW64 /d/GitRepository/ReactJs (DEV)
$ git commit -m 'basic only'


DELL@DESKTOP-LLRI2L1 MINGW64 /d/GitRepository/ReactJs (DEV)
$ git commit -m 'basic only'


DELL@DESKTOP-LLRI2L1 MINGW64 /d/GitRepository/ReactJs (DEV)
$ git push --set-upstream origin DEV

