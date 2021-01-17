# checkpoint-5
f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again (master)
$ mkdir learn_git_again

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again (master)
$ cd learn_git_again

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ touch third.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git init
Initialized empty Git repository in C:/Users/f.maouacine.CARRIERES/Desktop/learn_git_again/learn_git_again/.git/

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git add third.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git commit -m "adding third.txt"
[master (root-commit) 45393a8] adding third.txt
 Committer: Faiza Maouacine <f.maouacine@CARRIERES.LAN>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git log
commit 45393a8245f93f5b94ea9f590a3d2599b0d12c4f (HEAD -> master)
Author: Faiza Maouacine <f.maouacine@CARRIERES.LAN>
Date:   Sun Jan 17 16:08:04 2021 +0100

    adding third.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ touch fourth.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git add fourth.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git commit -m "adding fourth.txt"
[master fc409a4] adding fourth.txt
 Committer: Faiza Maouacine <f.maouacine@CARRIERES.LAN>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fourth.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ rm third.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git add third.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git commit -m "removing third.txt"
[master a20e32c] removing third.txt
 Committer: Faiza Maouacine <f.maouacine@CARRIERES.LAN>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 third.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git log
commit a20e32c42a85d9b1a214c307754db12fce8e4d3e (HEAD -> master)
Author: Faiza Maouacine <f.maouacine@CARRIERES.LAN>
Date:   Sun Jan 17 16:10:32 2021 +0100

    removing third.txt

commit fc409a4fde5b8483dd542dd92ee0714e96e9fd61
Author: Faiza Maouacine <f.maouacine@CARRIERES.LAN>
Date:   Sun Jan 17 16:09:39 2021 +0100

    adding fourth.txt

commit 45393a8245f93f5b94ea9f590a3d2599b0d12c4f
Author: Faiza Maouacine <f.maouacine@CARRIERES.LAN>
Date:   Sun Jan 17 16:08:04 2021 +0100

    adding third.txt

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git config --global core.pager "cat"

f.maouacine@QHSE MINGW64 ~/Desktop/learn_git_again/learn_git_again (master)
$ git config --global --list
core.editor="C:\Users\f.maouacine.CARRIERES\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
core.pager=cat
