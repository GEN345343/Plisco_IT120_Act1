admin@gen MINGW64 ~ (master)
$ cd Desktop
bash: cd: Desktop: No such file or directory

admin@gen MINGW64 ~ (master)
$ mkdir Plisco_IT120_Act1

admin@gen MINGW64 ~ (master)
$ cd Plisco_IT120_Act1

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git init
Initialized empty Git repository in C:/Users/admin/Plisco_IT120_Act1/.git/

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git remote add origin https://github.com/GEN345343/Plisco_IT120_Act1.git

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ touch Profile.txt Education.txt Background.txt Readme.txt Test.py

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git add .

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ ^[[200~git commit -m "Initial commit with all files"
bash: $'\E[200~git': command not found

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git commit -m "Initial commit with all files"
[master (root-commit) b70d767] Initial commit with all files
 5 files changed, 3 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git config --global user.name "Elgen B."

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git config --global user.email "pliscoelgen@gmail.com"

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$  git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Elgen B.
user.email=pliscoelgen@gmail.com
gui.recentrepo=C:/Users/admin/edmond
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/GEN345343/Plisco_IT120_Act1.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git commit -m "Initial commit with all files"
On branch master
nothing to commit, working tree clean

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git remote add origin https://github.com/GEN345343/Plisco_IT120_Act1.git
error: remote origin already exists.

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git remote -v
origin  https://github.com/GEN345343/Plisco_IT120_Act1.git (fetch)
origin  https://github.com/GEN345343/Plisco_IT120_Act1.git (push)

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git push origin master
info: please complete authentication in your browser...
remote: Permission to GEN345343/Plisco_IT120_Act1.git denied to gen123985.
fatal: unable to access 'https://github.com/GEN345343/Plisco_IT120_Act1.git/': The requested URL returned error: 403

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git branch -M master

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/GEN345343/Plisco_IT120_Act1.git'

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git push -u origin master
info: please complete authentication in your browser...
remote: Permission to GEN345343/Plisco_IT120_Act1.git denied to gen123985.
fatal: unable to access 'https://github.com/GEN345343/Plisco_IT120_Act1.git/': The requested URL returned error: 403

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git push -u origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 329 bytes | 329.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/GEN345343/Plisco_IT120_Act1.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

admin@gen MINGW64 ~/Plisco_IT120_Act1 (master)
$ git checkout -b Plisco_B1
Switched to a new branch 'Plisco_B1'

admin@gen MINGW64 ~/Plisco_IT120_Act1 (Plisco_B1)
$ git branch
* Plisco_B1
  master

admin@gen MINGW64 ~/Plisco_IT120_Act1 (Plisco_B1)
$  git add Profile.txt

admin@gen MINGW64 ~/Plisco_IT120_Act1 (Plisco_B1)
$ git commit -m "Amend: added Birth of Place, Religion, Father's Occupation, Mother's Name, Occupation"git 
[Plisco_B1 2078e67] Amend: added Birth of Place, Religion, Father's Occupation, Mother's Name, Occupation
 1 file changed, 14 insertions(+)
a
admin@gen MINGW64 ~/Plisco_IT120_Act1 (Plisco_B1)
$ git push origin Plisco_B1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 513 bytes | 513.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Plisco_B1' on GitHub by visiting:
remote:      https://github.com/GEN345343/Plisco_IT120_Act1/pull/new/Plisco_B1
remote:
To https://github.com/GEN345343/Plisco_IT120_Act1.git
 * [new branch]      Plisco_B1 -> Plisco_B1

admin@gen MINGW64 ~/Plisco_IT120_Act1 (Plisco_B1)
$ git add Readme.txt

admin@gen MINGW64 ~/Plisco_IT120_Act1 (Plisco_B1)
$ git commit -m "Readme.txt"

admin@gen MINGW64 ~/Plisco_IT120_Act1 (Plisco_B1)
$ git commit -m "Readme.txt"
[Plisco_B1 517f138] Readme.txt
 1 file changed, 160 insertions(+)

admin@gen MINGW64 ~/Plisco_IT120_Act1 (Plisco_B1)
$ git push origin Plisco_B1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.70 KiB | 1.70 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/GEN345343/Plisco_IT120_Act1.git
   2078e67..517f138  Plisco_B1 -> Plisco_B1





