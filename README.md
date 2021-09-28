
## Questao 2 :

Usuário@DESKTOP-REJBNKM MINGW64 ~ (master)
$ cd document
bash: cd: document: No such file or directory

Usuário@DESKTOP-REJBNKM MINGW64 ~ (master)
$ cd Documents

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents (master)
$ mkdir Dever

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents (master)
$ cd Dever

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever (master)
$ git init
Initialized empty Git repository in C:/Users/Usuário/Documents/Dever/.git/

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever (master)
$ git clone git@github.com:DavidSaintAnna/my_first_steps.git
Cloning into 'my_first_steps'...
warning: You appear to have cloned an empty repository.

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever (master)
$ cd my_first_steps

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
## Questao 3 :

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ echo>ola_mundo.txt

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ola_mundo.txt

nothing added to commit but untracked files present (use "git add" to track)

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ git add ola_mundo.txt
warning: LF will be replaced by CRLF in ola_mundo.txt.
The file will have its original line endings in your working directory

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   ola_mundo.txt


Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ git commit -m "test"
[master (root-commit) ceb4fc7] test
 1 file changed, 1 insertion(+)
 create mode 100644 ola_mundo.txt

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 221 bytes | 221.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:DavidSaintAnna/my_first_steps.git
 * [new branch]      master -> master

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)


## Questao 4 :
Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ touch .gitignore

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ ls
ola_mundo.txt

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ ls -a
./  ../  .git/  .gitignore  ola_mundo.txt

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        serei_ignorado.txt

nothing added to commit but untracked files present (use "git add" to track)

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ echo serei_ignorado.txt >> .gitignore

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ cat .gitignore
serei_ignorado.txt

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

Usuário@DESKTOP-REJBNKM MINGW64 ~/Documents/Dever/my_first_steps (master)
