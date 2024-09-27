
User@DESKTOP-SL8SCCG MINGW64 /
$ git config --global user.name thokozanie2

User@DESKTOP-SL8SCCG MINGW64 /
$ git config --global user.mail 218353711@tut4life.ac.za

User@DESKTOP-SL8SCCG MINGW64 /
$ cd Desktop
bash: cd: Desktop: No such file or directory

User@DESKTOP-SL8SCCG MINGW64 /
$ git status
fatal: not a git repository (or any of the parent directories): .git

User@DESKTOP-SL8SCCG MINGW64 /
$ git init
C:/Program Files/Git/.git: Permission denied

User@DESKTOP-SL8SCCG MINGW64 /
$ ls
LICENSE.txt        cmd/  git-bash.exe*  proc/         unins000.exe*
ReleaseNotes.html  dev/  git-cmd.exe*   tmp/          unins000.msg
bin/               etc/  mingw64/       unins000.dat  usr/

User@DESKTOP-SL8SCCG MINGW64 /
$ ls -all
total 5820
drwxr-xr-x 1 User 197121       0 Sep  6  2022 ./
drwxr-xr-x 1 User 197121       0 Sep  6  2022 ../
-rw-r--r-- 1 User 197121   18765 Aug 30  2022 LICENSE.txt
-rw-r--r-- 1 User 197121  226956 Aug 30  2022 ReleaseNotes.html
drwxr-xr-x 1 User 197121       0 Sep  6  2022 bin/
drwxr-xr-x 1 User 197121       0 Sep  6  2022 cmd/
drwxr-xr-x 1 User 197121       0 Sep  6  2022 dev/
drwxr-xr-x 1 User 197121       0 Sep  6  2022 etc/
-rwxr-xr-x 1 User 197121  137776 Aug 30  2022 git-bash.exe*
-rwxr-xr-x 1 User 197121  137264 Aug 30  2022 git-cmd.exe*
drwxr-xr-x 1 User 197121       0 Sep  6  2022 mingw64/
dr-xr-xr-x 9 User 197121       0 Sep 26 17:52 proc/
drwxr-xr-x 1 User 197121       0 Sep 26 17:52 tmp/
-rw-r--r-- 1 User 197121 1256530 Sep  6  2022 unins000.dat
-rwxr-xr-x 1 User 197121 3212176 Sep  6  2022 unins000.exe*
-rw-r--r-- 1 User 197121   24183 Sep  6  2022 unins000.msg
drwxr-xr-x 1 User 197121       0 Sep  6  2022 usr/

User@DESKTOP-SL8SCCG MINGW64 /
$ pwd
/

User@DESKTOP-SL8SCCG MINGW64 /
$ cd C:\xampp2\htdocs
bash: cd: C:xampp2htdocs: No such file or directory

User@DESKTOP-SL8SCCG MINGW64 /
$ cd User
bash: cd: User: No such file or directory

User@DESKTOP-SL8SCCG MINGW64 /
$ cd Users
bash: cd: Users: No such file or directory

User@DESKTOP-SL8SCCG MINGW64 /
$ cd ..

User@DESKTOP-SL8SCCG MINGW64 /
$ cd .

User@DESKTOP-SL8SCCG MINGW64 /
$ pwd
/

User@DESKTOP-SL8SCCG MINGW64 /
$ ls -a
./  ../  LICENSE.txt  ReleaseNotes.html  bin/  cmd/  dev/  etc/  git-bash.exe*  git-cmd.exe*  mingw64/

User@DESKTOP-SL8SCCG MINGW64 /
$ cd usr

User@DESKTOP-SL8SCCG MINGW64 /usr
$ pwd
/usr

User@DESKTOP-SL8SCCG MINGW64 /usr
$ ls -a
./  ../  bin/  etc/  lib/  libexec/  share/  ssl/

User@DESKTOP-SL8SCCG MINGW64 /usr
$ cd ..

User@DESKTOP-SL8SCCG MINGW64 /
$ cd ..

User@DESKTOP-SL8SCCG MINGW64 /
$ cd ..

User@DESKTOP-SL8SCCG MINGW64 /
$ cd C:

