
Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git
$ git init
Initialized empty Git repository in C:/Users/Tiberio/Desktop/Estudo Git/.git/

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        meu codigo.txt

nothing added to commit but untracked files present (use "git add" to track)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git add "meu codigo.txt"

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   meu codigo.txt


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   meu codigo.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        senac.jpg
        senhas.xlsx


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git add .

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   meu codigo.txt
        new file:   senac.jpg
        new file:   senhas.xlsx


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git commit -m "commit inicial"
[master (root-commit) f7f1b0a] commit inicial
 3 files changed, 2 insertions(+)
 create mode 100644 meu codigo.txt
 create mode 100644 senac.jpg
 create mode 100644 senhas.xlsx

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git remote add origin https://github.com/tiberiomorais/revisando_git

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ ^C

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push --set-upstream origin master


Logon failed, use ctrl+c to cancel basic credential prompt.
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/tiberiomorais/revisando_git/'

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push --set-upstream origin master
Logon failed, use ctrl+c to cancel basic credential prompt.
error: unable to read askpass response from 'C:/Program Files/Git/mingw64/libexe
Username for 'https://github.com':
Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push --set-upstream origin master
Logon failed, use ctrl+c to cancel basic credential prompt.
remote: Support for password authentication was removed on August 13, 2021. Plea
remote: Please see https://github.blog/2020-12-15-token-authentication-requireme
fatal: Authentication failed for 'https://github.com/tiberiomorais/revisando_git

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push --set-upstream origin master
Logon failed, use ctrl+c to cancel basic credential prompt.
remote: Support for password authentication was removed on August 13, 2021. Plea
remote: Please see https://github.blog/2020-12-15-token-authentication-requireme
fatal: Authentication failed for 'https://github.com/tiberiomorais/revisando_git

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push --set-upstream origin master
Logon failed, use ctrl+c to cancel basic credential prompt.


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push --set-upstream origin master
Logon failed, use ctrl+c to cancel basic credential prompt.
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 114.08 KiB | 12.67 MiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/tiberiomorais/revisando_git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   meu codigo.txt

no changes added to commit (use "git add" and/or "git commit -a")

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git add .

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   meu codigo.txt


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git commit -m "senac/usp"
[master dea4e75] senac/usp
 1 file changed, 4 insertions(+), 1 deletion(-)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 362 bytes | 181.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/tiberiomorais/revisando_git
   f7f1b0a..dea4e75  master -> master

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git reflog
dea4e75 (HEAD -> master, origin/master) HEAD@{0}: commit: senac/usp
f7f1b0a HEAD@{1}: commit (initial): commit inicial

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git reset --hard f7f1b0a
HEAD is now at f7f1b0a commit inicial

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git reflog
f7f1b0a (HEAD -> master) HEAD@{0}: reset: moving to f7f1b0a
dea4e75 (origin/master) HEAD@{1}: commit: senac/usp
f7f1b0a (HEAD -> master) HEAD@{2}: commit (initial): commit inicial

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git reset --hard dea4e75
HEAD is now at dea4e75 senac/usp

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git branch
* master

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git branch staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git branch
* master
  staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git checkout staging
Switched to branch 'staging'

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ git branch
  master
* staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ git status
On branch staging
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   meu codigo.txt

no changes added to commit (use "git add" and/or "git commit -a")

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ git add .

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ git status
On branch staging
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   meu codigo.txt


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ git commit -m "add nome completo"
[staging 71179a2] add nome completo
 1 file changed, 1 insertion(+)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ git push
fatal: The current branch staging has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin staging


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ ^C

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ git push --set-upstream origin staging
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 381 bytes | 381.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'staging' on GitHub by visiting:
remote:      https://github.com/tiberiomorais/revisando_git/pull/new/staging
remote:
To https://github.com/tiberiomorais/revisando_git
 * [new branch]      staging -> staging
Branch 'staging' set up to track remote branch 'staging' from 'origin'.

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ git branch
  master
* staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (staging)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git ?
git: '?' is not a git command. See 'git --help'.

The most similar commands are
        am
        gc
        mv
        p4
        rm

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git b?
git: 'b?' is not a git command. See 'git --help'.

The most similar commands are
        am
        gc
        mv
        p4
        rm

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git bra?
git: 'bra?' is not a git command. See 'git --help'.

The most similar command is
        branch

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git branch
* master
  staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git merge staging
Updating dea4e75..71179a2
Fast-forward
 meu codigo.txt | 1 +
 1 file changed, 1 insertion(+)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$  git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/tiberiomorais/revisando_git
   dea4e75..71179a2  master -> master

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git pull
Already up to date.

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git merge staging
Already up to date.

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push
Everything up-to-date

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git branch
* master
  staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git pull
Already up to date.

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git checkout -b sis_login master
Switched to a new branch 'sis_login'

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git branch
  master
* sis_login
  staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git status
On branch sis_login
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Sistema_de_Login.txt

nothing added to commit but untracked files present (use "git add" to track)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git add .

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git status
On branch sis_login
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Sistema_de_Login.txt


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git commit -m "Criando sistema de login"
[sis_login 439f957] Criando sistema de login
 1 file changed, 2 insertions(+)
 create mode 100644 Sistema_de_Login.txt

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git branch
* master
  sis_login
  staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git pull
Already up to date.

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git merge sis_login
Updating 71179a2..439f957
Fast-forward
 Sistema_de_Login.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Sistema_de_Login.txt

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 404 bytes | 404.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/tiberiomorais/revisando_git
   71179a2..439f957  master -> master

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git branch
* master
  sis_login
  staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (master)
$ git checkout sis_login
Switched to branch 'sis_login'

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git status
On branch sis_login
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Sistema_de_Login.txt

no changes added to commit (use "git add" and/or "git commit -a")
g
Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git add .

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git status
On branch sis_login
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Sistema_de_Login.txt


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git commit -m "add telefone ao sistema de login"
[sis_login 30011da] add telefone ao sistema de login
 1 file changed, 2 insertions(+), 1 deletion(-)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git push
fatal: The current branch sis_login has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin sis_login


Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git push --set-upstream origin sis_login
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 317 bytes | 317.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'sis_login' on GitHub by visiting:
remote:      https://github.com/tiberiomorais/revisando_git/pull/new/sis_login
remote:
To https://github.com/tiberiomorais/revisando_git
 * [new branch]      sis_login -> sis_login
Branch 'sis_login' set up to track remote branch 'sis_login' from 'origin'.

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git status
On branch sis_login
Your branch is up to date with 'origin/sis_login'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        segredos/

nothing added to commit but untracked files present (use "git add" to track)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git branch
  master
* sis_login
  staging

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ touch .gitignore

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git status
On branch sis_login
Your branch is up to date with 'origin/sis_login'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git status
On branch sis_login
Your branch is up to date with 'origin/sis_login'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        plan_secret.xlsx

nothing added to commit but untracked files present (use "git add" to track)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git status
On branch sis_login
Your branch is up to date with 'origin/sis_login'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git add .

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git commit -m "add o arquivo gitignore"
[sis_login fe874d5] add o arquivo gitignore
 1 file changed, 2 insertions(+)
 create mode 100644 .gitignore

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 314.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/tiberiomorais/revisando_git
   30011da..fe874d5  sis_login -> sis_login

Tiberio@DESKTOP-I117JRP MINGW64 ~/Desktop/Estudo Git (sis_login)
$