User@DESKTOP-SL8SCCG MINGW64 /c
$ ls
'$AV_ASW'/       '$WINDOWS.~BT'/   Config.Msi/                DumpStack.log.tmp   Microsoft/      PerfL
'$GetCurrent'/   '$WinREAgent'/   'Documents and Settings'@   Intel/              MinGW/         'Progr
'$Recycle.Bin'/  '$Windows.~WS'/   DumpStack.log              MSOCache/           OneDriveTemp/  'Progr

User@DESKTOP-SL8SCCG MINGW64 /c
$ cd xampp2

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2
$ ls -a
./             apache/               catalina_stop.bat    filezilla_start.bat  killprocess.bat  mercury
../            apache_start.bat      cgi-bin/             filezilla_stop.bat   licenses/        mercury
FileZillaFTP/  apache_stop.bat       contrib/             htdocs/              locale/          mysql/
MercuryMail/   catalina_service.bat  ctlscript.bat        img/                 mailoutput/      mysql_s
anonymous/     catalina_start.bat    filezilla_setup.bat  install/             mailtodisk/      mysql_s

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2
$ cd htdocs

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs
$ ls -a
 ./   ../   Cmder.exe*   Composer-Setup.exe*   Development/   Development.zip   LICENSE   PHPMVCFramewo

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs
$ cd Test

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git init
Reinitialized existing Git repository in C:/xampp2/htdocs/Test/.git/

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ touch index.html

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ notepad index.html

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ touch styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        styles.css

nothing added to commit but untracked files present (use "git add" to track)

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   styles.css


User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git commit -m "We created index.html and styles.css"
[master (root-commit) 93e183c] We created index.html and styles.css
 2 files changed, 14 insertions(+)
 create mode 100644 index.html
 create mode 100644 styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git commit -m "addded title on index"
[master 4785c12] addded title on index
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git commit -m "addded font size"
[master 6a8650d] addded font size
 1 file changed, 1 insertion(+)

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git log
commit 6a8650d24b9590324afdb9a36e6cf10764919340 (HEAD -> master)
Author: thokozanie2 <>
Date:   Thu Sep 26 18:19:22 2024 +0200

    addded font size

commit 4785c12d090ef35abe79c4d91e19518c1bc4e8a7
Author: thokozanie2 <>
Date:   Thu Sep 26 18:18:24 2024 +0200

    addded title on index

commit 93e183cf919e87380db705c4b1ab462da98e9fe4
Author: thokozanie2 <>
Date:   Thu Sep 26 18:08:08 2024 +0200

    We created index.html and styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git log --oneline
6a8650d (HEAD -> master) addded font size
4785c12 addded title on index
93e183c We created index.html and styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git config --global user.email 218353711@tut4life.ac.za

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git log --oneline
6a8650d (HEAD -> master) addded font size
4785c12 addded title on index
93e183c We created index.html and styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git log
commit 6a8650d24b9590324afdb9a36e6cf10764919340 (HEAD -> master)
Author: thokozanie2 <>
Date:   Thu Sep 26 18:19:22 2024 +0200

    addded font size

commit 4785c12d090ef35abe79c4d91e19518c1bc4e8a7
Author: thokozanie2 <>
Date:   Thu Sep 26 18:18:24 2024 +0200

    addded title on index

commit 93e183cf919e87380db705c4b1ab462da98e9fe4
Author: thokozanie2 <>
Date:   Thu Sep 26 18:08:08 2024 +0200

    We created index.html and styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ touch feature.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git commit -m "Added feature.js"
[master f15c010] Added feature.js
 1 file changed, 1 insertion(+)
 create mode 100644 feature.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git commit -m "Added new p tag under h1"
[master 4369fcf] Added new p tag under h1
 1 file changed, 1 insertion(+)

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git log --oneline
4369fcf (HEAD -> master) Added new p tag under h1
f15c010 Added feature.js
6a8650d addded font size
4785c12 addded title on index
93e183c We created index.html and styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git checkout 4785c12
Note: switching to '4785c12'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 4785c12 addded title on index

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test ((4785c12...))
$ git checkout master
Previous HEAD position was 4785c12 addded title on index
Switched to branch 'master'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git revert f15c010
[master a7ea5c9] Revert "Added feature.js"
 1 file changed, 1 deletion(-)
 delete mode 100644 feature.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git log --oneline
a7ea5c9 (HEAD -> master) Revert "Added feature.js"
4369fcf Added new p tag under h1
f15c010 Added feature.js
6a8650d addded font size
4785c12 addded title on index
93e183c We created index.html and styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git reset ^C

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git reset 4785c12
Unstaged changes after reset:
M       index.html
M       styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git reset 4785c12 --hard
HEAD is now at 4785c12 addded title on index

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git reset 93e183c --hard
HEAD is now at 93e183c We created index.html and styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git log --oneline
93e183c (HEAD -> master) We created index.html and styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git log --oneline
93e183c (HEAD -> master) We created index.html and styles.css

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git commit -m "corrected the spelling"
[master 09ed832] corrected the spelling
 1 file changed, 2 insertions(+), 2 deletions(-)

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git branch feature-1

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git branch -a
  feature-1
* master

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git checkout feature-1
Switched to branch 'feature-1'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ git branch -a
* feature-1
  master

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ touch feature-1.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ git status
On branch feature-1
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        feature-1.js

nothing added to commit but untracked files present (use "git add" to track)

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ git commit -m "Added a new feature file"
[feature-1 96f5b4e] Added a new feature file
 1 file changed, 1 insertion(+)
 create mode 100644 feature-1.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git checkout feature-1
Switched to branch 'feature-1'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git branch -D feature-1
Deleted branch feature-1 (was 96f5b4e).

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git branch -a
* master

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git checkout -b feature-1
Switched to a new branch 'feature-1'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ touch feature-1.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ git commit -m "Created a branch and added a feature file"
[feature-1 9c1488b] Created a branch and added a feature file
 1 file changed, 1 insertion(+)
 create mode 100644 feature-1.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-1)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git checkout -b feature-2
Switched to a new branch 'feature-2'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-2)
$ touch feature-2.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-2)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-2)
$ git commit -m "Added a feature2 branch and a file"
[feature-2 33e4d25] Added a feature2 branch and a file
 1 file changed, 1 insertion(+)
 create mode 100644 feature-2.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (feature-2)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git branch -a
  feature-1
  feature-2
* master

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git checkout master
Already on 'master'

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git merge feature-1
Updating 09ed832..9c1488b
Fast-forward
 feature-1.js | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 feature-1.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git merge feature-2
Merge made by the 'ort' strategy.
 feature-2.js | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 feature-2.js

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git push git@github.com:thokozanie2/git-one.git master
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git config --global --unset core.excludesfile

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git config --global --unset user.name
git config --global --unset user.email

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git config --global --list
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
user.mail=218353711@tut4life.ac.za
gui.recentrepo=C:/Users/User/ThokozanieMashele

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git config --global --unset user.mail

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git config --global --list
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
gui.recentrepo=C:/Users/User/ThokozanieMashele

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git config --global user.email "218353711@tut4life.ac.za"

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git config --global user.name "thokozanie2"

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git config --global --list
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
gui.recentrepo=C:/Users/User/ThokozanieMashele
user.email=218353711@tut4life.ac.za
user.name=thokozanie2

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ ssh -keygen
Bad escape character 'ygen'.

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/User/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/User/.ssh/id_rsa
Your public key has been saved in /c/Users/User/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:kXeOE+l/nBZaOoD5BPH6zEcLVIJe9LYQKdoLy+p7uzM User@DESKTOP-SL8SCCG
The key's randomart image is:
+---[RSA 3072]----+
|        .o+..    |
|        o+o*     |
|       ++oB +    |
|      o oX B .   |
|     . oS.B + o  |
|      o .* * * o |
|     .    = B =  |
|    . E    . +   |
|   .ooo=         |
+----[SHA256]-----+

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git push git@github.com:thokozanie2/git-one.git master
The authenticity of host 'github.com (20.87.245.0)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (15/15), 1.39 KiB | 94.00 KiB/s, done.
Total 15 (delta 5), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (5/5), done.
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/thokozanie2/git-one/pull/new/master
remote:
To github.com:thokozanie2/git-one.git
 * [new branch]      master -> master

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git add .

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git commit -m "added a button love me"
[master 74ebae7] added a button love me
 1 file changed, 1 insertion(+)

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git remote origin master
error: Unknown subcommand: origin
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand


User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git remote origin git@github.com:thokozanie2/git-one.git
error: Unknown subcommand: origin
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand


User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git remote add origin git@github.com:thokozanie2/git-one.git

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:thokozanie2/git-one.git
   e28ca66..74ebae7  master -> master

User@DESKTOP-SL8SCCG MINGW64 /c/xampp2/htdocs/Test (master)
$
